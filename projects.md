---
layout: default
title: Projects
permalink: /projects/
---

There are 3 projects that comprise the HTML & CSS 
section of this course. The requirements for each one are described below.

## Project 1: Resume

Students will build an HTML/CSS version of their resume. This
project focuses on HTML for content (paragraphs, headings, etc.) and CSS
for typography (font family, size, weight, color, etc.) and assignments
should demonstrate knowledge of this material. This is a one page
website and does not need to have any navigation.

### Content

The resume should include the following information/sections:

-   Name
-   Contact Info (Phone, Email, Website)
-   Skills
-   Education (At least one entry with the following information)

    -   School Name
    -   Degree
    -   Dates Attended

-   Employment History (At least 2 entries with the following
    information)

    -   Employer
    -   Job Title
    -   Description
    -   Dates

### Production

The HTML and CSS should demonstrate the following techniques:

#### HTML

-   Use of \<section\> tags for each section (Skills, Education,
    Employment History)
-   Use of \<article\> tags for each item with the section (School or
    Job)
-   Skills will be marked up using an unordered list
-   Use the \<link\> tag to link your external stylesheet.
-   Proper use of heading tags (A single h1 with student name, h2 for
    each section heading, h3 for each job/school)
-   Email address in contact information should be linked using an \<a\>
    tag.

#### CSS

-   Font family for body should be declared on the body tag
-   Typographic Styles for paragraphs
-   Typographic Styles 3 levels of headings (h1, h2, h3)
-   Typographic Styles for links (unvisited, visited, hover, active)
-   Typographic Styles for unordered lists

## Project 2: Site Layout

Students will build a basic website layout and produce it using
HTML/CSS. This project is designed to familiarize students with CSS
layout properties such as floating/clearing and positioning.

### Elements

The following elements/sections are required in the layout:

-   Masthead
    -   Logo

    + Tagline
-   Primary Navigation
    + Secondary Navigation as Dropdown Menu
-   Primary Content Area
    -   Level 1 heading
    -   At least 1 paragraph of dummy content
    -   At least 1 link

    + At least one floated image
-   Secondary Content Area/Sidebar
-   Footer
    -   Paragraph with copyright symbol
    -   Paragraph with text only navigation

### Production

The HTML and CSS should demonstrate the following techniques:

#### HTML

-   Container div with id attribute wrapped around entire site
-   Masthead using the \<header\> tag with an id attribute
    -   Logo in a div tag with an id attribute

    + Tagline in a paragraph tag with an id attribute
-   Navigation in a \<nav\> tag with an id attribute
    + Primary/Secondary navigation as list items in a nested unordered
    list
-   Primary and Secondary Content Areas as sections with ids
-   Footer as \<footer\> tag with an id attribute
-   \<link\> tag linking to external stylesheet

#### CSS

-   Use of width and auto margins on container for centering layout
-   Use of id selectors for styling layout elements
-   Absolute positioning for placement of logo/tagline
-   Floats for multi-column layout of primary/secondary content columns
-   Clear for clearing footer
-   CSS for dropdown navigation using [Sons of Suckerfish
    technique](http://www.htmldog.com/articles/suckerfish/dropdowns/)
-   Basic typographic styles for 3 levels of headings, paragraphs and
    links (can be taken from resume)

## Project 3: Photo Gallery

Students will build a photo gallery using HTML and CSS. The
photo gallery will include a display of thumbnail images that are
clickable in order to view a larger size image with an associated title
and description. This project focuses on basic layout and must use
either floats or absolute positioning in CSS to lay out the thumbnails.
Students will use a jQuery Plugin of their choosing (such as a [jQuery
Lightbox plugin](http://fancyapps.com/fancybox/)) to add interactivity
to their assignment.

### Content

Students will include at 10 images in the photo gallery, with two
different versions of each image (thumbnail and full size - the same
image cannot be used as both the thumbnail and full size image).

### Production

Students will build an HTML and CSS version of the Photo Gallery.
The HTML and CSS should demonstrate the following
techniques:

#### HTML

-   Use of src and alt attributes of the \<img\> tag
-   Use of \<a\> tags with href attribute for linking from thumbnail
    images to large versions

#### CSS

-   Use of floats or absolute position for thumbnail layout
-   Customized styling for full size image display

#### Javascript/jQuery

-   jQuery attached to the page using a \<script\> tag
-   Use of javascript such as a [jQuery Lightbox
    plugin](http://fancyapps.com/fancybox/)
