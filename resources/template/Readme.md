How to create a resource for CMEP
=================================

CMEP resource sources are stored in a folder alongside any assets (images, interactives, etc.) that the resource needs. The resource itself should be written in a text editor using [Pandoc flavour markdown](http://johnmacfarlane.net/pandoc/README.html#pandocs-markdown), or LaTeX with a minimalist set of packages. In either case, delimit mathematics notation with `$` for inline maths or `$$` for display maths.

If you submit a resource in LaTeX, we will use Pandoc to convert it to markdown, and thereafter maintain the markdown copy as authoritative. Authors may wish to [install Pandoc](http://johnmacfarlane.net/pandoc/installing.html) themselves to check that the result is good.

Check List
----------

- Decide on an identifier for the resource. This identifier will be used
to address the resource on the web so avoid characters that require special treatment by selecting from `[a-z]` or `[A-Z]` or `[0-9]` or the underscore character. Do not use spaces. Instead `join_words_together` with the underscore or by making a `CamelCaseIdentifier`.

- Make a folder for the resource, naming it with your chosen identifier.

- Choose a markup language to use - either [Pandoc](http://johnmacfarlane.net/pandoc/) or [LaTeX](http://latex-project.org/guides/).

- Create the main file for the resource, naming it `index.md` or `index.tex`. 

- Place any other asset files in the resource folder. Link to them from the main text using _relative_ links - i.e. by filename only, and not by pathname or full URI.

Multi-part resources
--------------------
These are common for resources that have problem, solution, or teacher support component. 

All parts are in fact rendered into the same index.html page under separate tabs. You must provide a tab name `tab` in the metadata and also a tab `weight`. Tabs are ordered in ascending weight order.

Non-markdown assets (such as images, pdfs, videos etc. must be explicitly linked in to the resource.)

URL for publication
-------------------

Resources will be published at 
`http://cambridge.maths.org/<resourceId>`.

Metadata
--------

Insert metadata in the (final) index.md file. [An example is here](index.md)

Clearance levels are:

*  0: not released
*  1: internal team
*  2: advisors and reviewers
*  3: schools
*  4: public pilot
*  5: public final

Styling for the web
-------------------

We have enabled the pandoc [`raw-html`](http://johnmacfarlane.net/pandoc/README.html#raw-html) option to allow us to surround blocks of markdown with styling commands. We will be using a responsive layout whhich means that pages can reformat themselves to cope with different width devices.

Overall, the web output will use [twitter bootstrap](http://twitter.github.io/bootstrap/) styling. Refer to the examples there for styles that may be applied with HTML wrappers. For responsive layouts, look at the [Fluid grid system](http://twitter.github.io/bootstrap/scaffolding.html#fluidGridSystem) and experiment by reducing the width of your browser window.

###Bootstrap we might use in content

Mostly the bootstrap styling appears in layout HTML templates (see sources/layouts). The list below
is a selection of features that you may want to use _inside_ markdown content.

* [Fluid grid system](http://twitter.github.io/bootstrap/scaffolding.html#fluidGridSystem)
* [Typography](http://twitter.github.io/bootstrap/base-css.html#typography) e.g. for default header styling and 
  - `<div class="lead">`Lead content to an article.`</div>`
* [Wells](http://twitter.github.io/bootstrap/components.html#misc)
  - `<div class="well">`Content in markdown to be styled in a box that stands out from the rest of the text.`</div>`
* [Collapse](http://twitter.github.io/bootstrap/javascript.html#collapse) is very useful for hide/reveal problems. It can be triggered by a button as in the Bootstrap link, or by a link as in
this [jsFiddle example](http://jsfiddle.net/gmp26/gD3Vz/5/). 
* [Float left or right](http://twitter.github.io/bootstrap/components.html#misc). 
* [Icons](http://twitter.github.io/bootstrap/base-css.html#icons)
* [Labels and Badges](http://twitter.github.io/bootstrap/components.html#labels-badges)
* [Hero Unit](http://twitter.github.io/bootstrap/components.html#typography) A very prominent box.
* [Page header](http://twitter.github.io/bootstrap/components.html#typography)
* [Thumbnails and Images](http://twitter.github.io/bootstrap/components.html#thumbnails)
* [Alerts](http://twitter.github.io/bootstrap/components.html#alerts) Useful for warnings or attention grabbing notes.
* [Media object](http://twitter.github.io/bootstrap/components.html#media) for icon, header, decsription. 

###Other Bootstrap styles

The remaining bootstrap styles are not directly applicable to markdown content, though they are applicable to the HTML layouts which which pull in content. They can also apply to the interactive content.

###How to write tables

I'd recommend using Pandoc multiline format tables - even when you only need one line in each cell. They give you more control. Do be careful to insert blank lines where the docs say you should - between each row, and before and after the table.

Here's an example:

  --------------------------
   $a$      $a^4$    $2a^4$ 
  -------- -------- --------
   $0$      $0$      $0$

   $1$      $1$      $2$

   $2$      $6$      $2$

   $3$      $1$      $2$

   $4$      $6$      $2$

   $5$      $5$      $0$

   $6$      $6$      $2$

   $7$      $1$      $2$

   $8$      $6$      $2$

   $9$      $1$      $2$
   ------------------------- 

   Table: _Final digit of 4th powers_

