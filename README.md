# Project  - E-commerce  

Welcome to my 5th project. This project is a functioning E-commerce Website.

My project will contain HTML, CSS, JavaScript, Python+Django, Relational databases & 
Stripe payments

![GitHub contributors](https://img.shields.io/github/contributors/nikhilkalhan92/Project-5---Ecommerce)
![GitHub last commit](https://img.shields.io/github/last-commit/nikhilkalhan92/Project-5---Ecommerce)
![GitHub language count](https://img.shields.io/github/languages/count/nikhilkalhan92/Project-5---Ecommerce)
![GitHub top language](https://img.shields.io/github/languages/top/nikhilkalhan92/Project-5---Ecommerce)


Link to final Project is here -


# 1 - UX

I was trying to think of an idea that would make me proud for my last project. and it clicked.

When I was younger, I loved Toys! The majority of toys especially the older ones you see are the ones I actually had when I was younger. This is pure nostalgia for me.

Enjoy

# 2 Structure






# 3 Skelton

I used Balsamiq to create my wireframes as this gives the template of the UI. This also shows where all elements will be placed within the screen.

There are 3 versions of each wireframe as one shows the design on a web browser and the other show on a Ipad and Iphone



# 4 Features


# 5 Technologies used

-   [HTML5](https://en.wikipedia.org/wiki/HTML)
    -   The project uses HyperText Markup Language.
-   [CSS3](https://en.wikipedia.org/wiki/CSS)
    -   The project uses Cascading Style Sheets.
-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
    -   The project uses JavaScript.
-   [Python](https://en.wikipedia.org/wiki/Python_(programming_language))
    -   The project uses Python.
-   [Boostrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
    -   The project uses Bootstrap 5.
-   [PostgreSQL](https://www.postgresql.org/)
    -   The project uses PostgreSQL as a database.
-   [Gitpod](https://www.gitpod.io/)
    -   The project uses Gitpod.
-   [Chrome](https://www.google.com/intl/en_uk/chrome/)
    -   The project uses Chrome to debug and test the source code using HTML5.
-   [Balsamiq](https://balsamiq.com/)
    -   Balsamiq was used to create the wireframes during the design process.
-   [GitHub](https://github.com/)
    -   GitHub was used to store the project's code after being pushed from Git.
-   [Stripe](https://stripe.com/gb)
    - Stripe was used to create a payment system



# 6. Development Cycle

I used GitHub pages to deploy my final project. To do this I had to:
1. Login or Sign Up to [GitHub] - https://github.com/nikhilkalhan92/Project-5---Ecommerce
2. Create a new repository named "Project-5---Ecommerce"
3. Once created, click on "Settings" on the navigation bar under the repository title.
4. Choose which folder to deploy from, I used "/root".
5. Click "Save", then wait for it to be deployed. 
6. The URL will be displayed above the "source" section in GitHub Pages.

**HOW TO FORK A REPOSITORY**

### If you need to make a copy of a repository:

1. Login or Sign Up to GitHub.
2. On GitHub, go to nikhilkalhan92/Project-4---Full-Stack.
3. In the top right corner, click "Fork".

### For the final deployment to Heroku, I had to:
1. Uncomment the PostgreSQL databse from my settings.py file.
2. Set debug = False in my settings.py file.
3. Commit and push all files to GitHub
3. In Heroku, remove the DISABLE_COLLECTSTATIC config var.
4. In the deploy tab, go to the manual deploy sections and click deploy branch.

### Project Checklist
Install Django and the supporting libraries
1. Install Django and Gunicorn. Gunicorn is the server I am using to run Django on Heroku.
2. Install support libraries including psycopg2, this is used to connect the PostgreSQL database
3. Install Cloudinary libraries, this is a host provider service that stores images
4. Create the requirements.txt file. This includes the project's dependencies allowing us to run the project in Heroku.

### Create a new, blank Django Project
1. Create a new project
2. Create the app
3. Migrate all new changes to the database
4. Run the server to test

### Setup project to use Cloudinary and PostgreSQL
1. Create new Heroku app
2. Sign into Heroku
3. Select New
4. Select create new app
5. Enter a relevant app name
6. Select appropriate region
7. Select the create app button

### Attach PostgreSQL database
1. In Heroku go to resources
2. Search for Postgres in the add-ons box
3. Select Heroku Postgres
4. Submit order form

### Prepare the environment and settings.py file
1. Create env.py file
2. Add DATABASE_URL with the Postgres URL from Heroku
3. Add SECRET_KEY with a randomly generated key
4. Add SECRET_KEY and generated key to the config vars in Heroku
5. Add if statement to settings.py to prevent the production server from erroring
6. Replace insecure key with the environment variable for the SECRET_KEY
7. Add Heroku database as the back end
8. Migrate changes to new database

### Get static media files stored on Cloudinary
1. Create a Cloudinary account
2. From the dashboard, copy the API Environment variable
3. In the settings.py file create a new environment variable for CLOUDINARY_URL
4. Add the CLOUDINARY_URL variable to Heroku
5. Add a temporary config var for DISABLE_COLLECTSTATIC
6. In settings.py add Cloudinary as an installed app
7. Add static and media file variables
8. Add templates directory
9. Change DIR's key to point to TEMPALTES_DIR
10. Add Heroku hostname to allowed hosts
11. Create directories for media, static and templates in the project workspace
12. Create a Procfile
