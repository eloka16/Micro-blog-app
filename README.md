# Micro-blog-app
#####Essentially our app should do the following
Let the user sign in and out with credentials specified in the configuration, only one user is supported.
When the user is logged in, they can add new entries to the page consisting of a text-only title and some HTML for the text.
The index page shows all entries so far in reverse chronological order (newest on top) and the user can add new ones from there if logged in.
We will be using SQLite3 directly for this application because it’s good enough for an application of this size. For larger applications, however, it makes a lot of sense to use SQLAlchemy, as it handles database connections in a more intelligent way, allowing you to target different relational databases at once and more.