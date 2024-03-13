# Rapid Repair
## 1. Introduction
Rapid Repair is an app designed to assist users in quickly finding servicemen for various tasks. Whether it's fixing a leaky faucet, painting a room, or repairing electrical appliances, Rapid Repair streamlines the proccess, offering a seamless platform for users to book various services with ease. Additionally, the app provices a platform for skilled servicemen to showcase their expertise and expaind their client base.

## 2. Features
Rapid Repair includes the following features:

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

* Booking Management
  - Users and servicemen can manage their booked services and view appointment details.

* Profile Management
  - Servicemen and users can create and manage their profiles, including adding services offered, availability, pricing, and portfolio showcasing their work for the servicemen and updating their personal information for the users. 



## 3. User Interface and Pages

Rapid Repair features a user-friendly interface with the following main pages:

* Home Page:
* Services Details Page:
* Registration and Login Page:
* Service Booking Page:
* User Profile Page:
* User Profile Management Page:

### 3.1. Visual Site Mockup

<details>
  <summary>Desktop Home Page Mockup</summary>
  
  ![Desktop](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/2443a537-591c-455c-9eda-a93eb06aaf9e)
</details>

<details>
  <summary>Mobile Home Page Mockup</summary>
  
  ![Mobile](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/9f319df0-2900-45e9-879a-20a4611594ae)
</details>

<details>
<summary>Login Page</summary>

  ![Login](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/1505fc5e-2264-45f6-951d-fcd93bd691ed)
</details>

<details>
<summary>Register Page Part 1</summary>

  ![Register PART1](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/c7e69eb7-0f8e-4422-b819-9bd991098c2f)
</details>

<details>
  <summary>Register Page Part 2</summary>

  ![Register PART2](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/2f8da441-940a-4f2e-97b6-92ffea43a219)
</details>


<details>
  <summary>Register Page Part 3</summary>

  
![Register PART3](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/1f8d4542-88c0-4b74-bacf-ac7814818193)
</details>


<details>
<summary>Registration Successful Page (Part 4)</summary>

  ![Register PART4](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/3fb054d1-551c-4083-a703-27f26ffea4d8)
</details>


### 3.2. Sitemap


<details> 
  <summary> Original sitemaps (OLD)</summary>
  
  ![sitemap](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/25596638-1050-4a14-9611-bbe58f32bb51)\

  ![sitemap](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/a52af353-1058-431e-a423-2ad2d0797650)
  
</details>

<details>
<summary>Updated Sitemap (with links)</summary>

![sitemap](https://github.com/heffenauer/rapid-repair-issues/assets/70574993/76545795-d722-45a2-affd-cf2ab2b13a68)

</details>


## 4. Functionality


### 4.1. Home Page

Home Page provides comprehensive information about our company including the following sections

- About Us
- Partners
- FAQ
- Accomplishments

User Interface elements included on the home page are: 

- Search Bar Functionality: Easily locate specific services or service providers by name.
- Comprehensive Service Listing: Explore our complete list of services where each service listed is clickable, leading users to service pages iwhere they can learn more about the service and proceed with booking if desired.

### 4.2. Registration/Login

Users have the option to log in to an existing account or create a new one. Opting to create a new account directs them to the Profile Creation Page, while choosing to log in to an existing account keeps them on the current page.

Login encompasses the following components:
- Input fields for email and password
- Confirmation button to finalize the login
- "Forgot Password" button for easy password recovery

Upon login, the user will be kept on the home page, where if they choose to press their user icon on the top right of the page, they will be redirected to the User/Serviceman Profile Page. On this Page they will be presented with their personal information that will be greyed out to avoid accidental changes, they can opt to enter edit mode which will refresh the page and allow for changes to be made in the user information fields. On this User/Serviceman Profile Page there will also be a link or button that will allow the User to access the Service Management Page, on which the User will be able to leave a review on completed tasks or to cancel an existing task. If the User is a Serviceman this page will allow them to cancel their reserved appointment. On the User/Serviceman profile page, if the User is a Serviceman, there will be presented their aggregated review score, a grade that the Serviceman will be able to see. They can use this value to determine whether their services are generally of good quality or if they should perform better in the future. The user will return to the home page upon successful performance of any chain of actions on these pages.

### 4.2.1 Profile Creation Page

Registration process encompasses the following components:
- Input fields for first name, last name, email, country, city, address, phone number, password, and confirmation of password
  Upon filling out these fields(this consists of several steps in which the user will enter his information)correctly the user would be redirected to the Successfull Registartion page

Depending on whether the user creating the profile wants to create a User profile or a Serviceman Profile. This option will be preseneted for the user on the first step of the registration as a checkbox, 
i.e.   Serviceman Profile - [x]

- A confirmation button to finalize the creation of the profile, which triggers a popup in case any input field is filled incorrectly
- 

### 4.3. Service Details Page 

Once users click on one of the services listed on the Home Page, they are directed to the Service Details Page.
This page provides customers with comprehensive information about the service, including a description, photos showcasing previous work, and any relevant subcategories. Customers can learn about the service duration and other details. Users can browse through available services, identifying those that best match their specific tasks. They can compare these services to similar ones, enabling them to make a well-informed decision before finalizing their choice.

The page includes the following navigations: 
* Obvious navigation back to the Home Page where all services are listed and 
* A prominent "Book This Service" button, directing users to the Service Booking Page


### 4.3.1 Service Booking Page

 If users are already logged into their account, they can proceed with booking. However, if they aren't logged in, they are redirected to the Login/Registration Page where they can either create a new account or log in. Once logged in or registered, users can move back through the service list and perform the booking.

After selecting the appropriate service, users are directed to the Service Booking Page where they can enter booking information. 
This includes 
* Input field for the desired date of the service
* Input field for the desired time for the service to be completed
* Input field for any special requests users might have

### 4.3.2 Service List Page
Once a user has selected a service they are intrested in they shall be redirected to the Serviceman List Page. 
The Servicemen List Page will provide a list of all Servicemen that can be selected for the service.
Once this process has been completed a pop-up will show up stating the service was successfuly booked and the user will be redirected back to his Profile Page where he can view his booking information.


### 4.4 User Profile Page
When the user logs into his account he can enter his Profile Page. On the Profile Page user can view and edit all of his information. An edit button will be assigned next to all of the information fields.
User can also view and edit his service bookings. Viewing and editing service bookings will be done on a separate page when clicked on the link.

If the user is a Serviceman, he will have almost the same functionalities as a ordinary user on the Profile Page. In addition, he can write "About Me" and "My Service" descriptions.

### 4.4.1 Service Management Page

When the user opens the "View your services" link, he will be redirected to the Service Management Page.
On this page the user can view all of his current bookings, as well the previous ones. There will be also a functionality to edit reservation details or to cancel the service.
Serviceman can also cancel their service booking, but can not edit them (for example: time slots).


## 5. Technical Requirements

The Rapid Repair is built using the following technologies:
* Backend: Java, Spring, PostgreSQL 
* Frontend: Angular 

## 6. Out of scope

* Payment Processing: Currently, users can only book the service they desire and pay the servicemen in cash in person. However, handling actual payment transactions, such as credit card processing or integrating with payment gateways, is beyond the scope of this project.

* Real-Time Chat: Implementing real-time chat would enable customers to communicate directly and quickly with servicemen within the app.

* Notification System: Users can receive notifications confirming their service bookings, providing updates on the serviceman's estimated arrival time. Additionally, they can be notified about ongoing sales or promotions within the app, ensuring they stay informed about potential discounts or special offers.
