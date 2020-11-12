# DSAC-UVA Website

Website for Data Science Analytics Club at the University of Virginia!

## Styling Description

-   [styles.scss](_sass/styles.scss) essentially is the master css file for the website
-   [root.html](_layouts/root.html) is the layout that every page is based on currently
    -   to implement a new page in the website add the file in [_areas_](_areas) with the following at the top:
    ```html
    --- layout: root title: Title permalink: /title/ description: "description"
    ---
    ```
-   [\_includes](_includes) has the standard content for every page on root template
