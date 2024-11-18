# WEB Technologies 2 (Back End) Final Exam

This project is a portfolio platform about pets named 'Pawfolio'. It gives you the opportunity to post something about your pet, view pictures of dogs and cats to relieve stress and view a calendar for interesting holidays.         

---

## Table of Contents
- [Installation](#Installation)
- [API usage details](#API-usage-details)
- [Key design desicions and features](#Key-design-decisions-and-features)
  
---

## Installation

---

### Prerequisites:
1. Visual Studio Code (https://code.visualstudio.com/download)
2. Node.js (https://nodejs.org/en)
3. MongoDB (https://www.mongodb.com/try/download/community)
4. MongoDB Compass (https://www.mongodb.com/try/download/compass)
5. MongoDB Shell (https://www.mongodb.com/try/download/shell)

Now, clone the repository
git clone https://github.com/aruzhq/WT-2-Final.git

Navigate to the project directory, install dependencies.

---

## API-usage-details

### APIs:
1. The Dog API - https://thedogapi.com/
   Choose 'Get your API key', then get free access. Enter your email, write about the app (I wrote sentences what are in the beginning of this file) and choose the type of project. Click on 'I would like to receive occasional emails about new features and updates'. Then you will receive email from aden@thatapiguy.com with your API key.
2. The Cat API - https://thecatapi.com/
   To get your API key you need to do the same thing as in Dog API, but on another link.
3. Calendarific API - https://calendarific.com/
   Sign up on the site, click on Dashboard (when you hover the cursor over the profile) and get your API key.

---

## Key-design-decisions-and-features

### Security:
1. Passwords hashed using bcrypt.
2. JWT-based authentication with session cookies.

### Role-based access control:
Distinction between admin and editor roles ensures secure and efficient management.

### Notifications:
Welcome emails for new users with Nodemailer's help.

### CRUD operations for portfolio items: 
Admin can create, delete and update items. Editors can ONLY create them. 

### Integration of two APIs:
1. The (Cat/Dog) API
2. Calendarific API
   
### User-friendly interface

### Database connection







