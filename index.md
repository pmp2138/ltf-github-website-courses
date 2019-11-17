Git for course deployment and websites
======================================

November 18, 2019

Lectures and slides
-------------------

-   [Introduction to Git and
    Github](lectures/git-github/intro-git-github.html) : tools to
    collaborate and update content.
-   [Using pandoc to automatically generate websites, presentations, and
    notes](lectures/pandoc-website/generate-materials.html) : convert
    simple, portable, and accessible text formats to
    "prettier" representations.

Instructions for contributing
-----------------------------

Only modify the markdown (`.md`) files, not the html or any other files.

Resources
---------

-   [Git](https://git-scm.com/) : version control software that manages
    projects and allows many people to contribute to a project.
-   [Github](https://github.com/) : a Microsoft-owned web platform that
    hosts Git-managed projects and provides tools for users to raise
    issues and questions on projects and merge thier own changes to
    a project.
-   [Markdown](https://en.wikipedia.org/wiki/Markdown) : a simple plain
    text document format that is very portable and easy to modify.
-   [Pandoc](https://pandoc.org/) : tool to convert to and from many
    file formats. For example, it can generate PDFs, websites, and
    presentations from Markdown text files.

### Tools to automate content generation; e.g. "build tools" (these might be OS-specific)

1.  GNU/Linux and Mac OSX

    -   [Gnu Make](https://www.gnu.org/software/make/) : simple tool
        that automatically detects changes in source materials and
        re-compiles dependencies. In our examples, this involves
        automatically "compiling" websites and presentations using
        Pandoc whenever there are changes to the Markdown files.

2.  Windows

    -   **Any help from Windows users on what is used?** Could install
        `make` with Cygwin, but seems overly complicated.

### Alternatives

-   [Gitlab](https://about.gitlab.com/) : an alternative to
    Microsoft's Github. A (possibly biased) comparison with Github is
    available on [Gitlab's
    website](https://about.gitlab.com/devops-tools/github-vs-gitlab.html).
-   [Shake Build](https://shakebuild.com/) : an alternative to Make with
    a little bit more of a learning curve but with more features and the
    benefits of access to a full programming language in Haskell.
    I (Adam) use this primarily, mostly because I use Haskell primarily.
    Many other languages also have build systems, and it can be
    beneficial to use a build system embedded in the language you
    prefer (e.g. [SCons](https://scons.org/) in Python,
    [Rake](https://ruby.github.io/rake/) in Ruby).
-   [Org mode](https://orgmode.org/) - an alternative to Markdown with
    advanced personal organizational tools integrated into the Emacs
    text editor.

Tutorials
---------

-   [Github Hello
    World](https://guides.github.com/activities/hello-world/) :
    introduction to Github, and no text editor even required!
-   [Git tutorial](https://git-scm.com/docs/gittutorial) : in depth
    introduction to Git
-   [Pandoc Getting Started](https://pandoc.org/getting-started.html) :
    very thorough and accessible introduction to using Pandoc.
-   [Try Pandoc Online](https://pandoc.org/try/) : simple web
    application that lets you convert text between many formats. Also
    shows the corresponding Pandoc command for each conversion.

Pros and Cons of Github for course deployment and website design
----------------------------------------------------------------

### Pros

-   some help here?

### Cons

-   some help here?

Misc contributions and/or feedback
----------------------------------

-   any random thoughts or contributions put here

The [Center for Teaching and learning](https://ctl.columbia.edu/) (CTL) and this workshop
-----------------------------------------------------------------------------------------

This event is sponsored by the **Lead Teaching Fellowship**, which is a
professional development program for graduate students at Columbia
University committed to advancing pedagogy.

The CTL has a lot of great programming that I would recommend for anyone
interested in teaching. Specific for doctoral students, there is the
[CTL Teaching Development
Program](https://ctl.columbia.edu/graduate-instructors/programs-for-graduate-students/ctl-teaching-development-program/),
the [Lead Teaching
Fellowship](https://ctl.columbia.edu/graduate-instructors/opportunities-for-graduate-students/lead-teaching-fellows/)
(sponsered this event), the [Teaching Observation
Fellowship](https://ctl.columbia.edu/graduate-instructors/opportunities-for-graduate-students/teaching-observation-fellows/),
and [Teaching Assessment
Fellowship](https://ctl.columbia.edu/graduate-instructors/opportunities-for-graduate-students/teaching-assessment-fellows/).
If you are interested in any of the fellowships, I think enrollment in
the Teaching Development Program would strengthen your application.