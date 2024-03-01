# Django User Management System

## Overview

This project implements a user management system for a platform supporting multiple organizations using Python, Django, and Django Rest Framework (DRF). It provides functionalities for user sign-up, role management, and organization membership requests.

## Tech Stack

- Python
- Django
- Django Rest Framework (DRF)
- RDBMS (PostgreSQL/MySQL)
- REST API

## Features

1. **User Signup:**
   - Admin creation on the first sign-up.
   - Approval requests for subsequent sign-ups.

2. **Admin Responsibilities:**
   - Role creation and assignment.
   - Approval or rejection of membership requests.

3. **Organizational Structure:**
   - Billing groups (Free, Pro, Premium) with user limits.

4. **Schema Design:**
   - Database models for users, organizations, roles, and membership requests.

5. **API Endpoints:**
   - User sign-up, role management, and organization membership requests.
   - Enforces business rules on limits and role assignments.

6. **Security:**
   - Authentication and authorization mechanisms.
   - HTTPS implementation.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/django-user-management.git
   cd django-user-management

