# SaifAuth API

The standalone authentication and posts API that served as the prototype for the authentication layer in my backend services. This project was later merged into the `saifapi` monorepo.

## Project Status

**Merged & Superseded**
The functionality of this API was integrated into the current `saifapi` monorepo. For the latest version and active development, please see:
**https://github.com/saif-abdelrazek/saifapi**

## Original Overview

A robust authentication API built with Node.js, Express, and MongoDB that provided comprehensive user authentication features including signup, signin, email verification, and password management, along with basic CRUD operations for posts.

## Original Features

- **User Authentication**: Secure signup and signin functionality.
- **Email Verification**: Email-based account verification system.
- **Password Management**: Change password and forgot password functionality.
- **Security**: Rate limiting, bot detection, and request shielding with Arcjet.
- **Data Validation**: Comprehensive input validation with Joi.
- **Posts Management**: Full CRUD (Create, Read, Update, Delete) API for user posts.

## Original Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT (JSON Web Tokens)
- **Validation**: Joi
- **Email**: Nodemailer
- **Security**: Arcjet (rate limiting, bot detection, shield)
- **Password Hashing**: bcrypt

## Historical Context & Architecture

This project was a significant learning exercise in building a secure, production-like backend service. It featured a clean separation of concerns with dedicated directories for controllers, middleware, models, and routers.

The API implemented complex security measures and validation, serving as the foundational authentication system that was later refactored and integrated into a larger, unified backend architecture (`saifapi`).

---

*Part of the A8K Legacy archive—a collection of early projects and learning experiments by [Saif Abdelrazek](https://saifabdelrazek.com).*
