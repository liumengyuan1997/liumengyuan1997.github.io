---
title: "Google Summer of Code 2024 @ Jitsi Meet"
collection: projects
permalink: /projects/GoogleSummerofCode2024@JitsiMeet/
date: 2024-8-26
excerpt: "Implement Raised Hand related features to Jitsi Meet"
---

Details:  

Enhanced [Jitsi Meet](https://meet.jit.si/) with advanced raised hand features, including automatic detection, real-time notifications, and interactive controls to streamline participant management and improve meeting engagement.

Implementation Spotlights:

* Fixed Raised Hand Queue Error: Resolved issues with the raised hand queue to improve functionality. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/14867)

* Hand Management Features: Implemented the ability to lower an individual participant's hand and to lower all hands for the meeting moderator. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/14851)

* Next Speaker Notification: Developed a notification system to prompt the next speaker to prepare for their turn, enhancing meeting flow. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/14904)

* Lower-Hand Notification: Added a notification to alert before a participant's hand is automatically lowered when the dominant speaker changes. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/14960)

* Configurable Raised Hands Features: Introduced a raisedHands object in config.js to group and manage all raised hand features, including enabling/disabling options and selectors for easier updates. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/14975)

* 'View Participants' Action: Added a 'View Participants' action to the notification, allowing users to open the participant pane directly from the notification. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/14959)

* Automated Hand Recognition: Enabled automatic detection and raising of participants' hands via the video stream, streamlining interaction management. [Link to PR](https://github.com/jitsi/jitsi-meet/pull/15001) & [Link to Feature Demo](https://youtu.be/WyY79P1reZI)

Key Learnings:

* Complexity Management: Navigated through thousands of files and effectively managed the inherent complexity involved in implementing these features, enhancing my ability to work with large and intricate codebases.

* Error Resolution: Developed skills in troubleshooting and fixing functional issues within a complex system, enhancing debugging techniques.

* Feature Implementation: Gained experience in adding and managing interactive features and notifications, improving user interaction and system usability.

* Configuration Management: Acquired knowledge in creating and managing flexible configurations, enabling or disabling features, and simplifying updates.

* User Interaction: Improved understanding of user interaction enhancement through real-time notifications and interactive controls.

* Video Stream Integration: Gained insights into integrating video stream data for automatic feature management, enhancing functionality based on live data.

* React Knowledge: Expanded understanding of React, including the use of hooks for managing state and side effects in functional components, which streamlined component logic and improved application performance.