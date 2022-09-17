# Shop For Home Project Documentation

## Introduction

This document aims to give a brief description about E-Commerce web application using Angular, Spring Boot and Postgresql. The main aim of this project is to build an E-commerce website of home décor items in the Covid situation where all the offline shops are closed. E-commerce is fast gaining ground as an accepted and used business paradigm. More and more business houses are implementing web sites providing functionality for performing commercial transactions over the web. It is reasonable to say that the process of shopping on the web is becoming commonplace. The objective of this project is to develop a general purpose e-commerce store where product like clothes can be bought from the comfort of home through the Internet. However, for implementation purposes, this paper will deal with an online shopping for clothes. An online store is a virtual store on the Internet where customers can browse the catalog and select products of interest. The selected items may be collected in a shopping cart. At checkout time, the items in the shopping cart will be presented as an order. At that time, more information will be needed to complete the transaction. Usually, the customer will be asked to fill or select a billing address, a shipping address, a shipping option, and payment information such as credit card number. An e-mail notification is sent to the customer as soon as the order is placed.

## Problem Statement

During this pandemic time it has been difficult to shop offline with the fear of spreading of corona virus. Hence many offline home décor shops have been closed due to no visitors. Almost all small businesses have been paused due to the pandemic. Hence there must be a way created for these small businesses to run even in these pandemic times so that they don’t have to bear huge loss.
Shop For Home is a popular Store in the market for shopping the home décor stuff .Due to Covid 19 all the offline shopping stopped. So, the store wants to move to the online platforms and wants their own web application. 
There are 2 users on the application: 
1.User 
2.Admin

## Problem Definition

E-commerce provides an easy way to sell products to a large customer base. However, there is a lot of competition among multiple e-commerce sites. When users land on an e-commerce site, they expect to find what they are looking for quickly and easily. Also, users are not sure about the brands or the actual products they want to purchase. They have a very broad idea about what they want to buy.

## Objectives

The primary goal of e-commerce is to reach maximum customers at the right time to increase sales and profitability of the business. Functions of e-commerce include buying and selling goods, transmitting funds or data over the internet.
The three main objectives are as follows
1.Find the best solution for their needs
2.Make a purchase, and
3.Get information/answers to their questions

## Product Perspective

Home décor shop is aimed towards the vendors who want to reach out to the maximum cross-section of customer and common people who can be potential customer. This project envisages bridging the gap between the seller, the retailer and the customer. OFS should be user- friendly, ‘quick to learn’ and reliable software for the above purpose. OFS is intended to be a stand-alone product and should not depend on the availability of other software. It should run on both UNIX and Windows based platform

## User classes and characteristics

The user should be familiar with the Shopping Mall related terminology like Shopping cart/Checking out/Transaction etc.
The user should be familiar with the Internet.

## Operating Environment

The product will be operating in windows environment. Home décor online shop system is a website and shall operate in all famous browsers, for a model we are talking Microsoft Internet Explorer, Google Chrome and Mozilla Firefox. Also it will be compatible with the IE 6.0. Most of the features will be compatible with the Mozilla Firefox and Opera 7.0 or higher version. The only requirement to use this online product would be the internet connection. The hardware configuration include Hard Disk: 40GB, Monitor: 15 inch Color monitor, Keyboard: 122 keys. The basic input devices required are keyboard, mouse and output devices are monitor etc.

## Overview

A E-commerce website that allows people to buy and sell physical goods, services, and digital products over the internet rather than at a brick-and-mortar location. Through an e-commerce website, a business can process orders, accept payments, manage shipping and logistics, and provide customer service.

## Product Functions

### 1. User-Friendly Design 

Perhaps the most important feature customers want in an ecommerce site is a good user experience. If your customers can’t find their way around your website or they struggle to find what they’re looking for, they will likely move swiftly on to one of the many other online retailers. Utilize ecommerce UX best practices. Prioritize customer experience by: Creating a simple, straightforward, high-quality homepage. Including a search bar. Clearly listing category pages in the navigation bar. Focusing on creating a responsive website. 14 Modern Website Design Trends for 2022 

### 2. Mobile-Friendly Features

In the modern marketplace, ecommerce consumers are increasingly reliant on their mobile devices. According to SaleCycle, mobile devices were used in 56% of all online purchases in 2020. In other words, most customers want to browse online stores on their phones, so including mobile optimization in your ecommerce website design is vital. Ensure your web design is automatically modified for the screen size and shape of phones to increase your conversion rate and keep customers happy. 

### 3. Multiple Payment Options 

Shopping cart abandonment is often a big issue for online retailers. To improve your chance of sealing the deal in the final checkout process on your website, be sure to make the purchasing stage as easy as possible for your customers by offering multiple online payment methods in the shopping cart. In addition to offering debit and credit card options, consider adding options for payment providers like PayPal or Stripe. You could also add plugins that have a buy now, pay later functionality to encourage customers to press the “purchase” button. 

### 4. 24/7 Customer Service 

A big part of a successful customer experience is providing helpful, accessible customer service. According to Microsoft, 90% of Americans consider customer service an important feature when deciding whether or not to purchase from a company. Include a 24/7 customer service chatbot as one of your ecommerce website features to address customer needs at any time. Plugins like Zendesk or LivePerson make it easy for you to add this feature to your website for a small fee.

### 5. User Discounts Customers

To feel that they’re getting a good deal and being treated differently from other customers. Offer personalized deals, offers, and other user features to give them this type of attractive, customized experience. Offer user accounts where customers can access loyalty pricing offers, their personalized wishlist, and account history. You can also use an ecommerce platform automated emailing system to send targeted special offers to loyal customers. 

### 6. Extensive Product Information

Shopping online has become extremely common, but many consumers still feel hesitant about making online purchases — especially from smaller brands that they may be unfamiliar with. A big disadvantage of online shopping for consumers is that they are unable to see or try the product before making a purchase. In order to convince your customers that your product is high-quality and worth their money, be sure to offer as much product information as possible. On your product pages, include detailed product descriptions that offer information about size, material, color, ingredients, and place of origin. Offer high-quality product photography that show the product from every angle. For clothing, be sure to include images of a model wearing the item.

## Approportioning of Requirements 

As stated by the customer, security is not a concern of this project. As such, it is beyond the scope of this system to encrypt personal user data, encrypt credit card information, prevent unauthorized login attempts, or any other concern of this nature. Additionally, the system is not responsible for the following: 
• Verifying that credit card information is valid
• Verifying the email address provided by a user 
• Storing additional information about a product beyond simply the category and price         • Allowing users to edit their account details (username, password, mailing address, etc) 
• Allowing customers to order multiple copies of product in a single order 
• Providing individual product description 
• Allowing the Admin to update login credentials or other information about the Admin.

Specific Requirements

### Functional Requirements

User Stories –

1.	As a user I should be able to login, Logout and Register into the application.
2.	As a user I should be able to see the products in different categories.
3.	As a user I should be able to sort the products.
4.	As a user I should be able to add the products into the shopping cart.
5.	As a user I should be able to increase or decrease the quantity added in the cart.
6.	As a user I should be able to add “n” number of products in the cart.
7.	As a user I should be able to get the Wish list option where I can add those products which I want but don’t want to order now.
8.	As a user I should get different discount coupons.

Admin Stories –

1.	As an Admin I should be able to login, Logout and Register into the application.
2.	As an Admin I should be able to perform CRUD on Users.
3.	As an Admin I should be able to Perform CRUD on the products.
4.	As an Admin I should be able to get bulk upload option to upload a csv for products details
5.	As an Admin I should be able to get the stocks.
6.	As an Admin I should be able to mail if any stock is less than10.
7.	As an Admin I should be able to get the sales report of a specific duration.
8.	As an Admin I should be able to set the discount coupons for the specific set of users

### Software Requirements

The functional requirements or the overall description documents include the product perspective and features, operating system and operating environment, graphics requirements, design constraints and user documentation. 
The appropriation of requirements and implementation constraints gives the general overview of the project in regards to what the areas of strength and deficit are and how to tackle them. 

Technologies: Angular, Spring Boot, MySQL
Languages: Type Script, Java, SQL Querries
IDE: Eclipse , Vs code, Postgresql
Operating System: Windows 7/8/10/11 , Linux distros, MacOS X or later.

### Hardware Requirements 

Minimum hardware requirements are very dependent on the particular software being developed by a given Enthought Python/ VS Code user. Applications that need to store large arrays/objects in memory will require more RAM, whereas applications that need to perform numerous calculations or tasks more quickly will require a faster processor. 

Processor: Intel or AMD dual core x86 processor. 
Ram: 2 GB or above. 
Hard disk: 500 MB of free disk space or more.

## Architecture

### Angular Architecture

There are main eight blocks of Angular.
1. Module
2. Component
3. Metadata
4. Template
5. Data Binding
6. Service
7. Directive
8. Dependency Injection

### Spring Boot Architecture

The spring boot consists of the following four layers: 
1. Presentation Layer – Authentication & Json Translation 
2. Business Layer – Business Logic, Validation & Authorization 
3. Persistence Layer – Storage Logic 
4. Database Layer – Actual Database

### Micro Services Architecture

Typically, microservices are used to speed up application development. Microservices architectures built using Java are common, especially Spring Boot ones. It’s also common to compare microservices versus service-oriented architecture. Both have the same objective, which is to break up monolithic applications into smaller components, but they have different approaches

### DataBase Design

Tables are created for all entities
Entities in the Database include
1. Product_Category
2. Product_info
3. Cart
4. Users
5. product_in_order
6. Order_main

## Non functional Requirements

### 1. Usability:

Regardless of the size of your business, the website of your business should be easy to use for even a non-technical user. Do you know that a general user takes just 0.05 seconds to figure out whether the website is worth its time or not? Thus you have to give special attention to the design of your homepage, CTAs, and easy checkout to get past those milliseconds of doom. The usability of a website is also defined by:
• How easily a user can achieve their target in a single page visit
• How quickly they can perform tasks in the store
• The memorable & intuitiveness of the design
• Number and types of errors users make

### 2. Security:

Security comes with utmost importance if your site is dealing with monetary transactions, users’ financial and sensitive data. Using an SSL certificate and data privacy policy will create trust among the users for your website and convert the customers into brand advocates. It is also considered for the different admin roles by which you can control who can create, see, copy, change or delete information. Depending upon the location of your business, security also refers to compliance with customer data protection rules such as GDPR in Europe.

### 3. Performance: 

For increasing the traffic on your website, you have to give special attention to the performance in the non-functional requirements documentation. The focus should be on loading the e-commerce store as fast as possible regardless of the number of integrations and traffic on your website. You can set up the speed benchmark, maximum SKUs which you want to add, or any other performance indicator best for your business. Don’t consider the 3rd party system delivery time, because the developers will not have control over the 3rd party API calls.

### 4. Maintainability:

The operational costs for maintenance are the tricky part of planning a business budget. Thriving the website maintenance from the initial development means cutting the time & cost to determine and resolve the faults of the system in the future. Well, it sounds sad but there is no way to avoid issues in the future and you have to look for a website development company that can maintain your website.

### 5. Scalability:

Last but not the least, you have to look for a future-proof solution considering the scalability. It will define how the website can grow and increase its features and functionality without impacting the performance of your website. You must be able to add more memory, servers, or disc space for making more transactions on your website. On the server side, while entering new markets you may need to add localization features. Overall, this NFR accounts for painless business expansion and has both hardware and software implications. 
                                    
## Implementation

We will implement a simple e-commerce application. We'll develop an API using Spring Boot and a client application that will consume the API using Angular. Basically, the user will be able to add/remove products from a product list to/from a shopping cart and to place an order.

## Technology used

In below I would like to explain which technologies are used in this project. It’s helpful for understand the project layouts & overview of documentation.

### Back-end

1. Java
2. Spring Boot
3. Spring Security
4. JWT
5. Hibernate
6. PostgreSQL
7. Maven

### Front-end

1. Angular
2. Bootstrap

## IMPLEMENTATION STEPS

First you need to start back-end server, after that execute client side. Follow below steps to run this application on your system.
1. First Install Java 11 jdk, Vs code, Eclipse, PostgresSQL
2. From your local FrontEnd code path -> open cmd
Eg -> {local path}\ecommerce-eshop\frontend
3. Run  this command -- code .
4. Run Npm install from vs code terminal
5. Run npm start 
6. After the successful compiling you got this link in terminal localhost/4200.
7. Open this link in google chrome

DataBase

1. Install postgres SQL 
2. After installation serach PgAdmin in your computer
3. Open that PgAdmin
4. Open this query editor and You can run the querry from sql file.
5. Run the query.
