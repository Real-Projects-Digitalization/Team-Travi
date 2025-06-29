# Team Travi - Project Documentation

Introduction
This document outlines the development process, architecture, and current state of the "Team Travi" mobile application.
Travi is an all-in-one app designed to simplify group travel by centralizing planning, coordination, and decision-making. Our goal is to transform the often chaotic process of planning a group trip into a fun, collaborative, and data-driven experience.

1. Prototype Evolution: From Vision to Functionality
Our development process followed an iterative approach, starting with a visual concept (Figma Development) and evolving into a functional Prototype based on user feedback / interview partners.

Phase 1: The Figma Prototype (Low-Fidelity)
Our initial step was to create a visual representation of our app concept using Figma. This resulted in a clickable, non-functional prototype that allowed us to present the basic user flow and visual design.
We also used the Figma Prototype for our Mid Term presentation to showcase our idea.
Link to the Figma Prototype: https://www.figma.com/proto/pX4Wk5MMcwsg7BG328ONou/Untitled?node-id=1-4&starting-point-node-id=1%3A4&t=58aXvMhfriEeNYDl-1

Key Feedback from Figma Prototype Testing
We gathered crucial feedback from initial user tests with the Figma prototype. The main criticisms were:
- **Limited Functionality: Users could see the design but couldn't perform any real actions. There was no data being created or saved**
- **Superficial Experience: The prototype felt shallow as users could not explore beyond a few pre-defined paths**
- **Linear & "On-Rails" Path: The click-dummy followed a single, predetermined path. Users had no freedom to explore or make their own choices, which made it feel unrealistic**
- **No Real Interaction: The prototype lacked any form of dynamic interaction, data input, or personalized content, which are core to our app's value proposition**

This feedback made it clear that to properly validate our idea, we needed a prototype with real, working functionalities.

Phase 2: The Adalo MVP (High-Fidelity & Functional)
Based on the feedback, we decided to build a functional Prototype using the low-code platform Adalo. This allowed us to move beyond visuals and implement the core logic of our app.

Key Improvements with the Adalo MVP:
Our current Adalo prototype is a significant leap forward and now includes:

User Authentication: Users can sign up for a new account and sign in to their existing account.

Interactive "Swipe" Feature: A core feature where users can actively engage with content by swiping on Destinations, Trips, and Accommodations. These choices are saved in a real database.

Group Creation & Management: Users can create travel groups, name them, and invite other registered users to join.

Collaborative Planning: The app demonstrates a basic version of the group matching feature, showing how individual preferences can be aggregated.

2. Relational Data Model
To ensure a logical and scalable application, we designed a relational data model with a clear hierarchy. We call this our "Logical Granularity".

The structure is designed to guide the user from the big picture to the small details, mirroring a natural planning process.

Destinations: This is the top-level entity (the "Where"). It's the container for everything else.

Trips: These are thematic experiences or activities that are dependent on a Destination (the "What").

Accommodations: These are the places to stay, also dependent on a Destination (the "Where to sleep").

This structure prevents overwhelming the user and makes the planning process intuitive.
