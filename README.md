# Web Accessibility Checklist

[![GitHub](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen/) &nbsp; [![Buy Me A Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://www.buymeacoffee.com/brandonhimpfen) &nbsp; [![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; [![Sponsor Project](https://srv-cdn.himpfen.io/badges/sponsor-project/sponsor-project-flat.svg)](https://github.com/brandonhimpfen/donate/blob/main/README.md)

A quick checklist for web accessibility, which also acts as a great beginners' guide.

## Landmarks

```<header role="banner">```

Typically your website's header.

```<nav role="navigation">```

Navigation of your website, which contains navigation links.

```<main role="main">```

The one area where content is primarily focused.

```<article role="article">```

One content item. An example is a single blog post in an index.

```<aside role="complementary">```

Separated content section that supports the main content.

```<footer role="contentinfo">```

Footer that contains information about the document such as website author, website ownership, copyright information, links to legal documents, etc...

```<form role="search">```

Give the end user the ability to search your document or website.

## Language Attribute

```<html lang="en">```

Specify the language of the document.

## Document Outline

Use semantic headings and structure

## Links

Ensure links have a `:focus` state

Ensure links are recognizable, such as by underline and different colour then the text.

## Images

State what the image is about using `alt`

## JavaScript

Unobtrusive Javascript

Use unobtrusive Javascript.

No-JavaScript Alternatives

Provide an alternative for end users who don't have JavaScript enabled or where JavaScript is unavailable.

## Forms

Logical layout

Form controls have `label`

An example would be: ```<label for="name">Your Name:</label> <input id="name" type="text">```.

Don't use `placeholder` attributes instead of the `label` tag

Group related form elements

Group related form elements with `fieldset`.

## Media (Audio and Video)

Provide text transcripts for audio

Subtitles for videos

## Colour and Contrast

Test colour contrast

## Colour Blindness Test

Deuteranopia

Protanopia

Tritanopia

## Testing

Test using a screen reader

Test using only the keyboard
