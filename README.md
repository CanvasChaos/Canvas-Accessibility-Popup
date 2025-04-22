<h1 align="center"> Canvas-Accessibility-Popup </h1>

This project enhances the accessibility workflow in Canvas LMS by adding a popup confirmation dialog whenever a user attempts to save content in the Rich Content Editor (RCE) that contains accessibility issues.
By integrating with Canvas' built-in Accessibility Checker, this script intercepts save actions across RCE instances for pages, assignments, syllabus, announcements, and discussions, prompting the user to either:
•	Continue Editing, which opens the Accessibility Checker sidebar to fix issues, or
•	Save Anyway, which proceeds to save the content while acknowledging the unresolved accessibility concerns.
________________________________________
## Features
This script is designed to work with the Canvas LMS platform for announcements, discussions, pages, assignments, and the syllabus. This popup will not work for quizzes (classic or new) or block editor pages. Responsive design has been added to the popup for usage on the canvas mobile app for any pages listed above that have the rich content editor and canvas accessibility checker on the mobile app. 
________________________________________
## Based On
This project is built on and extends dcartertod's accessibility.js script, which provided the initial framework for integrating accessibility checking within Canvas. Additional functionality was added to provide an accessibility warning box to guide the user more effectively and consistently.
________________________________________
## Installation
1.	Download or clone this repository.
2.	Upload the script to your Canvas theme:
  o	Go to Admin > Themes in your Canvas instance.
  o	Select your theme and click Edit.
  o	Under the JavaScript tab, upload this file.

**NOTE: If you already have custom javascript in you canvas instance, please click View File and copy the code to save in you own JS file (unless you already have this saved). Then, paste this new code at the end of your existing JS file and re-upload it to Canvas via the Theme Editor.

3.	Apply and publish the theme to make it live for your institution.
________________________________________
## Accessibility Commitment
This tool is designed to encourage better accessibility compliance and reduce risk for institutions under WCAG and Title II regulations. While it doesn't enforce accessibility fixes, it increases user awareness and offers convenient tools to fix issues before publishing.
________________________________________
## Disclaimer
This project is licensed under the MIT License, which permits reuse, modification, and distribution with proper attribution. However, by using this code, you acknowledge and agree to the following:
•	No Warranty or Liability: This software is provided "as is", without warranty of any kind, express or implied. The author shall not be held liable for any claims, damages, or other liabilities arising from its use or misuse.
•	User Responsibility: You are solely responsible for updating, maintaining, and ensuring the code functions properly within your environment.
•	Partial Accessibility Coverage: The accessibility popup is based on Canvas LMS’s native accessibility checker and does not guarantee full compliance with accessibility standards (such as WCAG 2.1/2.2, Section 508, or Title II requirements). It should be used as a supplementary tool, not a comprehensive solution.
•	No Official Affiliation: This project is not affiliated with or endorsed by Instructure or Canvas LMS. Any references to Canvas are purely for compatibility and functional context.
•	Use at Your Own Risk: Always validate accessibility using multiple tools and follow institutional and legal accessibility guidelines before deploying in production.



