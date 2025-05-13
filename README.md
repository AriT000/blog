# ClearBlog: 
### A Blogging App for the Modern User

<br>

### The Challenge:
In our modern world, social media has taken center-stage and continues to be a primary source for sharing information. How can we facilitate better connections in a digital environment?  
<br>
---
### The opportunity:
That is where our app comes in. ClearBlog will provide users the ability to share their thoughts and ideas in a simple to use interface. By utilizing Ruby as our primary language, we are able to provide functionality at little cost. That way, we can focus on providing users with a straightforward, no-frills social media platform.
<br>
---
### Main Functionality:
- Visitors can read blog posts
- Login for admin
- Rich text editor (Bold, Italics, etc.)
- Admin can create, edit, and delete blog posts
---
### Steps
1. Prerequisites:  
- Ruby 3.4.3 (installed via rbenv)  
- Rails (`gem install rails`)  
- PostgreSQL (`sudo apt install postgresql libpq-dev`)  
- Node.js  

2. Set up PostgreSQL user  
- Create a PostgreSQL role (`sudo -u postgres createuser --superuser postgres`)  
- Set a password (`sudo -u postgres psql -c "\password postgres"`)  

3. Clone repo/set up app  
- clone the repo (`git clone https://github.com/AriT000/Blog.git"`)  
- cd into it (`cd blog`)  
- bundle install  

4. Start app  
- start the server (`bin/dev`)  
