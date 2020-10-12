# course_project

file structure:

/model :contains page layouts
/model/main_page :contains basic layouts to be developed in the first cycle
/model/secondary_page :contains the layouts that will be developed additionally to extend the sitemap (optional)

/pages :contains ready-made website pages. it looks like
    /page/home_page
    /page/hover_cart
    ...
    /page/product_details

    file structure of the page:
    /page/example contains:
    
    1. #source (directory) contsins:
        index.html (not minimized)
        scss (directory) contsins:
            contains multiple files with scss extension   
    2. fonts (directory) (optional)
    3. images (directory)
    4. js (directory)
    5. index.html (minimized file)
    6. style.css (minimized file)

