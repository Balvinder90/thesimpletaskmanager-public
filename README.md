# Task Manager App

A full-stack task management web application built with React, TypeScript, and Supabase.

▶ **Live Demo:** https://thesimpletaskmanager.netlify.app

---

## Overview
This application allows users to manage their tasks through a clean and intuitive interface. Users can sign up, sign in, or continue anonymously, with tasks securely stored and associated with their account. Stats based on users are also stored and both tasks and stats are updated with realtime updates. Anonymous user’s tasks and stats are automatically deleted once they log out.

The project focuses on authentication flows, client-side state management, and user-friendly task organization features.

---

## Features

### Authentication
- Email/password sign up and sign in
- Anonymous user sessions
- Password update and reset functionality
- Supabase-managed authentication

### Tasks/Stats Management
- Create, read, update, and delete tasks/stats
- Tasks are persisted per user except for anonymous users
- Stats are persisted per user except for anonymous users
- Real-time UI update for tasks and stats 

### Filtering & Sorting
- Sort tasks alphabetically (A–Z)
- Sort by priority
- Filter by date created
- Filter by date last edited
- Reset filters to default
---

## Demo

### Full demo for an existing account
[Watch on YouTube](https://www.youtube.com/watch?v=wY8veXTyq_8)

### Full demo for an anonymous account
[Watch on YouTube](https://www.youtube.com/watch?v=wnProlF4TIs)

---

## Tech Stack

- **Frontend:** React, TypeScript, CSS, Motion.dev (Animations)
- **Backend / Services:** Supabase (Authentication & Database)
- **Architecture:** Client-side application

---

## Architecture & Decisions

- The application is built as a client-side React app using Supabase for backend services.
- Authentication and database interactions are handled directly from the frontend using Supabase’s client SDK.
- Environment variables are used to securely manage Supabase credentials.
- Anonymous users can explore the app before creating an account.

---

## What I Learned

- Implementing secure authentication flows
- Managing complex UI state with TypeScript
- Designing filtering and sorting logic
- Integrating a backend-as-a-service into a frontend application
- Structuring a project for maintainability

---

## Source Code

The full source code for this project is kept in a **private repository**.

If you’re interested in reviewing the implementation, feel free to contact me.

---

## Author
Balvinder Singh
