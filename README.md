# MomentumXLab Auth System

This repository contains the authentication system for MomentumXLab — a robust SaaS platform for managing user accounts, plans, and access to digital tools such as EA (Expert Advisor). It integrates Firebase Authentication, Firestore database, and Stripe payment processing.

## 🔐 Features

- Firebase Authentication (Email/Password signup and login)
- Firestore database for user plan tracking (`expires`, `activated`, `plan`)
- Dashboard displaying user info
- Stripe Checkout integration
- Stripe Webhook listener (via Firebase Functions)
- Cloud Function API for EA license verification

## 🧩 File Structure
