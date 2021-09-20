---
title: Paginated Request Task
show_downloads: false
github_url: https://github.com/Moonkid/ios-course/tree/gh-pages/final-test/assets
---

### Goal

Write a "simple" application which displays a news list.

#### App look

app home | news details |
--- | --- 
![](media/1.png) | ![](media/2.png)

*Please ignore top and bottom navigation bars*

#### Requirements

Application's home screen consists of 2 containers, top one displays featured headlines in a horizontal carousel manner, second container is a table view with other articles.

Both table view and horizontal carousel should have an automated `load more` feature a.k.a `endless list`.
(When you reach the end of list a new data should be fetched automatically and new items should be applied to the list end)

On a visible card/cell the next info is displayed:

- Article image (As a background for a carousel card)
- Article title
- Article source
- Publish date

When you tap on an article a details screen should be presented modally if article `content` exists
Article details screen should display next info

- Article image (As a background for a carousel card)
- Article title
- Article source
- Publish date
- Article content

If article doesn't have a `content` to display an article url should be presented using `SafariViewController`.

- Use UIKit or SwiftUI
- For the horizontal carousel use [Top headlines](https://newsapi.org/docs/endpoints/top-headlines) paginated request
- For the table view use [Everything](https://newsapi.org/docs/endpoints/everything) paginated request
- You can use any 3rd party framework or service (Swift Package Manager is preferred)

[//]: [Design](https://dribbble.com/shots/6858644-News-Application)
