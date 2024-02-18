# Angular 17 JWT Authentication & Authorization example with Rest API (standalone)

- Backend: https://github.com/mbachmann/spring-boot-3-starter-security.git
- Frontend: https://github.com/mbachmann/angular-17-jwt-auth-starter-standalone.git

Build Angular 17 JWT Authentication & Authorization example with Rest Api, HttpOnly Cookie and JWT (including HttpInterceptor, Router & Form Validation).
- JWT Authentication Flow for User Registration (Signup) & User Login
- Project Structure with HttpInterceptor, Router
- Way to implement HttpInterceptor
- How to store JWT token in HttpOnly Cookie
- Creating Login, Signup Components with Form Validation
- Angular Components for accessing protected Resources
- How to add a dynamic Navigation Bar to Angular App
- Working with Browser Session Storagegit s

## Flow for User Registration and User Login
For JWT – Token based Authentication with Rest API, we’re gonna call 2 endpoints:
- POST `api/auth/signup` for User Registration
- POST `api/auth/signin` for User Login
- POST `api/auth/signout` for User Logout

