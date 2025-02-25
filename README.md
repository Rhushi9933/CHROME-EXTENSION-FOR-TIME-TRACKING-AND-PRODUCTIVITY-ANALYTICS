# CHROME-EXTENSION-FOR-TIME-TRACKING-AND-PRODUCTIVITY-ANALYTICS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Gaikwad Rhushabh Navnath

*INTERN ID*: CT6WLNC

*DOMAIN*: Full Stack Web Development

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH

*DISCRIPTION*:(Min 500 words)

Productivity Tracker: A Chrome Extension for Website Time Tracking and Analytics

Introduction

In today’s digital world, managing online activities effectively is essential for maintaining productivity. Many individuals struggle with spending excessive time on unproductive websites, leading to decreased efficiency in their personal and professional lives. To address this issue, Productivity Tracker, a Chrome extension, has been developed to monitor the time users spend on various websites and provide insightful analytics.

This extension tracks browsing habits, classifies websites as productive or unproductive, and generates detailed reports. The tool enables users to understand their internet usage patterns and optimize their productivity by limiting distractions.

Project Overview

The Productivity Tracker Chrome extension consists of three main components:

1.	Tracking System: This feature logs the time spent on different websites. The extension runs in the background and continuously records the active tab's URL and duration.

2.	Analytics Dashboard: A user-friendly dashboard displays categorized reports, showing productive vs. unproductive time spent online.
 
3.	Custom Website Classification: Users can define specific websites as productive or unproductive, allowing for personalized tracking based on individual needs.
   
This extension is designed for students, professionals, and anyone who wants to develop better digital habits.

Key Features

1. Automatic Website Time Tracking

The extension starts tracking time as soon as the browser is opened. It detects when users switch between tabs and accurately logs the duration spent on each site. This tracking continues seamlessly in the background without requiring user intervention.

2. Categorization of Websites

Users can classify websites as productive (e.g., coding platforms, educational sites) or unproductive (e.g., social media, entertainment sites). This classification helps users analyze their internet usage effectively.

3. Detailed Productivity Reports

The extension provides users with a weekly breakdown of their browsing history, including:

•	Total time spent on each website

•	Percentage of productive vs. unproductive time

•	Trends and insights based on browsing behavior

4. Real-time Data Synchronization

Data is stored using Chrome’s local storage, ensuring user privacy and offline accessibility. Optionally, the extension can integrate with a backend (e.g., Firebase or a custom database) to sync data across multiple devices.

5. Interactive Popup Interface

The extension includes a popup UI that gives users a quick summary of their current session. By clicking the extension icon, users can view real-time data about the websites they’ve visited and their corresponding time logs.

6. Customizable Settings

The settings page allows users to manage:

•	The list of productive and unproductive websites

•	Alerts or notifications when exceeding a predefined time limit

•	Weekly or daily report preferences

Technical Implementation

1. Chrome Extension Structure

The extension consists of multiple files:

•	manifest.json – Defines extension settings and permissions

•	background.js – Handles time tracking and manages data storage

•	content.js – Sends data to background scripts

•	popup.html & popup.js – Displays real-time stats in a small interface

•	options.html & options.js – Provides a UI for users to classify websites

2. Tracking Time with Chrome API

The extension uses the chrome.tabs API to detect when a user switches tabs or opens a new website. The time spent on each tab is recorded and stored locally.

3. Data Storage

Time logs are stored in Chrome’s local storage (chrome.storage.local) to maintain user privacy. If a backend is implemented, it will store the data in a cloud database for synchronization across devices.

Benefits of Using This Extension

1.	Increased Productivity: Users can identify and minimize time spent on distractions.

2.	Better Time Management: Helps users stay focused on important tasks by tracking digital habits.

3.	Data Privacy: No personal data is shared, as everything is stored locally (unless cloud sync is enabled).

4.	User-Friendly Interface: The popup UI and dashboard provide an easy-to-understand summary of browsing habits.

5.	Customizable Experience: Users have complete control over how websites are categorized and monitored.

Future Enhancements

In future updates, the extension can include additional features such as:

•	Goal Setting: Users can set daily time limits for specific websites.

•	AI-based Categorization: Automating the classification of websites based on browsing patterns.

•	Mobile Compatibility: Expanding functionality to mobile browsers for cross-platform tracking.

Conclusion

Productivity Tracker is a powerful Chrome extension designed to help users take control of their online habits. By tracking time spent on various websites, classifying them based on productivity, and providing insightful analytics, this tool empowers individuals to make more informed decisions about their browsing behavior. Whether you’re a student, professional, or someone looking to boost efficiency, this extension is a valuable addition to your productivity toolkit.

*Output:*
![Image](https://github.com/user-attachments/assets/8f958e22-040c-4646-8a27-7ad630c42bb3)
