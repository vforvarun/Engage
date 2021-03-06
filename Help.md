# Instructors GitHub Help

This page contains information on how to add or update content within the Engage repository.

* [Page Content Format](#page-content-format)
* [Edit Page Content](#edit-page-content)
* [Create New Page](#create-new-page)
* [Create New Directory](#create-new-directory)
* [Delete Page](#delete-page)
* [Octotree](#octotree)

## Page Content Format

GitHub uses [Markdown](https://en.wikipedia.org/wiki/Markdown) for authoring content. After updating a page with Markdown the page is rendered via GitHub to an easily readable format.

See [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) for further details.

Quick Reference:

```

# This is an <h1> header tag
## This is an <h2> header tag

_This will be italic_
__This will be bold__

* Unordered list item
  * Unordered sublist item

1. Ordered list first item
1. Ordered list second item (the 1. is not a typo)
   1. Ordered list sublist item

[Hyperlink Text](http://hyperlink.target)

![Embedded image hover text](http://link.to.image.png)

[![Clickable image](http://image.png)](http://link.target)

> Quote

Inline code with a single `back tick`.

Block code with three back ticks to open the block and three to close the block.

```

## Edit Page Content

1. Ensure you are looking at a file in the repository and not a directory.
1. Click the `Edit this file` button that looks like a pen 🖊️.
1. Add or change the content using [Markdown format](https://guides.github.com/features/mastering-markdown/).
1. Click `Commit new file` at the bottom of the browser window.

## Create New Page

1. Go to the parent directory within the repository.
1. Click the `Create new file` button.
1. Type the page name with the extension `.md` eg: `notes.md`.
1. Click in the content section and add content using [Markdown format](https://guides.github.com/features/mastering-markdown/).
1. Click `Commit new file` at the bottom of the browser window.

## Create New Directory

1. Go to the parent directory.
1. Click the `Create new file` button.
1. Type in the directory name.
1. Type a forward slash `/`.
1. Type `README.md`.
1. Click in the new README page and add content using [Markdown format](https://guides.github.com/features/mastering-markdown/).
1. Click `Commit new file` at the bottom of the browser window.

## Delete Page

1. Ensure you have selected the page and not a directory.
1. Click the `Delete this file` button that looks like a little bin 🗑️.
1. Click `Commit changes` at the bottom of the browser window.

## Delete Directory

To delete a directory delete all the files contained within the directory. Directories don't technically exist within Git, only file paths.

Alternatively use [Git](https://git-scm.com/) to clone the repository and work with it locally.

## Octotree

This is not required however the browser extension called [Octotree](https://github.com/buunguyen/octotree) will make it easy for you to navigate the contents of any repository on GitHub.

Click one of the links below to add to your browser:

* [FireFox](https://addons.mozilla.org/en-US/firefox/addon/octotree/)
* [Chrome](https://chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagc)
* [Opera](https://addons.opera.com/en/extensions/details/octotree/)

## Gitpod

One-Click Online IDE for GitHub

As with Octotree, Gitpod is not required. If you wish to make major changes to any GitHub repository you can either clone the repository to your desktop, or try Gitpod. Gitpod allows you to edit the repository in the browser using the Visual Studio Code application.

Visit [Gitpod](https://www.gitpod.io/) or install the [browser extension](https://addons.mozilla.org/en-US/firefox/addon/gitpod/).


