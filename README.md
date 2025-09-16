# Fragments UI

## Overview
This project is a simple web client for testing the **Fragments microservice**.  
It allows users to log in with **AWS Cognito Hosted UI**, fetch authentication tokens, and call the secured backend API.  
Built using **Parcel** as the bundler and **oidc-client-ts** for authentication.

---

## Prerequisites
Make sure you have the following installed:
- [Node.js (LTS)](https://nodejs.org/en/)  
- [npm](https://www.npmjs.com/) (comes with Node.js)  
- GitHub repo cloned with SSH (`git@github.com:avinav456/fragments-ui.git`)  
- An AWS Cognito **User Pool** and **App Client ID** configured  

---

## Installation
Clone the repo and install dependencies:

```bash
git clone git@github.com:avinav456/fragments-ui.git
cd fragments-ui
npm install

