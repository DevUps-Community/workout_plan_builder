# Plan Builder for Clients Mini Project

## Objective
Build a plan builder tool for admins to create and assign plans to clients.

## Features to Implement
1. **Admin Login:**
   - Secure admin login functionality.
2. **Plan Builder:**
   - Allow admins to create and customise plans for clients.
3. **Plan Assignment:**
   - Enable admins to assign plans to specific clients.

## Description
This project aims to build a plan builder tool for admins to create and assign plans to clients.

**Aspects to Consider:**

- **Schema Design:**
  - Plan how to store plan details, client associations, and customisation options.
  - Consider how to handle plan templates and modifications.

- **React App Design:**
  - Design components for admin login, plan creation, and plan assignment.
  - Ensure an intuitive interface for creating and managing plans.

- **Best Practices:**
  - Implement secure and efficient plan management.
  - Ensure data integrity and accuracy in plan details.
  - Provide clear and actionable interfaces for plan creation and assignment.

## Technical Requirements
- **Backend:** Node.js with Express
- **Database:** Supabase
- **Frontend:** React

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement admin login with Supabase Auth.
3. **Plan Builder API:**
   - Create endpoints to build and manage plans.
4. **Frontend:**
   - Build React components for admin login and plan builder.
   - Implement plan assignment functionality.
