Introduction, overview, basic tools
================
Steven Moran
(16 January, 2025)

- [Getting started](#getting-started)
- [JMP](#jmp)
- [R](#r)
- [RStudio](#rstudio)
- [What is the difference between R and
  RStudio?](#what-is-the-difference-between-r-and-rstudio)
- [Make sure that RStudio works](#make-sure-that-rstudio-works)
- [Spreadsheets](#spreadsheets)
- [Text editor (optional, but
  suggested)](#text-editor-optional-but-suggested)
- [Other optional programs](#other-optional-programs)
  - [GitHub (optional, advanced)](#github-optional-advanced)
  - [Uploading files to GitHub
    (beginner)](#uploading-files-to-github-beginner)
  - [Accesing GitHub with RStudio
    (advanced)](#accesing-github-with-rstudio-advanced)
  - [Understanding GitHub (advanced;
    optional)](#understanding-github-advanced-optional)

# Getting started

To get started with this course, you will need to
[install](https://en.wikipedia.org/wiki/Installation_(computer_programs))
several software packages and get to know how to use them. Follow all
the steps that you need below, before moving on to [chapter
2](https://github.com/bambooforest/IntroDataScience/3_writing_scientific_reports).

For detailed instruction, see also:

- <https://moderndive.com/1-getting-started.html>

# JMP

[JMP](https://www.jmp.com) is a statistical analysis program that’s easy
to use for visualizing and analyzing data. We will use it for examples
and for fun for some rapid development.

A [free student
version](https://www.jmp.com/en_nl/academic/jmp-student-edition.html) is
available and the University of Miami also provides a free license:

- <https://www.it.miami.edu/about-umit/it-news/made-for-u/sas-jmp-pro/index.html>

Please download it and install it.

# R

This course will use the [R programming
language](https://en.wikipedia.org/wiki/R_(programming_language)) for
our projects. If you are not familar with R, please have a look at the
basics. There are many tutorials out there! Here is a free one from
[DataCamp](https://www.datacamp.com):

- <https://app.datacamp.com/learn/courses/free-introduction-to-r>

Here’s some history about R and a description of what it is used for and
by whom:

- <https://www.datacamp.com/blog/all-about-r>

# RStudio

Install [RStudio](https://www.rstudio.com), unless you are already an R
pro and prefer some other
[GUI](https://en.wikipedia.org/wiki/Graphical_user_interface),
[CLI](https://en.wikipedia.org/wiki/Command-line_interface), or
[computer program](https://en.wikipedia.org/wiki/Computer_program) that
allows you to [create R
markdown](https://rmarkdown.rstudio.com/authoring_quick_tour.html)
reports that will be stored in your GitHub repository. Note: be weary of
automatic spell checking – and presumably grammar checking – in RStudio.

There are a lot of tutorials out there about RStudio. Here are two
useful ones:

- <https://www.youtube.com/watch?v=FIrsOBy5k58>
- <https://www.datacamp.com/tutorial/r-studio-tutorial>

# What is the difference between R and RStudio?

Here is a good description of the difference between R and RStudio:

- <https://moderndive.com/1-getting-started.html>

See in particular Figure 1.1: Analogy of difference between R and
RStudio.

# Make sure that RStudio works

You should see something like this when you open **RStudio**. (You will
not need to open **R** directly.)

<figure>
<img src="figures/1.png" alt="Open RStudio." />
<figcaption aria-hidden="true">Open RStudio.</figcaption>
</figure>

Then create an RMarkdown file.

<figure>
<img src="figures/2.png" alt="Create RMarkdown file." />
<figcaption aria-hidden="true">Create RMarkdown file.</figcaption>
</figure>

Give it a title or leave it “Untitled”. My suggestion call it “README”
(all caps). Then hit OK.

<figure>
<img src="figures/3.png" alt="Give it a title." />
<figcaption aria-hidden="true">Give it a title.</figcaption>
</figure>

Now you should have a basic RMarkdown file, like this:

<figure>
<img src="figures/4.png" alt="Example RMarkdown file." />
<figcaption aria-hidden="true">Example RMarkdown file.</figcaption>
</figure>

Click on the **Knit** button and it will prompt you to save the file.
Save it somewhere on your computer.

<figure>
<img src="figures/5.png" alt="Click on Knit and save the file." />
<figcaption aria-hidden="true">Click on Knit and save the
file.</figcaption>
</figure>

Then RStudio should “knit” (aka
“[compile](https://en.wikipedia.org/wiki/Compiler)”) your RMarkdown file
and display it for you.

<figure>
<img src="figures/6.png" alt="Your report should appear." />
<figcaption aria-hidden="true">Your report should appear.</figcaption>
</figure>

# Spreadsheets

You will also want a [spreadsheet
program](https://en.wikipedia.org/wiki/Spreadsheet), so that you can
look at and manipulate data in [tabular
formats](https://en.wikipedia.org/wiki/Table_(information)). Here are
some options:

- [Microsoft Excel](https://en.wikipedia.org/wiki/Microsoft_Excel)
- [Numbers](https://en.wikipedia.org/wiki/Numbers_(spreadsheet))
- [OpenOffice](https://en.wikipedia.org/wiki/Apache_OpenOffice)

Here is an excellent introduction to Excel (“You Suck at Excel with Joel
Spolsky”):

- <https://www.youtube.com/watch?v=0nbkaYsR94c>

It is quite long and detailed and will be more advanced than what we
will do.

# Text editor (optional, but suggested)

You may need a good [text
editor](https://en.wikipedia.org/wiki/Text_editor) to access and edit
[plain text](https://en.wikipedia.org/wiki/Plain_text). Please try to
understand the difference between plain text and so-called [rich
text](https://en.wikipedia.org/wiki/Formatted_text). For example, a good
text editor is not [Microsoft
Word](https://en.wikipedia.org/wiki/Microsoft_Word) – MS Word is a good
rich text editor. Depending on your computer’s [operating
system](https://en.wikipedia.org/wiki/Operating_system), you might
consider for example:

- [BBEdit](https://en.wikipedia.org/wiki/BBEdit):
  <https://www.barebones.com/products/bbedit/>
  ([macOS](https://en.wikipedia.org/wiki/MacOS))
- [Notepad++](https://en.wikipedia.org/wiki/Notepad%2B%2B):
  <https://notepad-plus-plus.org> ([Microsoft
  Windows](https://en.wikipedia.org/wiki/Microsoft_Windows))

If you are using some form of
[Linux](https://en.wikipedia.org/wiki/Linux) you probably already know
what you’re doing.

Note: there are many other plain text editor software programs out
there. [LMGTFY](https://www.dictionary.com/e/slang/lmgtfy/):

- <https://www.google.com/search?&q=best+plain+text+editors>

# Other optional programs

If you’ve gotten this far, you have everything you need for this course.
Here are some optional software programs.

This means, you don’t need to go further unless you want to do more
advanced things in this course. Probably best to talk to me if you’re
interested.

## GitHub (optional, advanced)

Your final data practical may be uploaded to your GitHub repository
(your README.Rmd and README.md files along with any plots, images,
etc.).

If you are new to [software
repositories](https://en.wikipedia.org/wiki/Software_repository) you may
leave this step until the end of the course, although I encourage you to
jump in early because repositories can be used to save your work in the
cloud and to share it with others for input and collaboration.

Create a [GitHub](https://en.wikipedia.org/wiki/GitHub) account:

- <https://github.com>

In your GitHub account, e.g. mine is <https://github.com/bambooforest>,
create a repository for your data practical. It is up to you if you
choose to have the repository public or private.

If you choose private, you will have to add in the settings the GitHub
username of anyone and everyone that you want to give access to it. If
you go private, you will have to give me access so that I can grade the
data practical. If you go public, think about which [software
license](https://en.wikipedia.org/wiki/Software_license) is to be
associated with your repository. GitHub gives you a list to choose from,
including [creative commons
licenses](https://creativecommons.org/licenses/). Choose wisely!

Since one of the [two hardest things in Computer Science (and Data
Science)](https://martinfowler.com/bliki/TwoHardThings.html) is “naming
things”, you may either spend some time coming up with a repository name
that you like (and ideally that makes sense) or you can simply call it
IntroDataScience. You can always change it later! (Caveat: but then you
must update the URL in the [repositories
tab](https://docs.google.com/spreadsheets/d/1di-H7lsmdkT1RJlsXERkIcBSE4Y6XKIwPdulyaZ13DM/edit#gid=788106030&range=A1)
and to tell anyone else you may have shared the URL with – another
reason why naming things is hard: changing names, whether variables in
code, URLs, physical addresses, etc., **causes more work for you and for
others**!).

In your data practical repository for this course, you will create a
[README markdown file](README.Rmd), which you will “knit” into a
markdown file (.md). Both files must be uploaded to your GitHub
repository. By naming it README.Rmd, it will display nicely in the
browser.

Pro-tip: when you initially create a [GitHub
repository](https://docs.github.com/en/get-started/quickstart/create-a-repo),
if you check the appropriate settings, an empty `README.md` file is
created for you. Go ahead and
[edit](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)
it.

## Uploading files to GitHub (beginner)

The most basic way to upload files to GitHub is through the browser by
clicking the `Upload files` button and dragging the file into the
browser window, when prompted:

<figure>
<img src="figures/upload.png" alt="Upload to GitHub." />
<figcaption aria-hidden="true">Upload to GitHub.</figcaption>
</figure>

## Accesing GitHub with RStudio (advanced)

For advanced users, you can access your GitHub repository from within
RStudio by using Git in RStudio.

If you have not yet cloned your repository, follow these steps:

1.  Click on the green “Code” button on your Github repository and copy
    the URL.
2.  Open RStudio, and go to File \> New Project \> Version Control \>
    Git, and paste in the URL that you copied. Under “Create Project as
    Subdirectory of”, browse and select a folder on your computer where
    you want the course materials to go.
3.  Click on “Create Project”. This will create a folder called that has
    the name of the repository that you have cloned.
4.  You can open this as a project in RStudio by using the projects tab
    in the upper right of RStudio. Alternatively, try File \> Open
    Project and then navigate to the folder where your repository is.
    Then open the R project file, i.e., name-of-your-project.Rproj.

If you have already cloned your repository to your computer, you can
nevertheless associate the directory of your local repository with
RStudio:

1.  In RStudio, go to File \> New Project \> Existing Directory, and
    then navigate / click on the your repository’s directory.
2.  Click on “Create Project”.
3.  Follow step 4 above.

Here some information about RStudio projects:

- <https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects>

## Understanding GitHub (advanced; optional)

For those who want to know more about GitHub and [version
control](https://en.wikipedia.org/wiki/Distributed_version_control),
here are some tutorials (but there are many more on the web and you are
not expected to go through them all!):

- <https://docs.github.com/en/get-started/quickstart/hello-world>
- <https://www.youtube.com/watch?v=fQLK8Ib_SKk>
- <https://resources.github.com/whitepapers/github-and-rstudio/>
- <https://happygitwithr.com/index.html>
- <https://kbroman.org/github_tutorial/>
- <https://lab.github.com>

You need a basic understanding of how to use GitHub, i.e., how to access
it, how to add, edit, and remove files from it, if you want to use the
features that make working with repositories great (e.g., collaborative
coding).

There are other advanced methods that we can discuss in class, but that
are not required to do the work in this class, e.g.:

- <https://guides.github.com/activities/forking/>

That being said, putting a bit of extra effort into understand methods
like
[forking](https://en.wikipedia.org/wiki/Fork_(software_development))
will not only help you better understand common practices in data
science and software engineering, but also allow you to access and
collaborate with [over 200 million
repositories](https://en.wikipedia.org/wiki/GitHub):

- <https://docs.github.com/en/get-started/quickstart/github-flow>

There are a number of good
[GUIs](https://en.wikipedia.org/wiki/Graphical_user_interface) for
working with GitHub. For example:

- <https://gitup.co>
- <https://desktop.github.com/>
- <https://acodez.in/git-gui-clients/>
