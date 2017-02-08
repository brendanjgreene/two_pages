What our app will do:

1. A user issues a request for a domain’s root URL / to go to its home page
2. two_pages.py maps the URL / to a Python function
3. The Python function finds a web template living in the templates/ folder.
4. A web template will look in the static/ folder for any images, CSS, or JavaScript files it needs as it renders to HTML
5. Rendered HTML is sent back to two_pages.py
6. two_pages.py sends the HTML back to the browser