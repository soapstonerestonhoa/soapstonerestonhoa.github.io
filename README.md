# Summary

> If you're just here to add/update content, skip to the next section.

The purpose of this repository is to establish a simple web presence for the Cluster.  All of the content is purposefully flat to keep things as simple as possible.

This repository is publicly exposed via [GitHub Pages](https://pages.github.com/).  The link for the site is https://soapstonerestonhoa.github.io/.

The site is built using a static site generator called Jekyll.  Below are some details about Jekyll:

1. [Setting Up a GitHub Pages Site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
2. [Jekyll](https://jekyllrb.com/)

Most of the content is rendered using basic Markdown.  If you only want to output plain text with no formatting, then the Markdown will be "invisible" to you and it will be like typing in a very simple word processor. If you want to add some extra formating, then this is a great [reference](https://www.markdownguide.org/basic-syntax/).

# Adding and Updating Content

> There is no way to break the site.  All changes are tracked and can be undone.  If something doesn't work or look right, then the absolute worst case is that you look at the version [history](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/viewing-the-branch-history) and undo a change.

## Modifying the Landing Page

If you want to modify the initial landing page, the file is here - https://github.com/soapstonerestonhoa/soapstonerestonhoa.github.io/blob/main/home.md.

## Editing an existing page

To edit an existing page, just find the markdown (.md) file, click the edit, and make the necessary edits.

## Adding a new page
 
 1. Navigate to the folder that corresponds to the type of page needed (_docs for side navigation vs _pages for no side navigation)

 > See [Editing Tips](#editing-tips) below for examples of this difference
  
 2. Click "Add file" and name the file including the .md extension

> It is easiest to copy the content from an existing file in the same folder and make changes to the newly created copy vs starting from scratch.
   
 3. Add the "front matter" for navigation purposes
 4. Add the desired content

## Saving Changes

When happy with edits, "save" the file by Commiting the changes.  It's okay to leave all values as the default on the "Commit changes" tab.  The changes will display on the public site after a few minutes.

## Editing Tips

- When editing, you can switch between the raw version and what it will look like when the Markdown is rendered by using the "Preview" tab.  

 - For pages that need a side navigation, look within the "_docs" folder.  An example of a page that uses this is https://soapstonerestonhoa.github.io/handbook/overview/.

 - For pages that do not need a side navigation bar, look within the "_pages" folder.  An example of a page that uses this is https://soapstonerestonhoa.github.io/faq/.
 
 - Other advanced edits are possible with some deeper configuration changes.

