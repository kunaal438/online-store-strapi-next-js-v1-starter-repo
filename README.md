# Online Store - Core Features

In this repo, you will know about this project's details on what stack it is built on and why. You will also find supportive files that you may need to follow along in the course.

*Online store is made by [**@modernweb**](https://youtube.com/@modernweb) for youtube tutorial* 

👉 You can check it live on - https://online-store-v1.modernweblabs.in 

---

## Project Stack

This online store uses all the latest frameworks and libraries

<br />
<p align="center">
 <img width="400" alt="Screenshot 2025-09-19 at 1 56 55 PM" src="https://github.com/user-attachments/assets/a19bbb8f-d6e1-4db5-bd58-c5282eb958c9" />
</p>

### Frontend

1. **Next JS** - This framework is built on top of react JS. Next js offers some great features like SSR, APIs, ISR etc.
2. **Next Auth** - For user auth session management in frontend with google auth support.
3. **Chakra UI** - For easy, modern, responsive, functional UI components

### Backend

1. **Strapi** - It is an open source professional level CMS ( content management system ), we are using this to manage the data for store like order management or products management.
2. **Stripe** - It is a beginner friendly and easy to use payment gateway which does not require any kind of business verification to use in test mode. These projects run in test mode. No real transaction is involved on this project demo at least.
3. **Cloudinary** - This project uses cloudinary to manage file uploads, all the files generated on strapi of frontend get saved on cloudinary.
4. **Nodemailer** - This project also uses nodemailer to send email notifications like welcome email, order status or dispute notification etc.

### Database

1. **Postgres SQL** - This project uses Postgres SQL database instead of Strapi's default SQLite database.
   
---

## Project Features
   
1. **Cart sync** - local storage to user account.
2. Checkout product validations and **product stock locking** to prevent overselling.
3. Category, color and price based **search filter** for products on search page. 
4. **Email notification** on Joining, Order placement / updates, any dispute alert, support status.
5. **Release of all locked product stocks** in case of order failure or checkout expiry. ( Every 10 mins CRON JOB )
6. Fully wokring **support page** with support status on emails and support management by Strapi "support" Role user.
7. **SSR** dynamic product page, search page, support page, categories, sub-cateogries and more to help general site SEO. ( Only Effective with real data )
8.  **Fraud protection** by stopping the user from making new order until their dispute on delivered order is resolved.
9.  Beautiful **Modern and Responsive** Frontend UI with Chakra UI + **Dual theme** store.
    
    and **much more..**

---

If you have any question regarding this project feel free to contact on help@modernweb.in. 

I would love to hear you feedback on this project, share your feedback on feedback@modernweb.in
