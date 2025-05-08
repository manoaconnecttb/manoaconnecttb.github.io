---
layout: default
title: Club Hub - ManoaConnectTB
---

# Welcome to Manoa Connect

<a href="https://github.com/manoaconnecttb">**Manoa Connect**</a> is a centralized platform designed to connect students at the University of Hawai‘i at Mānoa with the many amazing clubs, student organizations, and communities on campus.

We believe that every student should be able to find a place where they belong—and Club Hub is here to help make that happen.

---

## Deployment

See Website: <a href="https://manoa-connect.vercel.app/">Manoa Connect</a>
- ![ci-ManoaConnect](https://github.com/manoaconnecttb/ManoaConnect//workflows/ci-ManoaConnect/badge.svg)
<br>
See Github Organization: <a href="https://github.com/manoaconnecttb">ManoaConnectTB</a> 

## Overview

Our goal is to build a user-friendly and dynamic platform where:
- Students can explore a wide variety of UH Mānoa clubs based on interests, major, or activity type.
- Clubs can create and manage public profiles to advertise their purpose, events, and meeting times.
- Students can express interest, contact club leaders, and track the clubs they’ve joined.

## What ManoaConnectTB Provides

Club Hub Allows for the Following Features:
- **Club Directory** with profiles and contact info
- **Club News Feed** with posted announcements and events
- **Student Dashboards** for managing saved/joined clubs
- **Admin Tools** to check user submitted posts and delete inappropriate clubs/posts

---

## Progression
- **Milestone 1:** <a href="https://github.com/orgs/manoaconnecttb/projects/1">M1</a>
<br>
- **Milestone 2:** <a href="https://github.com/orgs/manoaconnecttb/projects/4/views/1">M2</a>
<br>
- **Milestone 3:** <a href="https://github.com/orgs/manoaconnecttb/projects/9/views/1">M3</a>

## Current Screenshots
- **Landing Page**
<br>
![image](https://github.com/user-attachments/assets/4f4266e0-2212-4d18-8d1d-8271b0f01bbb)
- **Home Page**
<br>
![image](https://github.com/manoaconnecttb/manoaconnecttb.github.io/blob/main/pics/home_page.png?raw=true)
- **Explore Pages**
<br>
![image](https://github.com/manoaconnecttb/manoaconnecttb.github.io/blob/main/pics/explore_clubs.png?raw=true)
![image](https://github.com/manoaconnecttb/manoaconnecttb.github.io/blob/main/pics/explore_posts.png?raw=true)
- **Feedback Page**
<br>
![image](https://github.com/user-attachments/assets/eb78b0ff-80b2-420f-bbae-c10a42714f22)
- **Admin Tools Page**
<br>
![image](https://github.com/manoaconnecttb/manoaconnecttb.github.io/blob/main/pics/admin_page.png?raw=true)

---

## User Guide
- Users can sign up and create an account with the signup page
- If they have an account, users can log into their account with the sign in page
- Users can view all clubs and posts on either explore page
- Users can send feedback to the site admins
- Clubs can create new posts through the home page and explore page
- Club leaders can create new clubs through the explore clubs page


## Developer Guide
Clone the Repo
- git clone https://github.com/manoaconnecttb/manoaconnect.git && cd manoaconnect
Install Requirements
- Install Node.js (v16+)
- Install dependencies:
    - Frontend: cd client && npm install
    - Backend: cd ../server && npm install
Run the App
- Start backend: cd server && npm run dev
- Start frontend: cd ../client && npm start
- Visit http://localhost:3000
Project Structure
- client/ → React frontend
- server/ → Node.js/Express backend
- models/, routes/, controllers/ → For backend logic
Make Changes
- Frontend: add/update React components in client/src
- Backend: edit routes/controllers/models in server/
- Use .env for config (API keys, DB URI)
Test Your Code
- Frontend: cd client && npm test
- Backend: cd server && npm test
Contribute
- Fork → Branch → Commit → PR
- Follow code style and leave clear comments
Need Help?
- Open an issue on GitHub or contact the team

---

## Community Feedback

- "Overall, I really like the functionality of the website in that it's user-friendly and highly intuitive to use. On the other hand, I'd like to see "organizational tabs" in the "explore clubs" tab to help group clubs into categories such as "academic/professional, recreation, sports, etc." to help potential students filter their own interests!"
<br>
- "The “Welcome \*\*\*\*\*@gmail.com” text feels a bit raw — it’d look nicer if it showed just the name, like “Welcome, \*\*\*\*\*.”, The "Manoa ConnectTB" logo and title at the top center could be more and better polished and better quality. The cards for the posts and clubs work, but they look a little basic. Adding better padding, hover effects, and some updated fonts could help make them stand out more. You might want to hide users’ full emails on public pages and as I said use a username."
<br>
- ""
<br>
- ""
<br>
- ""
<br>

## Future Improvements
Based on the feedback provided by some users, one big concern we should address is user privacy as having the email of a user under their posts is leaking sensitive data. Another area of improvement would be the functionality of some pages such as the explore page to include a search filter to better align with what clubs or posts users want to see.

---

[Team Contract](https://docs.google.com/document/d/19ISbg1g8jTFm1V74StpGrG74BBHWuKIC-xssoQD9noM/edit?usp=sharing)


