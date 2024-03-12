# Rapid Repair
### 1. Introduction
Rapid Repair is an app designed to assist users in quickly finding servicemen for various tasks. Whether it's fixing a leaky faucet, painting a room, or repairing electrical appliances, Rapid Repair streamlines the proccess, offering a seamless platform for users to book various services with ease. Additionally, the app provices a platform for skilled servicemen to showcase their expertise and expaind their client base.

### 2. Features
Rapid Repair includes the following features:

User features

* Registration and Login
  - Users can create accounts or log in using existing credentials to access the app's features.

* Search Bar Functionality
  - Users can easily search for specific services or servicemen based on location or service category.

* Review Functionality
  - Users can rate and provide feedback on the quality of service received, helping others make informed decisions.

* Filter Function
  - Users can refine search results by applying filters such as service type, price range, availability, and ratings.

* Booking Services
  - Users can view available servicemen, check their profiles and ratings, and book services directly through the app.

* Serviceman booking management
  - Users and servicemen can manage their booked services and view appointment details.

Servicemen Features

* Profile Management
  - Servicemen can create and manage their profiles, including adding services offered, availability, pricing, and portfolio showcasing their work.



### 3. User Interface and Pages

Rapid Repair features a user-friendly interface with the following main pages:

* Home Page:
* Services Details Page:
* Registration and Login Page:
* Service Booking Page:
* User Profile Page:
* User Profile Management Page:

3.1. Visual Site Mockup

Desktop Home Page Mockup

![Desktop](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/2443a537-591c-455c-9eda-a93eb06aaf9e)

Mobile Home Page Mockup

![Mobile](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/9f319df0-2900-45e9-879a-20a4611594ae)

Login Page 

![Login](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/1505fc5e-2264-45f6-951d-fcd93bd691ed)

Register Page Part 1

![Register PART1](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/c7e69eb7-0f8e-4422-b819-9bd991098c2f)

Register Page Part 2

![Register PART2](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/2f8da441-940a-4f2e-97b6-92ffea43a219)

Register Page Part 3

![Register PART3](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/1f8d4542-88c0-4b74-bacf-ac7814818193)

Registration Successful Page (Part 4)

![Register PART4](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/3fb054d1-551c-4083-a703-27f26ffea4d8)


3.2. Sitemap

![sitemap](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/25596638-1050-4a14-9611-bbe58f32bb51)


### 4. Functionality


4.1. Home Page

Home Page provides comprehensive information about our 
- About Us
- Partners
- FAQ
- Accomplishments

User Interface elements included on the home page are: 
- Search Bar Functionality: Easily locate specific services or service providers by name.
- Comprehensive Service Listing: Explore our complete list of services where each service listed is clickable, leading users to service pages iwhere they can learn more about the service and proceed with booking if desired.

4.2. Registration/Login

Users have the option to log in to an existing account or create a new one. Opting to create a new account directs them to the Profile Creation Page, while choosing to log in to an existing account keeps them on the current page.

Login encompasses the following components:
- Input fields for email and password
- Confirmation button to finalize the login
- "Forgot Password" button for easy password recovery

4.2.1 Profile Creation Page

Registration encompasses the following components:
- Input fields for name, last name, email, country, city, address, phone number, password, and confirmation of password
- A confirmation button to finalize the creation of the profile, which triggers a popup in case any input field is filled incorrectly

4.3. Service Details Page 

Once users click on one of the services listed on the Home Page, they are directed to the Service Details Page.
This page provides customers with comprehensive information about the service, including a description, photos showcasing previous work, and any relevant subcategories. Customers can learn about the service duration and other details. Users can browse through available services, identifying those that best match their specific tasks. They can compare these services to similar ones, enabling them to make a well-informed decision before finalizing their choice.

The page includes the following navigations: 
* Obvious navigation back to the Home Page where all services are listed and 
* A prominent "Book This Service" button, directing users to the Service Booking Page


4.4 Service Booking Page

After selecting the appropriate service, users are directed to the Service Booking Page where they can enter booking information. 
This includes 
* Input field for the desired date of the service
* Input field for the desired time for the service to be completed
* Input field for any special requests users might have

 If users are already logged into their account, they can proceed with booking. However, if they aren't logged in, they are redirected to the Login/Registration Page where they can either create a new account or log in. Once logged in or registered, users can continue with the booking process.

### 5. Technical Requirements

The Rapid Repair is built using the following technologies:
* Backend: Java, Spring, PostgreSQL 
* Frontend: Angular 

### 6. Out of scope

* Payment Processing: Currently, users can only book the service they desire and pay the servicemen in cash in person. However, handling actual payment transactions, such as credit card processing or integrating with payment gateways, is beyond the scope of this project.

* Real-Time Chat: Implementing real-time chat would enable customers to communicate directly and quickly with servicemen within the app.

* Notification System: Users can receive notifications confirming their service bookings, providing updates on the serviceman's estimated arrival time. Additionally, they can be notified about ongoing sales or promotions within the app, ensuring they stay informed about potential discounts or special offers.
