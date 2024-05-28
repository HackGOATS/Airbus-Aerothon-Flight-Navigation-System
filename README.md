![image-2](https://github.com/HackGOATS/Airbus-Aerothon-Flight-Navigation-System/assets/75236583/236dc2a2-48f0-45da-9853-a8084e8b4a03)![image](https://github.com/HackGOATS/Airbus-Aerothon-Flight-Navigation-System/assets/75236583/e60bb8b6-7e3c-49f7-bac5-cc17d4fb52e8)# Airbus-Aerothon-Flight-Navigation-System
# Flight Navigation System

## Overview
The Flight Navigation System is designed to enhance flight navigation for optimal route planning and risk mitigation. By leveraging the Rapidly-exploring Random Tree (RRT*) algorithm, this system optimizes flight paths considering various factors such as weather conditions, air traffic, and no-fly zones. The project aims to improve aviation safety, reduce delays, and increase fuel efficiency.

## Project Theme
Enhancing Flight Navigation Mechanism for Optimal Route Planning And Risk Mitigation.

## Problem Statement
Aviation safety requires efficient and reliable navigation. This project develops a flight navigation system to identify optimal flight paths while addressing challenges like adverse weather, air traffic, and environmental variables. The system provides real-time risk assessment and suggests alternative routes, enhancing safety and operational efficiency.

## Proposed Solution
The solution uses the RRT* algorithm for optimizing air traffic routes. It considers multiple parameters such as weather conditions, elevation changes, no-fly zones, and risk assessment. The key advantages include reduced delays, enhanced safety, flexibility, and adaptability. The algorithm rapidly explores the airspace, constructs potential routes, and optimizes the path based on specified parameters.

## Technological Stack
- Frontend: HTML, CSS, ReactJS
- Programming Languages: Python (RRT* algorithm), JavaScript
- Backend: NodeJS
- Database: MySQL
- APIs: Real-time weather data, elevation information
- Algorithm: RRT*

## Architecture
The architecture involves the RRT* algorithm for path planning and optimization. The system integrates with external APIs to fetch real-time data, ensuring accurate and optimized routes.
![image](https://github.com/HackGOATS/Airbus-Aerothon-Flight-Navigation-System/assets/75236583/7226360f-e71f-4319-951e-bb5017a681af)

## Flowchart
![image-1](https://github.com/HackGOATS/Airbus-Aerothon-Flight-Navigation-System/assets/75236583/90b351b6-d735-49bb-844c-d202371a04e3)

## Impact Metrics
1. Reduction in flight delays and cancellations
2. Improved fuel efficiency and reduced carbon emissions
3. Enhanced flight safety
4. Scalability to handle increased flights and routes
5. Cost savings for airlines

## Assumptions and Constraints
- Accurate and up-to-date data sources are available.
- Efficient performance and scalability of the RRT* algorithm are crucial.

## Visualization
![image-2](https://github.com/HackGOATS/Airbus-Aerothon-Flight-Navigation-System/assets/75236583/acd5c7fa-6ac8-4485-bc79-1c275c6cc576)

## Solution Decision Points
1. RRT Algorithm Selection:* Chosen for its rapid exploration and optimization capabilities.
2. Frontend Technology: ReactJS for a responsive and user-friendly interface.
3. Backend Technology: NodeJS for scalable and high-performance server-side operations.
4. Database: MySQL for reliable data management.

## Front-end Demonstration

### Using ReactJS
1. Create a new React app:

#### npx create-react-app flightnavigation
Navigate to the project directory:
#### cd flightnavigation
Install required packages:
#### npm install react-router-dom
#### npm install styled-components
#### npm install react-chartjs-2
Build the project for production:
#### npm run build
Start the development server:
#### npm start

### Using HTML & CSS
Open the .html file:
You can either host it on a local server or directly open it in a web browser.

### Back-end Demonstration
1. Connect MySQL with python script

## Running the Prototype
To execute the prototype, follow the respective steps for ReactJS or HTML & CSS as detailed above. Ensure you have all dependencies installed and configured correctly for a seamless experience. By following this guide, you can set up and run the Flight Navigation System prototype, demonstrating its capabilities in optimizing air traffic routes and enhancing aviation safety.
