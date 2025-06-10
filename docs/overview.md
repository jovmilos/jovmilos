# Medijana Municipality Website Planning

This repository contains planning documents for the official website of the City Municipality Medijana.

## Features
- Laravel 12 application with MySQL database `Medijana`.
- User roles: **Admin**, **User**, and **Ghost**.
- Role based dashboards for each user type.
- Registration and login forms protected by Google reCAPTCHA v3.
- Multilingual support: Serbian (Cyrillic and Latin) and English.
- Modules for News, Documents, and Competitions (Konkursi).
- Ghost users can submit various electronic requests via a set of forms.

## Database
See [`schema.sql`](schema.sql) for the base tables `roles` and `users` used during registration.
The script seeds the `roles` table with the three default roles and defines the `users` table with all required fields for registration.
