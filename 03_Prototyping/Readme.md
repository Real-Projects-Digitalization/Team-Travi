# Team Travi - Project Documentation

## Introduction
This document outlines the development process, architecture, and current state of the "Team Travi" mobile application.  
Travi is an all-in-one app designed to simplify group travel by centralizing planning, coordination, and decision-making. Our goal is to transform the often chaotic process of planning a group trip into a fun, collaborative, and data-driven experience.

🔗 **Link to the final Prototype:** [https://luca-steinleitners-team-1.adalo.com/travi](https://luca-steinleitners-team-1.adalo.com/travi)

🌐 **Link to the Landing Page (Work in Progress):** [https://xlhyimcj0pdk.manus.space](https://xlhyimcj0pdk.manus.space)  
*The landing page has been created but is still missing some functionalities and requires further development to fully showcase our app.*

---

### Prototype Evolution: From Vision to Functionality
Our development process followed an iterative approach, starting with a visual concept (Figma Development) and evolving into a functional Prototype based on user feedback / interview partners.

# Phase 1: The Figma Prototype (Low-Fidelity)
Our initial step was to create a visual representation of our app concept using Figma. This resulted in a clickable, non-functional prototype that allowed us to present the basic user flow and visual design.  
We also used the Figma Prototype for our Mid Term presentation to showcase our idea.  
🔗 **Link to the Figma Prototype:** [https://www.figma.com/proto/pX4Wk5MMcwsg7BG328ONou/Untitled?node-id=1-4&starting-point-node-id=1%3A4&t=58aXvMhfriEeNYDl-1](https://www.figma.com/proto/pX4Wk5MMcwsg7BG328ONou/Untitled?node-id=1-4&starting-point-node-id=1%3A4&t=58aXvMhfriEeNYDl-1)

## Key Feedback from Figma Prototype Testing
We gathered crucial feedback from initial user tests with the Figma prototype. The main criticisms were:
- **Limited Functionality:** Users could see the design but couldn't perform any real actions. There was no data being created or saved.
- **Superficial Experience:** The prototype felt shallow as users could not explore beyond a few pre-defined paths.
- **Linear & "On-Rails" Path:** The click-dummy followed a single, predetermined path. Users had no freedom to explore or make their own choices, which made it feel unrealistic.
- **No Real Interaction:** The prototype lacked any form of dynamic interaction, data input, or personalized content, which are core to our app's value proposition.

This feedback made it clear that to properly validate our idea, we needed a prototype with real, working functionalities.

# Phase 2: The Adalo MVP (High-Fidelity & Functional)
Based on the feedback, we decided to build a functional Prototype using the low-code platform Adalo. This allowed us to move beyond visuals and implement the core logic of our app.

## Key Improvements with the Adalo MVP:
Our current Adalo prototype is a significant leap forward and now includes:
- **User Authentication:** Users can sign up for a new account and sign in to their existing account.
- **Interactive "Swipe" Feature:** A core feature where users can actively engage with content by swiping on Destinations, Trips, and Accommodations. These choices are saved in a real database.
- **Group Creation & Management:** Users can create travel groups, name them, and invite other registered users to join.
- **Collaborative Planning:** The app demonstrates a basic version of the group matching feature, showing how individual preferences can be aggregated.

# Relational Data Model
To ensure a logical and scalable application, we designed a relational data model with a clear hierarchy. We call this our "Logical Granularity".  
The structure is designed to guide the user from the big picture to the small details, mirroring a natural planning process.

## First Relational Prototype:
![Travi drawio](https://github.com/user-attachments/assets/1b9a0859-6f3c-4b45-bd26-5146c6834661)


- **Destinations:** This is the top-level entity (the "Where"). It's the container for everything else.
- **Trips:** These are thematic experiences or activities that are dependent on a Destination (the "What").
- **Accommodations:** These are the places to stay, also dependent on a Destination (the "Where to sleep").

This structure prevents overwhelming the user and makes the planning process intuitive.

## Current State of the Prototype
The current functional prototype built with Adalo successfully demonstrates the core value proposition of our app. Key working features include:

✓ User Sign-Up & Sign-In  
✓ A dynamic "Swipe" interface for liking/disliking Destinations, Trips, and Accommodations  
✓ Saving user choices to a persistent database  
✓ Viewing liked items in a "Favorites" section  
✓ Creating travel groups and inviting other users  
✓ A basic view of a group's commonly liked items

---

## 📁 03_Prototyping

This folder contains all prototype-related artifacts and documents used throughout the design and development phase. It tracks the evolution from low-fidelity design to high-functioning MVP.

### Files:

- **Prototype_Team_Travi_Figma.mp4**  
  A walkthrough video showcasing the first interactive Figma prototype of the Travi app.

- **The Team Canvas.pdf**  
  Team-building and role clarification document.

- **Team Canvas 1.0.pdf**  
  First version of the team canvas capturing early responsibilities and collaboration values.

- **Potential_User_Evaluation_Team-Travi.xlsx**  
  Catching Feedback to our MVP from the first Interview Partners.
