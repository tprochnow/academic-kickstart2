---
title: Home Page
linktitle: Home Page
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  website:
    parent: 2) Editing Your Site
    weight: 4

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 4
---
Next, we will change some settings for your home page. This will personalize your site (to an extent) and be able to adjust your home page. 

You will need to navigate to `config/_default/params.toml`

## Font and Style

You can decide from a number of font and color options. Feel free to select one, save the document, and see how it looks in the viewer. You can also search for more font and color options through Hugo. 

## Contact Information

While we are in this document you can also edit your contact information that will show up on the bottom of your site. If there is any lines of information you would not like to show up you can "comment it out" by adding # before it. 

## Menu Items

The menu at the top of your page can be edited through the `config/_default/menus.toml` document. Here you can add or remove widgets from the top navigation bar. Using the weights you can rearrange how they show up. Typically you will want your menu to mirror the order of your homepage top to bottom. This also comes with a built in template for adding a link to your CV. Later in this tutorial we will see how to add a CV so make sure this is active now (remove any #). 

## Widgets

Widgets are the segments of your home page that hold content. These are all located in the content/home folder. The Academic theme comes with many helpful widgets which we will edit as we go; however, it is possible to add other widgets or create your own. We will not do so in this tutorial. Next we will get into editing individual widgets.

## Unwanted Widgets

While some of you may love to use every widget given in this current build many might want to remove or make widgets inactive. 

For now we will remove several widgets to clean up the home page. If you see value in these or wish to edit them feel free to disregard this section.  

1. Navigate to the `content/home` folder. 
2. You can deactivate the widget by changing ```active=true``` to ``active=false``. This will make it easy for us to come back and reactivate if you change your mind.
3. We will be deactivating these widgets:
  * `accomplishments.md`
  * `demo.md`
  * `experience.md`
  * `hero.md`
  * `skills.md`
  * `slider.md`
  * `tags.md`
4. Save your document and check your home page for changes. 
