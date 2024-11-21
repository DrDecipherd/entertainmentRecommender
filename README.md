# Game Recommender
Website starting with game recommendations based on user selected tags. Further to include other entertainment mediums.

Design
I want to get a good grasp of Django, Python, React, and Cloud databases in the 2024/2025 space. I have experience in all of these areas, but not together, and it has been a while. This project will begin as a game recommender. Too long have I had to sit with friends in discord deciding what games we have on what platforms etc. So here is where we fix it.

Software Engineering 
Software Requirements Specification
(SRS) Document

Joshua Elliott
11/02/2024

1. Introduction
1.1	Introduction
This document outlines the project's requirements, detailing the system's functionality and specifying its constraints.

1.2	Scope of this Document
The target audience for this system includes video game players seeking recommendations for new games. The system is designed to provide a curated list of games, including their prices, platforms, and other details, to assist users in navigating the overwhelming abundance of available games.

1.3	Overview
The product is a web application that allows users to filter game information and export results as tables or save data for future reference. The results will display games matching the applied filters, sourced initially from the IGDB API. 

1.4	Business Context
This application has the potential to generate revenue through subscription-based profiles and premium features. Premium options may include importing users' game libraries from various services to minimize suggestions for games they already own, favoriting suggestions, saving profiles, and sharing profiles with others. To sustain these features and cover operational costs, such as AWS cloud hosting, I plan to implement an optional subscription membership and specific advertising that does not overly impede on the functionality.

2. General Description
2.1 Product Functions
The product should take input in the form of filters and search criteria and return the result of games that that person could play given financial, platform, or personal limitations and preferences. 

2.2 Similar System Information
Quantic Foundry Video Game Recommendation Engine
-takes input of 3 game titles the user has enjoyed and returns a list of similar games
Steam Interactive Recommender
	-only for steam
 Other Platforms similar to steam

2.3 User Characteristics
The users are any person who is seeking a new video game to play and wants a full list of any game made that is available based on their hardware, financial situation, social situation, and personal preferences.

2.4 User Problem Statement
Currently, the only recommenders are AI, which is controversial and potentially unreliable, and platform specific recommendations such as PSN, Steam, Epic Games, etc. Many people own multiple devices and have many games across a multitude of consoles and computers which makes the task of looking at all the options available nearly impossible without a dedicated amount of research time.

2.5 User Objectives
The objectives are to have a fast, single-page, modern web application that will serve a table of game recommendations based off inputs and filters.

2.6 General Constraints
Internet connection, a mobile or desktop computer, and the ability to use it.
/////////////////////////////TO DOCUMENT///////////////////////////////////////////////
3. Functional Requirements
3.1	Item 1
    -Subitem 1
3.2 Item 2
    -Subitem 2

4. Interface Requirements
4.1 User Interfaces
4.1.1 GUI

4.1.2 CLI

4.1.3 API

4.1.4 Diagnostics or ROM

4.2 Hardware Interfaces

4.3 Communications Interfaces

4.4 Software Interfaces

5. Performance Requirements

6. Other non-functional attributes

6.1 Security

6.2 Reliability

6.4 Maintainability

6.5 Portability

6.6 Extensibility

6.7 Reusability

6.8 Application Affinity/Compatibility

6.9 Resource Utilization

6.10 Serviceability

7. Operational Scenarios
Scenario A: 

Scenario B: 
	
Scenario C: 
