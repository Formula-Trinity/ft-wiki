# Wiki Contributing Guide

The FT Wiki is maintained by the team. If you have useful information about your department, subsystem, manufacturing process or competition experience, you are encouraged to add it.

You do not need to know how to code or use Git from the command line. Most changes can be made directly through the GitHub website.

## Before Contributing

You will need:

- A GitHub account
- Access to the [FT Wiki Repository](https://github.com/Formula-Trinity/ft-wiki)

All wiki pages are written using **Markdown** and are stored in the `docs` folder.

**!!WARNING!!**  
Please **do not** edit anything inside the `site` folder, this contains auto-generated HTML files that will be overwritten when wiki is rebuilt! (they should not be on public GitHub anyway...)

## Finding Correct Page

From the [GitHub repository home page](https://github.com/Formula-Trinity/ft-wiki):

1. Open the `docs` folder
2. Navigate to the relevant car, department, subsystem
3. Open/Create the appropriate `index.md` file

For example the FTX7 chassis page is located at:

`docs/ftx7/chassis/index.md`

A specific chassis subsystem may instead be located at:

`docs/ftx7/chassis/subsystem-name/index.md`

Try to put information in the most relevant existing section. If no suitable page exists, you can create a new one.

## Editing an Existing Page

Once you have opened the relevant `.md` file on the GitHub website:

1. Select the pencil icon labelled Edit this file
2. Make your changes in the editor
3. Use the `Preview` tab to check how the page will appear
4. Select `Commit Changes` when you are finished
5. Enter a short description of what you changed
6. Choose to create a new branch for the change, name it something appropriate
7. Select `Propose Changes`

GitHub will then allow you to open a **pull request**. A pull request is just a request for the wiki maintainers to review before your changes are added.

## Opening Pull Request

Give the pull request a clear title, such as:

`Added FTX7 chassis manufacturing notes`

In the description explain briefly:

- What you added or changed
- Why it's useful
- Whether anything still needs to be checked

Your change will not immediately modify the public wiki. A maintainer will review it first and might:

- Approve and merge it
- Suggest changes
- Ask for more information
- Make small corrections

You can continue editing the same files after opening the pull request. Any further commits to the same branch will automatically appear in the existing pull request.

## Using Markdown

Wiki pages are written in Markdown, which is a simple way of formatting plain text.

Markdown is very straightforward once you begin editing, so do not let the syntax overwhelm you. You can also look at existing pages to see how headings, links, images and lists are formatted.

For more detailed advice, which you are unlikely to need, check out the [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
