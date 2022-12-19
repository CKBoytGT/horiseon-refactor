# Horiseon Refactor

## Description

Refactor of marketing agency Horiseon's landing page with a focus on accessibility and best practices.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes Made

* Used semantic HTML elements to organize the page content.
* Consolidated repeated CSS rulesets.
* Reorganized stylesheet for more logical flow.
* Added helpful comments to HTML and CSS.
* Added accessible alt attributes to all images.
    * For the hero image, aria-label and role attributes were used in accordance with [this article](https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html).
* Corrected the heading hierarchy while still maintaining the original font size.
* Added a descriptive title.
* Fixed the broken Search Engine Optimization navigation link.
* Resized and compressed images to lower file size and load time without sacrificing image quality or deviating from the intended page design.
    * Would need to confirm with client that this change is acceptable, as it was not part of the original scope.

## Screenshot

![Screenshot of Horiseon website.](/assets/images/horiseon-screenshot.jpg)

## Link

Pending.