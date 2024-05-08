
## Description

Charity is a MERN stack application that allows user to login securely with JWTAuth, explore charities from our curated MongoDB database and add/remove them from their own portfolio. Each portfolio has a user summary and option to download tax forms 1040sa and f8283 for easier filing as well as a Veriti Donation Summary downloadable file in xlsx format. This application was built with Apollo server and uses Express routing. 

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [Installation](#installation)
5. [Technologies](#technologies)
6. [Future Development](#future-development)
7. [Tests](#tests)
8. [Questions](#questions)

## Usage
### User Story

```md
AS A person who values donating a portion of my finances
I WANT the ability to keep track of my donations
SO THAT I can explore and save new charities, donate to them and export donation data for tax filing
```

## Installation
To run this application locally: <br/>
_*this is for development purposes only_

1. Pull down and branch this repository
2. Run ```npm i``` to install all dependencies
3. Seed the database by running ```npm run seed```
4. Make sure to import your own Stripe and MongoDB keys
4. Run the front and back-end servers with ```npm run develop```


<br/>

The following media shows the application's appearance and functionality: 



https://user-images.githubusercontent.com/107900180/208547170-24e93f2d-f24c-446e-8b6a-811f9942d36f.mp4


### How to Use

    1. Create an account
        A. When you first navigate to the home page, you will see a button that says "Start Donating Today" and one that says "Login". Both buttons will lead you to a login page, with a link to sign up if you do not already have an account.
        B. You will be asked to provide a username, your email address, and a password of your choosing.

    2. Login
        A. If you already have an account, simply click "Login" or "Start Donating Today" and enter your credentials.

    3. Explore
        A. Once logged in, you have access to an Explore page, where you will see dozens of 501c3 charities, along with tags to help identify which categories said charities belong to.
        B. You may filter the results based on category to more easily find the charity you're looking for.
        C. If you come across charities that interest you, you can Save them to your portfolio.
        D. You are also able to Donate to a charity directly from the Explore page.

    4. Portfolio
        A. Your Portfolio includes information specific to you. This will hold your saved charities, as well as your donation history.
        B. Your Portfolio will show you how much you have donated towards specific categories.
        C. You will also have access to a downloadable excel spreadsheet with your charities' important tax information, like donation amounts and ein numbers.
        D. You can download tax forms right from your giving Portfolio.
        E. You can also Unsave any saved charities so they will no longer appear on your Portfolio.

    5. Donation
        A. Once you select a charity and click Donate, you will be prompted to enter an amount.
        B. You will then be taken to a Stripe checkout page in which you will need to enter payment information.
        C. This donation informaion will be added to your Portfolio page as well as your downloadable spreadsheet!



## Technologies
* MongoDB
* ExpressJS
* React
* NodeJS
* Apollo
* GraphQL
* JWTAuth
* SheetJS
* Stripe
* Bcrypt
* Dotenv
* Flowbite
* Tailwind
* JavaScript


## Future Development
We would like to continue to add the following functionality to our application:
* Implement donate/save buttons in Recommendation
* Storing donation data in back-end
* Forgot password functionality
* Category questionnaire for user 

## Tests
None

Or visit our app's repository on GitHub:
[charity;](https://github.com/FarooQ-2113/charity)

