# Frontend Intern Task README

## Table of Contents

- [Project Overview](#project-overview)
- [Task Description](#task-description)
- [Implementation](#implementation)
- [Error Handling](#error-handling)
- [Testing](#testing)
- [Contributing](#contributing)

## Project Overview

This repository contains my solution for the Frontend Intern Task. The task involved creating a web page using HTML, CSS, and JavaScript.I created and host a simple single-page website outlining my goals for the next 2 years in the tech field.
Each required element had a specified `data-testid` attribute for easy identification and testing.

## Task Description

The task requirements were as follows:

1. Display your Slack Display.
Attribute: data-testid="slackDisplayName"

2. Current Time in UTC:Display the current time in UTC.
Attribute: data-testid="currentTimeUTC"
Format: HH:MM:SS
Example: 12:34:56
Note: The time should be updated every second.

3. Current Day of the week (e.g. Monday, friday):Display the current Day of the week.
Attribute: data-testid="currentDayOfWeek"
Example: Monday

4.Slack Email:Display your Slack Email.
Attribute: data-testid="slackEmail"
Example: your.slack.email@slack.com

5. Slack profile pictureDisplay your Slack Profile Picture
Attribute: data-testid="slackProfilePicture"
Example: https://example.com/your-profile-picture.png


6. Add a link to hng.tech/learn.Attribute: data-testid="hngLink"
Add a link to keyword.dogAttribute: data-testid="keywordLink"
Add a link to scrapeanyweb.siteAttribute: data-testid="scrapeanywebLink" 


## Implementation

To fulfill the task requirements, I followed these steps:

### HTML Structure

I created the basic structure of the web page using HTML, including all the required elements with their respective `data-testid` attributes.

### CSS Styling

I applied CSS styling to enhance the visual appeal of the page. The styling included backgrounds, fonts, colors, and responsive design for a better user experience.

### JavaScript for Real-Time Data

I used JavaScript to dynamically update the current day of the week and UTC time in milliseconds. I also added a function to handle errors, such as missing profile pictures or HNG URLs.

### GitHub Hosting

I hosted the web page on GitHub Pages, making it accessible via the URL: [https://github.com/abstaina44/HNG-Frontend-Task.git](https://github.com/abstaina44/HNG-Frontend-Task.git).

### Testing

I tested the page thoroughly to ensure that all elements were displayed correctly, real-time data updated as expected, and error handling worked as intended. I used the `data-testid` attributes for testing.

## Error Handling

Error handling was implemented to improve user experience:

- **Missing Profile Picture**: If the Slack profile picture is missing, the code displays a default image and provides a default alt text for accessibility.
- **Missing HNG URL**: If the GitHub repository URL is not found, the code displays an error message and removes the link to prevent broken links.

## Testing

To ensure the functionality and correctness of the web page, I performed testing by:

- Checking that all elements were displayed as specified in the task description.
- Verifying that the current day of the week and UTC time were updated in real-time.

## Contributing

I welcome contributions and feedback to improve this project. If you have any suggestions or find issues, please open an issue or submit a pull request.

Thank you for reviewing my solution!

Made with 🤍 by Ephraim Abstaina
