# DSAC-UVA Website

Website for Data Science Analytics Club at the University of Virginia!

## Styling Description

-   [styles.scss](_sass/styles.scss) overrides bootstrap defaults
-   [root.html](_layouts/root.html) is the layout that the index page (entire website) will be using
    -   to implement a new section in the website add the file in [_includes](_includes) with a template similar to below and add the html file to *root.html*:
    ```html
    ---
    <section id="section">
        <div class="container">
            <div class="row">
                <p>Left Aligned Text.</p>
                <div class="col-lg-12 text-center">
                    <p>Center Aligned Text.</p>
                    <h2 class="section-heading">So much to explore!</h2>
                    <hr class="primary" />
                </div>
            </div>
        </div>
    </section>
    ---
    ```
-   [\_includes](_includes) has the sections for the root template

## To-do

[ ] Fix menu styling on mobile screens
