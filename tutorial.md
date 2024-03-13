# Create and publish OER with GitHub
<section>

We believe that open educational resources can be created using tools the open source community has been successfully using for many years now.
This tutorial guides you through the creation of open educational resources (OER) with GitHub. Using our GitHub template, you can easily create and publish your own OER in just a few minutes.

> This is only a technical instruction. Please make sure to check and regard legal regulations of your country.

## What's in this tutorial:

* [Quick Start (< 5 minutes)](#quick-start)
* [Step-by-step (< 10 minutes)](#requirements)
* [Reference](#reference)
* [Troubleshooting](#troubleshooting)
* [FAQ](#faq)

<br>

## Possible formats for your OER
This tutorial focuses on our template. However, you could also use other formats.

<br>

## LiaScript
![LiaScript](img/preview.png)

<br>

LiaScript is what this tutorial is made with.
All it takes for your OER to be displayed with LiaScript is a Markdown file hosted anywhere and is the quickest and easiest way to your first OER.

[Go to LiaScript](https://liascript.github.io)

<br>

## Markdown documents template
<a href="https://tibhannover.github.io/oer-github-tutorial-template/" target="_blank"><img src="img/template.png"/></a><br><br>

Our Markdown documents template template allows you to quickly host your OER on GitHub Pages with just a few steps.
A web page as well as different formats like PDF and epub are generated automatically with each change to your OER.

You can see this tutorial made with our template here: [Template OER Tutorial](https://tibhannover.github.io/oer-github-tutorial-template/)

[View our template on GitHub](https://github.com/tibhannover/oer-github-tutorial-template/)

<br>

## JupyterBook
<a href="https://smatts.github.io/oer-tutorial-jupyter-book/00_intro.html" target="_blank"><img src="img/jupyterbook.png" /></a><br><br>

JupyterBook is a program that can quickly create customizable books. It even allows to execute Python code in the form of Jupyter Notebooks.

You can see this tutorial made with JupyterBook here: [Jupyter OER Tutorial](https://smatts.github.io/oer-tutorial-jupyter-book/00_intro.html)

[Go to JupyterBook](https://jupyterbook.org)

> After completing this tutorial, you will have an automatically generated OER with your own content and metadata, published on GitHub for free and ready to be put into our OER search index [OERSI](https://oersi.org).

</section>

## Quick Start

If you want to get started quickly, you can follow this quick start tutorial and create a simple OER within just a few minutes.

### 1. Create a GitHub account, if you don't have one yet
> As we will host our OER on [GitHub](https://github.com/), a free GitHub account is required.

If you do not have an account yet, go to GitHub's sign up page and create a free account: [https://github.com/signup](https://github.com/signup).

Afterwards, log into your account.

### 2. Create your project
> Create the place where your OER lies.

<details>

<summary><b>Markdown Documents Template (Click to enlarge)</b></summary>

Go to the [Markdown Documents Template](https://github.com/TIBHannover/markdown-documents-template) and click on the green **Use this template** button, then on **Create a new repository**. This generated your own project (called `repository`).
Assign the repository's owner to yourself (or to a group of your choice, if you are a member of one) and give it a short, but meaningful name that describes your OER. This name will also be the used for the URL to your OER. Optionally add a description.
Make sure that the repository is set to **public**.
Lastly, confirm by clicking on **Create repository from template**.

!?[Create repository from template](videos/create-from-template.mp4)

</details>

<details>

<summary><b>LiaScript (Click to enlarge)</b></summary>

Create a new repository on [GitHub](https://github.com) or [GitLab](https://gitlab.com).
Assign the repository's owner to yourself (or to a group of your choice, if you are a member of one) and give it a short, but meaningful name that describes your OER. This name will also be the used for the URL to your OER. Optionally add a description.
Make sure that the repository is set to **public**.

</details>

<details>

<summary><b>JupyterBook (Click to enlarge)</b></summary>

Go to the [Jupyter OER Template](https://github.com/smatts/jupyter-oer-template/tree/main) and click on the green **Use this template** button, then on **Create a new repository**. This generated your own project (called `repository`).
Assign the repository's owner to yourself (or to a group of your choice, if you are a member of one) and give it a short, but meaningful name that describes your OER. This name will also be the used for the URL to your OER. Optionally add a description.
Make sure that the repository is set to **public**.
Lastly, confirm by clicking on **Create repository from template**. 

</details>

### 3. Fill the project with your content
> Now that you have your own project/repository, you can fill it with your own content.

<details>

<summary><b>Markdown Documents Template (Click to enlarge)</b></summary>

Currently, you have the template's dummy data in your repository. You can edit a file by clicking on the file and then on the edit button. The files you should edit are:

* `chapter01.md`
* `chapter02.md`
* `chapter03.md`
* `chapter04.md`

You can start by edititing `chapter01.md`. Click on the file, the in the top right corner, click on the pen symbol ("Edit this file"). You can delete the file's content and start writing something of your own.

Now, in the top right corner, click on the green "Commit changes..." button. Write a short message on what you have changed ("Commit message"), if you want a longer description, and now click on the green "Commit changes" button.

You can also choose to create or delete files. If you do not want the four chapter files that were created by the template, you can click on the file, click on the three dots on the top right of the file, and then on "Delete file". To upload files, you can click on the "Add file" button in your repository.

</details>

<details>

<summary><b>LiaScript (Click to enlarge)</b></summary>

Create a Markdown file in your repository and fill it with your content.

You can either create the file locally and upload it to GitHub, or create it directly on GitHub.

</details>

<details>

<summary><b>JupyterBook (Click to enlarge)</b></summary>

Currently, you have the template's dummy data in your repository. You can edit a file by clicking on the file and then on the edit button. The files you should edit are:

* `00_intro.md`
* `01_chapter.md`

To edit a file, click on the file. Then in the top right corner, click on the pen symbol ("Edit this file"). You can delete the file's content and start writing something of your own.

Now, in the top right corner, click on the green "Commit changes..." button. Write a short message on what you have changed ("Commit message"), if you want a longer description, and now click on the green "Commit changes" button.

You can also choose to create or delete files. If you do not want the four chapter files that were created by the template, you can click on the file, click on the three dots on the top right of the file, and then on "Delete file". To upload files, you can click on the "Add file" button in your repository.

</details>

### 4. Generate the OER
> The automatic generation will take your content and generate different output formats.

<details>

<summary><b>Markdown Documents Template (Click to enlarge)</b></summary>

Lastly, enable the automatic generation of your OER. To do this, go to the project's `Settings` -> `Pages` and in `Build and Development` set the source to `GitHub Actions`. After this, you can head to the `Actions` tab and click on the newest workflow run. If the worklow already ran, you will find that it failed. This happened because the Pages were not enabled yet. In this case, click on re-run jobs. Otherwise, wait until the jobs have finished. The generated documents are now created.

!?[Pages](videos/pages.mp4)

</details>

<details>

<summary><b>LiaScript (Click to enlarge)</b></summary>

Simply go to the [LiaScript website](https://liascript.github.io) and paste the **raw** URL to your markdown file there. Now LiaScript generates your OER.

</details>

<details>

<summary><b>JupyterBook (Click to enlarge)</b></summary>

To build your book and view it online, you have to enable GitHub pages. To do this, go to the project's `Settings` -> `Pages` and in `Build and Development` set the source to `GitHub Actions`. After this, you can head to the `Actions` tab and click on the newest workflow run. If the worklow already ran, you will find that it failed. This happened because the Pages were not enabled yet. In this case, click on re-run jobs. Otherwise, wait until the jobs have finished.

</details>

### 5. Add your metadata
Go to our [Metadata Generator](https://oersi.gitlab.io/metadata-form/metadata-generator.html) and insert the metadata that describes your OER. In the top right corner, you have the option to switch the language between **German** ("DE") and **English** ("EN").

Once you are done, click on the "Generate" button in the bottom of the page. The metadata is now generated in a format our template understands. Now copy everything to your clipboard. For this, you can click on "Copy".

In your repository, click on the `metadata.yml` file and then on the pen symbol ("Edit this file") to edit the file. Delete the file's contents and paste the metadata from your clipboard. Now click on the green "Commit changes..." button and confirm with "Commit changes".

Now at the bottom of the page, you can click on `Generate`. This generates the metadata in the correct format. You can then copy the output to your clipboard either by using the `Copy` button, or by selecting the whole text (`Ctrl + A`) and copying it (`Ctrl + C`).

!?[Add metadata](videos/metadata-placeholder.mp4)

### Done!
At the front page of your repository, inside the `README.md` content, there are several links you can use to view your generated documents. Click on the `landing page` link to view a page that lists metadata about your OER and supplies several links to different output formats (like a web version, a pdf version, ...).

> To insert your OER into the OER search index [oersi.org](https://oersi.org), head to the `About` section in the index of your repository, click on the settings symbol and add `open-educational-resources` to `Topics`. Your course will be indexed at night and appear on the next day.


## Step by step tutorial
The step by step tutorial consists of the following steps, which you can click through either on the sidebar, using the arrows on the bottom or simply using the arrow keys on your keyboard.

* [Requirements](#requirements)
* [Create a project](#create-a-project)
* [Fill with your own content](#fill-with-content)
* [Generate Output](#generate-output)
* [Add your metadata](#add-your-metadata)
* [Configuration options](#configuration-options)
* [Insert into OERSI](#insert-your-oer-in-oersi)

### Requirements

<section>

> For this tutorial, **you will need a GitHub account**. It is also recommended to **get to know Markdown**, a markup language which can create formatted text using only plain-text, since Markdown is used to write and format your content.
>
> If you already have a GitHub account and know basic markdown syntax, you can skip this part and directly go do [Create a project](#create-a-project).

### Create a GitHub account

If you don't have an account yet, go to [GitHub](https://github.com/) and sign up. Confirm your e-mail address and log in.

### Markdown

From Matt Cone's [Markdown guide](https://www.markdownguide.org/getting-started/):

>Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages.
>
>Using Markdown is different than using a WYSIWYG editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.
>
>For example, to denote a heading, you add a number sign before it (e.g., # Heading One). Or to make a phrase bold, you add two asterisks before and after it (e.g., **this text is bold**). It may take a while to get used to seeing Markdown syntax in your text, especially if you’re accustomed to WYSIWYG applications.

If you want to learn about Markdown, what it is and what you can do with it, you can read this guide: [Get Started](https://www.markdownguide.org/getting-started/).

To see basic formatting options, check out the [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/). More basic syntax can be found in the [Basic Syntax](https://www.markdownguide.org/basic-syntax/) guide.

Some of the basic Markdown syntax is shown in the reference part of this tutorial: [Reference: Markdown](#markdown-1).

</section>

### Create a project

<section>

> The place where you will put your OER is called a `repository`. You can think of it as a project where all your files are located.

Once you are logged into GitHub, go to the [TIB Hannover markdown documents template repository](https://github.com/TIBHannover/markdown-documents-template) and click on "Use this template" -> "Create a new repository".

![Create repository](img/create-repository.png)

Assign the repository to the correct owner and give it a short but meaningful name. The name will be the URL of the repository as well. You can add a description if you want. Now make sure that the visibility of the repository is set to **public**. This has two main reasons: firstly, so people can see your OER, and secondly to use the GitHub pages functionality which we will get to later. Lastly, confim by clicking on "Create repository from template".

Now, a new repository is initialized for you containing the contents from the template.

#### Video tutorial
!?[Tutorial as video](videos/create-from-template.mp4)

</section>

### Fill with content

<section>

> Currently, there is still dummy data inside your repository. The next step is to replace this dummy data with your actual OER.

### How and where to upload your own content

In the repository, you can find four `chapterXX.md` files. These are our dummy content files.
You can either edit or delete them. You can of course create new files, too.
If you create new files, make sure that they end with the correct file format ending `.md`, so `filename.md`.

To edit a file, click on the file name in the index of your repository.

![Change content](img/edit-file-1.png)

Then, in the top right corner of the file, click on the pen button to edit the file.

![Change content](img/edit-file-2.png)

Now, you can replace the content with your own. Add as much as you like.
The file is a `Markdown` file, so you should write your content using this markup language.
You can find more about Markdown in the [Markdown section](#markdown-1) in the reference part of this tutorial.

Once you are done, you can save your changes by clicking on the green `Commit changes...` button in the top right corner.

![Change content](img/commit-changes-1.png)

Add a meaningful but short commit message, which is a message describing the changes you have made, and optionally a longer description.
Then confirm by clicking the green `Commit changes` button.

![Change content](img/commit-changes-2.png)

### What not to do
Using emojis or other unicode characters can break the build.

### Ensuring the correct order

By default, the automatic generator will look for all Markdown files (so those ending with `.md`) in the top-level of the repository except for the `README.md` file, order them alphabetically and create the different output formats by appending them in this order. If you want to upload multiple content files, you will either have to:

* adapt the names of the files so that they will be ordered correctly alphabetically, for example:

  * `01_Introduction.md`
  * `02_Some-Chapter.md`
  * ...
* or you will have to list every file in the correct order in `config.yml`.

You can learn more about that in the [Configuration options](#configuration-options) section in the reference part of this tutorial.

### Why can I not see the updated content?
If you have committed all your changes and still can not see them on your generated landing page and documents, try deleting the cache and reload the page (or open your page in a new private tab). A shortcut to reload and refresh at the same time is `Ctrl + F5`.

Please note that changes can take a few minutes to be built into the generated documents.

If it still does not work, check your document for forbidden characters (such as emojis or other unicode characters) and ensure that the names of your Markdown files do not contain spaces or other unsuitable characters for filenames, as both can break the document generation scripts.

</section>

### Generate output

<section>

> The automatic generation will take your content (everything inside the `Markdown` files, so those ending with `.md`) and generate different output formats. For example, these include a **web page** and a **pdf** version of your OER and are publicly accessible. This generation is done each time you change something in your repository, so your content will always be up to date.

In order to generate the different output formats for your OER, go to the project's `Settings` -> `Pages` and in `Build and Development` set the source to `GitHub Actions`. After this, you can head to the `Actions` tab and click on the newest workflow run. If the worklow already ran, you will find that it failed. This happened because the Pages were not enabled yet. In this case, click on re-run jobs. Otherwise, wait until the jobs have finished. The pages and documents are now created. They can be accessed by the link that appeared under the `deploy` step.

Congratulations, you now have a complete course/document that you can make your own!

#### What are Actions?

> An `Action` is something that GitHub can execute with every commit (save) you make to the repository. This includes the generation of documents or pages, which we are using in this tutorial.
>
> A more detailed explanation of GitHub Actions can be found here: [Understanding GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions).

#### What are Pages?
> A `Page` is a public website hosted by GitHub. We can use GitHub Actions to automatically generate our website and then host it on GitHub Pages for everyone to see. You can either host your site for free on `your-username.github.io` or use your own costum domain.
>
>More information on GitHub Pages can be found here: [About GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages).

### Video tutorial
!?[Actions and Pages](videos/pages.mp4)

</section>

### Add your metadata

<section>

> Metadata is the data describing your OER. This includes information like the title, author, license and much more. If you don't supply metadata with your repository, it is unclear what your OER is about, who it is from, if and how your OER can be used and so on. This is why we have a `metadata.yml` file in our repository. This file lets us include the information about the OER directly in the repository. This is also necessary for inserting your OER into a search index like [OERSI](https://oersi.org). This section shows how to replace the dummy metadata in the repository with the correct metadata describing your OER.

Perhaps the easiest way to generate your own metadata for your repository in the correct format is to use the [OERSI metadata generator](https://oersi.gitlab.io/metadata-form/metadata-generator.html) and fill out at least all required fields, but try to fill out as much as you can.

![Metadata generator](img/metadata-form.png "Metadata Generator")

Now at the bottom of the page, you can click on `Generate`. This generates the metadata in the correct format. You can then copy the output to your clipboard either by using the `Copy` button, or by selecting the whole text (`Ctrl + A`) and copying it (`Ctrl + C`).

![Copy output to clipboard](img/metadata-copy-to-clipboard.png)

In your GitHub repository, edit the `metadata.yml` file. Now delete the whole file content and paste the output of the generator.
To save, click on `Commit changes...` in the top right corner. Confirm by clicking on `Commit changes`.

#### Video: Update the metadata
!?[Update the metadata](videos/metadata-placeholder.mp4)

</section>

### Insert your OER in OERSI
> Let's assume that...
>
> * you have put your whole completed course or document content into the repository, and it's either ordered alphabetically or you have defined the correct order in the `config.yml` file,
> * you have enabled the `Pages` for `GitHub Actions` and there are no errors during Action execution, thus you have a published Page that represents the current version of your repository,
> * you have entered full and correct metadata, ensuring the license is correct and you are not violating another work's license with this license,
> * inside your `metadata.yml` file, you have set your creative work status to `Published` and the educational level to `University`,
>
> **then you are ready to put your OER into OERSI!**

To put your course into the Open Ecucational Resources Search Index (OERSI), head to the `About` settings in the index of your repository. Then in `Topics`, add `open-educational-resources`.

![About settings](img/about.png)

![Set the topic](img/about-topics.png)

The [OERSI](https://oersi.org) updates its index every night. So you will be able to find your OER the next day either through the search bar or by filtering using the filters on the left (e.g. search for your name in `Author` or setting the `Provider` to GitHub to only show OER from GitHub).

If you want to immediately see your changes in the OERSI, you can use the [record updater](https://oersi.org/resources/pages/de/record_update/).

To take the OER out of OERSI, simply set the status (`creativeWorkStatus`) in the `metadata.yml` to `Draft` or `Incomplete` (or alternatively, you could remove the topic `open-educational-resources`).

### Done!
Congratulations, you did it!

If you want to learn more about what you can do with this template, you can continue with the [reference](#reference) part.

## Reference
<!--  style="background-color:#ff5959;" -->
> This part is still under construction.

> You have your OER in different output formats, complete with your own content and metadata and it is even already indexed in [oersi](https://oersi.org),
> but you want to learn more about what you can do with this template?

In this part of the tutorial, we highlight further configuration options, Markdown basics, workflows in GitHub and much more.

* [Configuration options](#configuration-options)
* [Markdown](#markdown-1)
* [Git](#git)
* [Working offline](#working-offline)
* [Immediate update in OERSI](#immediate-update-in-oersi)
* [Different formats](#different-formats)

### Configuration options

<section>

> In the repository, there is a file called `config.yml`. This gives you some configuration options concerning the automatic generation of your OER, like the order of your content.

In the top level of the repository, there is a file named `config.yml`. It includes configuration for these four things:

* `output`: state the output formats that you want to be automatically generated
* `generate_landingpage`: decide whether or not to create a landing page
* `content_files`: define the order of your content files
* `generate_reuse_note`: decide whether or not to generate a reuse note on the generated documents

#### Editing this file

As you are editing this file, you have to consider the format of this file. This file is a `yaml` file. This file has a specific structure you have to follow, or else the automatic generator will not work.

As you can see when opening the file, the structure looks like this:

``` yaml
output:
  - format: asciidoc
  - format: epub
  - format: html
  - format: pdf
generate_landingpage: true
# content_files:  # uncomment this to set the order of the documents (default alphabetical)
#   - chapter01.md
#   - chapter02.md
#   - chapter03.md
#   - chapter04.md
generate_reuse_note: true
```

So we have to consider the identation and the correct symbols to use. If we want to use the `content_files` option, we uncomment this by deleting the `#` before each line and removing the residual spaces:

``` yaml
output:
  - format: asciidoc
  - format: epub
  - format: html
  - format: pdf
generate_landingpage: true
content_files:  # uncomment this to set the order of the documents (default alphabetical)
  - chapter01.md
  - chapter02.md
  - chapter03.md
  - chapter04.md
generate_reuse_note: true
```

The dashes (`-`) have to start with two spaces before the dash and then one space after the dash.
Basically, just make sure the number of spaces is consistent throughout the whole file.

#### Video tutorial
!?[Config file explained](videos/config.mp4)

</section>

### Markdown
> For a good overview on what Markdown is and what you can do with it, you can check out the Markdown guide from Matt Cone:
> 
> * [What is Markdown and why should I use it?](https://www.markdownguide.org/getting-started/)
> 
> * [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

<section>

### Headings

To create a heading, add number signs (`#`) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (`<h3>`), use three number signs (e.g., `### My Header`) [[1](https://www.markdownguide.org/basic-syntax/)].

<!-- data-type="none" -->
| Heading level | How to write it | How it looks |
|---|---|---|
| Heading level 1 | # Heading level 1 | <h1>Heading level 1</h1> |
| Heading level 2 | ## Heading level 2 | <h2>Heading level 2</h2> |
| Heading level 3 | ### Heading level 3 | <h3>Heading level 3</h3> |
| Heading level 4 | #### Heading level 4 | <h4>Heading level 4</h4> |
| Heading level 5 | ##### Heading level 5 | <h5>Heading level 5</h5> |
| Heading level 6 | ###### Heading level 6 | <h6>Heading level 6</h6> |

### Markdown elements
<!-- data-type="none" -->
| Element | How to write it | How it looks |
|---|---|---|
| Bold | \*\*Bold text\*\* | **Bold text** |
| Italic | \*Italicized text\* | *Italic text* |
| Blockquote | > blockquote | To be seen at the top of this section |
| Ordered list | 1. First item <br> 2. Second item | 1. First item <br> 2. Second item |
| Unordered list | - First item <br> - Second item | - First item <br> - Second item |
| Code | \`code\` | `code` |
| Horizontal rule | \-\-\- | --- |
| Link | [Link text](link url) | [Markdown Guide](https://www.markdownguide.org) |
| Image | ![Alt text](image url) | ![Image showing the text placeholder](http://via.placeholder.com/50x50) |

[1] Matt Cone, [markdownguide.org](https://www.markdownguide.org), [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

### Links to other sections

You can link to sections within your document using the link syntax shown in the table above.
The links are generated from the heading:

* `# Heading` -> `#heading` (You can reference it like this: `[Heading](#heading)`)
* `# Heading 1` -> `#heading-1`
* `### Lower heading level!` -> `#lower-heading-level`

You can also set custom links like this:

`## My heading {#custom-id}`

Now the link to this section is `#custom-id`.

</section>

### Git
<!--  style="background-color:#ff5959;" -->
> This part is still under construction.

> This section only gives a brief overview of Git.
> If you want to learn more about it, check out the free online [Pro Git](https://git-scm.com/book/en/v2) textbook.

<section>

### What is Git and why should you use it?
Have you ever worked on different versions of a document, or even with different people?
Then you likely know how hard it is to keep track of changes, and how easy to accidentally overwrite them.
Git is a tool that helps with that. **It is a so-called *version control system*.**
To learn more about version control, you can check out the [Version Control section of the Pro Git book](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).

</section>

### Working offline
<!--  style="background-color:#ff5959;" -->
> This part is still under construction.

<section>

> If you want to work offline, using some kind of text editor (similar to working with Word on documents), some necessary steps and background knowledge are required.

Since we are working with `Git` (see [Git section](#git) for more information), and want to publish our content on `GitHub` (see [GitHub section](#github)), we have to find a way to bring our offline work online. For this, you should check out the [Git section](#git).

### Editors
First off, let's talk about editors.

Of course, you know text editors like *Word* or *LibreOffice*.
However, for the automatic output generation used in this template, we need *plain text* that is easily readable for machines.
This is why we are working with [Markdown](#markdown-1) to format our *plain text*.

There are a lot of editors that help you with writing text using the Markdown syntax.
On of the ways they help is by showing a rendered preview as you type.

![Editor](img/vscode.png "VSCodium, the open source version of the popular editor VSCode")

The editor you can see in the screenshot is called **VSCodium**, which is the open source version of a popular editor **VSCode** by Microsoft.
In this editor, you can install lots of plugins that can help you out.
It also has a built-in Git functionality which helps you publish your changes.

### Put your changes online
Your local changes have to be uploaded.
This brings some possible challenges.

You could simply copy the whole file content, click on edit on the file in the repository that you want to update, delete that file's contents, paste your new content and commit those changes.
But that is rather tedious and unnecessary. Neither is it the way Git is supposed to be used.

We will stick to the *VSCodium*/*VSCode* editor for this example.

</section>

### Immediate update in OERSI
> Your OER will be automatically inserted into the [OERSI](https://oersi.org) if you fulfill the requirements listed in the [insert your OER into OERSI section](#insert-your-oer-in-oersi). The resources are updated each night. If you want to see **immediate** changes, you can use the (experimental) record updater.

Head to the [record updater page](https://oersi.org/resources/pages/de/record_update/) on [oersi.org](https://oersi.org).
Insert the link to your GitHub repository or to the generated landing page of your OER.

![Record updater](img/record-updater.png)

Then, click on update. Your OER should now be updated in the OERSI.

### Different formats

<section>

> After following this tutorial, we have different output formats like a HTML version, a PDF version and so on.
> We could, however, generate all kinds of different formats, for example a course format like this tutorial.

Using this template is not the only option to host OER using GitHub.
For example, this tutorial runs using LiaScript.
Moreover, you don't *have* to use GitHub as your hosting platform - other Git-based platforms like GitLab can be used, too (it is however necessary for most of the formats to have some sort of automated CI pipeline included in the Git hoster).
We currently don't have templates with automated generation for other platforms, though.

Below you find a short list of several possible formats your OER could use. <br><br>

nicht unbedingt github

<h3>[Markdown documents template](https://github.com/TIBHannover/markdown-documents-template)</h3>

This is the template that is described in this tutorial.
As you know by now, it takes your Markdown files, puts them together and generates different formats from them.
These formats are linked to and can be downloaded from the landing page that is generated using GitHub Actions and GitHub Pages.

<!--  style="background-color:#fff;" -->
> ✅ Easy setup with our template
> 
> ✅ Automatic generation of different formats
> 
> ✅ Can include interactive elements
> 
> ✅ Always have the newest changes online
> 
> ✅ GitHub automatically tracks changes made to your files
> 
> ✅ Easy collaboration with others on GitHub
>
> ✅ Customizable with CSS
> 
> ❌ Needs a GitHub account
> 
> ❌ Customizing can be tricky / Limited page layout customization ? textfluss gestaltung


<h3>[Markdown slides template](https://github.com/TIBHannover/markdown-slides-template)</h3>

The Markdown slides template is very similar to the Markdown documents template from this tutorial.
But instead of creating a single text document, the slides template creates several slides.
For this, you create one Markdown file for one set of slides and the template generates the slides in both HTML and PDF format and shows a list of all generated slides together with preview images in a GitHub Page.

<!--  style="background-color:#fff;" -->
> ✅ Easy automatically generated slides in two formats
> 
> ✅ Easy setup with our template
> 
> ✅ Automatic up to date overview page
> 
> ✅ Always have the newest changes online
> 
> ✅ Automatically tracks changes made to your files
> 
> ✅ Easy collaboration with others
> 
> ❌ Slides are only partly customizable
> 
> ❌ Needs a GitHub account

<h3>[LiaScript](https://liascript.github.io)</h3>

LiaScript takes a markdown file and automatically generates a course format from it.
The tutorial you are currently viewing is actually made with LiaScript!
Or rather, the Markdown file this tutorial is written in is being interpreted by LiaScript, which therewith generated this course.
So all you really need is a Markdown file.

<!--  style="background-color:#fff;" -->
> ✅ Super easy to set up, just need one markdown file somewhere on the internet!
> 
> ✅ Runs everywhere 
> 
> ✅ Large number of elements you can use like: ... graphen, tabellen, karten, ...
> 
> ✅ No installation, everything happens live & online
> 
> ✅ Easy to click through the different sections
> 
> ✅ Automatic translation into many different languages
> 
> ✅ Interactive elements and extended Markdown can be used
> 
> ✅ responsive website, good mobile view
> 
> ❌ Only online, no download
> 
> ❌ Depends on one single service
> 
> ❌ Only one Markdown file at a time

<h3>[Static Site Generators](https://github.com/collections/static-site-generators)</h3>

A static site generator generates a static site.
Typically, it will be possible to also write your content using Markdown, but at the same time, you will be able to edit your layout and include more elements yourself which the static site generator then uses to create your web page.
Of course, this requires some basic knowledge about HTML, CSS and the static site generator you are using.
You should also be familiar with the command line or using GitHub Actions yourself.

<!--  style="background-color:#fff;" -->
> ✅ Creates a lightweight web page
> 
> ✅ Very customizable
> 
> ❌ Not for complete beginners - you need some knowledge about web development
> 
> ❌ Takes longer to get a first version running / more configuration and technical know-how necessary

<h3>[JupyterBooks](https://jupyterbook.org/en/stable/intro.html)</h3>

Jupyter Book is a free and open source tool to create online books.
You can create sections and subsections that you can click through.
They are added to a table of contents, which can be viewed in a sidebar or accessed via a menu.
It is also possible to include executable content.
Moreover, you can download your book in both Markdown and PDF format.
You can start out with a template supplied by the software itself.

<!--  style="background-color:#fff;" -->
> ✅ Creates online books with sections and table of contents to click through
> 
> ✅ Allows lots of configuration and structuring
> 
> ✅ Supplies download as Markdown and PDF
> 
> ✅ Can include executable content
> 
> ❌ Not for complete beginners (you will need to run commands from the command line or create a GitHub Action)
> 
> ❌ Configuration is done via config files, which can be tricky to learn if you are unfamiliar with coding

</section>

## Troubleshooting

<section>

Something does not work?
Maybe you find your issue right here.

### I do not see my changes

You have added your content and your metadata but can not see your changes in your landing page and generated documents?
Following these steps might help you.

1. Delete your cache and reload your page/document

Often, the old version of the page is still loaded in your browser's cache.
If you reload the page or document by hitting `Ctrl + F5` together, you can reload your page while deleting the cache of that page.
You can also open your page or document in a new private tab or window, as the browser usually does not use its cache there.

2. Check your file names and content

Check if your file name contains characters like **spaces**. These are not allowed and cause the document generation to break.

Also, ensure that there are no special characters like emojis or other unicode characters in your documents. Our document processor does not understand these characters, which also leads to breaking the document generation.

3. Check your media

Sometimes, images or videos can cause the document generation to break.
Usually, this happens when you use an unsupported format. Stick to widespread formats like `png` and `jpg` to be sure.

</section>


## FAQ

<section>

### Can I upload non-text files like PDF files?
Yes, you can! Git however won't be able to track changes made to those files, it can only track _that_ it was changed.

### How can I change how images are displayed?
You can change image size, placement and more by using HTML-tags. HTML is, like Markdown, a markup language, basically converting plain text into formatted output.

**Change image size**:

`<img src="path/to/image.png" alt="Image description" style="width:100px"; />`

The **src** contains the path to your image, the **alt** contains an image description, and the **style** contains the information about the image size. Here, we have set the **width** to **100 pixels**. You can also set the height (but note that setting a fixed width *and* height that does not match the original ratio of the image can skew it), and of course, change the size how you want.

**Make text float around an image**:

`<img src="path/to/image.png" alt="Image description" style="float: left; margin: 0 20px 20px 0;" />`

Again, **src** contains the path to the image and **alt** its description. Now in the **style** tag, you find two directions: `float: left;` places your image on the left and allows other content like text to *float* around it. The tag `margin: 0 20px 20px 0;` is about spacing: you can set a margin around your image (or element in general), leaving that space blank. Here, the values for the margin are sorted top, right, bottom, left. So in this case, there is a margin of 20 pixels to the right and to the bottom. This prevents the text to directly "touch" your image, making it easier to read.

### Why are the direct paths to my files different?
You may have encountered links containing `https://raw.githubusercontent.com/`. If you are wondering what this means and why GitHub changes your URL this way, the reason is the following:

When you go through your repository's files in GitHub, you see them embedded in the GitHub web page, which lets you do several things like edit, delete, show its history and so on. So when you have a link to this file, the link points to this web page and not to the file itself (which is called the *raw* file). If you want to access the file *only*, so the raw file, GitHub allows you to do that by changing the URL to `https://raw.githubusercontent.com/`.

### How can I create a new folder?
You can not create an empty folder. This means you have to add files in GitHub *in* that new folder. Either create a new file and change the path to that new folder (i.e. instead of creating a new file `file.md`, write it with a new folder like `newfolder/file.md`, a new folder will be automatically created) or upload a non-empty folder.

</section>