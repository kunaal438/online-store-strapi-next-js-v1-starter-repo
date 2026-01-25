# Online Store - Core Features

In this repo, you will know about this project's details on what stack it is built on and why. You will also find supportive files that you may need to follow along in the course.

*Online store is made by [**@modernweb**](https://youtube.com/@modernweb) for youtube tutorial* 

👉 You can check it live on - https://online-store-v1.modernweblabs.in 

## Project Stack

This online store uses all the latest frameworks and libraries 
<br />
<p align="center">
 <img width="400" alt="Screenshot 2025-09-19 at 1 56 55 PM" src="https://github.com/user-attachments/assets/a19bbb8f-d6e1-4db5-bd58-c5282eb958c9" />
</p>

#### Frontend

<!--
<img width="2152" height="1353" style="margin-bottom:20px;" alt="Screenshot 2025-09-19 at 1 46 58 PM" src="https://github.com/user-attachments/assets/b9f07737-0135-4c37-b605-65b4afa7efe5" />
<br><br />
-->

1. **Next JS** - This framework is built on top of react JS. Next js offers some great features like SSR, APIs, ISR etc.
2. **Next Auth** - For user auth session management in frontend with google auth support.
3. **Chakra UI** - For easy, modern, responsive, functional UI components

#### Backend

<!--
<img width="2540" height="1235" alt="Screenshot 2025-09-19 at 1 52 57 PM" src="https://github.com/user-attachments/assets/96efc03d-92f9-4c03-b663-60c685458e9b" />
-->
  
1. **Strapi** - It is a open source professional level CMS ( content management system ), we are using this to manage the data fos tore like order management or products management.
2.  **Stripe** - It is a beginner freindly and easy to use payment gateway which does not require any kind of business verification to use in test mode. This projects run in test mode do no real transaction is involded on this project demo at least.
3. **Cloudinary** - This projects uses cloudinary to manage file uploads, all the files generated on strapi of frontend get saved on cloudinary.
4. **Nodemailer** - This project also uses nodemailer to send email notifications like welcome email, order status or dispute notificaiton etc.

#### Database

1. **Postgres SQL** - This project uses Postgrest SQL database instead of Strapi's default SQLite database.

## Project Features

The online store has a lot of real world features such as -

1. **Google based authentication** with Next Auth for frontend session management and Strapi for validating the auth and create store specific JWT key.
2. **Cart sync** - local storage to user account.
3. Checkout product validations and **product stock locking** to prevent overselling.
4. Category, color and price based **search filter** for products on search page. 
5. **Email notification** on Joining, Order placement / updates, any dispute alert, support status.
6. **Release of all locked product stocks** states in case of order failure or checkout expiry. ( Every 10 mins CRON JOB )
7. Fully wokring **support page** with support status on emails and support management by Strapi "support" Role user.
8. **SSR** dynamic product page, search page, support page, categories, sub-cateogries and more to help general site SEO. ( Only works with real data )
9. **Fraud protection** by stopping the user from making new order until thier dispute on delivered order is resolveds.
10. Beautiful **Modern and Responsice** Frontend UI with Chakra UI + **Dual theme** store.
    
    and **much more..**


If you have any question regarding this project feel free to contact me on help@modernweb.in. 

I would love to hear you feedback on this project, share your feedback on feedback@modernweb.in
