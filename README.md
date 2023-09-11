**UrbanMigration: A Social App**
**SUMMARY**
- Frontend: Written with JavaScript/React; hosted on GitHub Pages.
- Backend (Server Logic): Written with Node/Express as Lambda functions (FaaS); hosted on AWS (requests come from frontend to Lambda function to data).
- Backend (Database): Google Calendar API.

**Objective **
To build a serverless, progressive web application (PWA) with React using a test-driven development (TDD) technique. The application uses the Google Calendar API to fetch upcoming events.

**Context**
This project involves creating a web application that combines the benefits of serverless architecture and PWAs. Following a TDD approach, the app will provide features like instant loading, offline support, and push notifications. The main functionality revolves around enabling users to search for city-based events, utilizing serverless advantages and PWAs' capabilities for a seamless, scalable, and user-friendly application.

**The 5 Ws**
1. Who — App users: locals, peers, professionals. 
2. What — Web app with a serverless backend, developed using a TDD technique. 
3. When — Users of this app will be able to use it whenever they want to view upcoming events for a specific city. 
4. Where — The server and application is hosted on AWS. Allowing online and offline usage.
5. Why — Taking advantage of serverless infrastructure, PWA user experience, TDD practices, and data visualization.

**Your Project Requirements**
** Key Features: **
1. Filter Events by City.
2. Show/Hide Event Details.
3. Specify Number of Events.
4. Use the App When Offline.
5. Add an App Shortcut to the Home Screen.
6. Display Charts Visualizing Event Details.

**User Stories: **
1. As a user, I would like to be able to filter events by city so that I can see the list of latest events that take place in that city. 
2. As a user, I would like to be able to adjust event details. 
3. As a user, I would like to control the number of events in view on the list. 
4. As a user, I would like to be able to use the app when offline using previously cached events. 
5. As a user, I would like an app shortcut to increase accessibility. 
6. As a user, I would like to be able to see a chart showing the upcoming events in each city so that I know what events are organized in which city.

**Technical Requirements:** 
- React application. 
- Built using the TDD technique. 
- Use the Google Calendar API and OAuth2 authentication flow. 
- Serverless functions calls to AWS lambda for the authorization server. 
- Hosted in a Git repository on GitHub. 
- Compatibility with  Chrome, Firefox, Safari, Edge, and Opera, as well as on IE11. 
- Adaptive design (from 1920px to 320px) 
- Pass Lighthouse’s PWA checklist. 
- Service worker ensures offline and low wifi 
- Compatible with desktop and mobile
- Deployed on GitHub Pages. 
- Alert system using an OOP approach to show information to the user. 
- Data visualization capability. 
- Approximately coverage rate >= 90%. 
- Monitored through online tools

**Serverless Functions Calls**
The application will be using serveless functions to call fo the following actions
- Events from google calendar based on lcoation
- User Auth
- User list
- Filter event function

