# Professional Coach Website

This repository contains the code and configuration for a professional coach's multi-page website, created using Ghost.io. The website is designed to be easily editable by the client, allowing them to update content and add new blog posts autonomously.
https://victoria-valroff.ghost.io/

## Table of Contents
- [Client Requirements](#client-requirements)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Customization](#customization)

## Client Requirements
My client's requirements were clear: she wanted to be able to edit the content (images and text) of her website easily. She requested a multi-page website featuring an "About Me" page, individual pages for each of her coaching targets (individuals, organizations, and CEOs), and a resources page for her blog posts and podcasts. Additionally, she wanted the ability to host her blog on the website and add new articles independently.

Based on her specific needs, I chose Ghost.io as the hosting platform. This solution allowed the client to manage the website autonomously once it was set up. It also provided me with the flexibility to customize the website through their Local Host Edits feature, enabling me to code and tailor the templates to meet her requirements precisely.

## Features

- **Editable Content:** The client can easily edit text and images across the website.
- **Multi-Page Layout:** The website includes multiple pages:
  - **Home Page:** Introduction and highlights.
  - **About Me:** Information about the professional coach.
  - **Coaching Pages:** Separate pages for each coaching target:
    - Individuals
    - Organisations
    - CEOs
  - **Resources Page:** A collection of blog posts and podcast episodes.
- **Blog Integration:** The blog is hosted on the website, allowing the client to add new articles autonomously.
- **Tailored Templates:** Custom templates tailored to the client's needs, using Ghost's Local Host Edits.

## Technologies Used

- **Ghost.io:** A powerful platform for creating and managing content-driven websites.
- **HTML/CSS:** For structuring and styling the website.
- **JavaScript:** For dynamic content and interactivity.

## Setup Instructions

### Prerequisites

- Node.js and npm installed on your machine.
- A Ghost.io account and a hosted instance.

### Installation

1. Clone the repository:
   ```git clone https://github.com/your-username/professional-coach-website.git ```
2. Navigate to the project directory: ```cd professional-coach-website```
3. Install the dependencies: ```npm install```
4. Start the Ghost development environment: ```ghost start```

### Deployment
Log in to your Ghost.io account.
Navigate to your site settings.
Upload the theme files or connect to your repository for continuous deployment.

## Usage

### Editing Content

1. Log in to the Ghost admin panel.
2. Navigate to the page or post you want to edit.
3. Use the editor to update text, images, or other content.
4. Save and publish your changes.

### Adding Blog Posts

1. Log in to the Ghost admin panel.
2. Click on "New Post."
3. Write your blog post using the editor.
4. Add any images or media.
5. Publish the post.

## Customization

### Local Development

To customize the website templates:
1. Navigate to the theme directory: ```cd content/themes/your-theme```
2. Make your changes to the HTML, CSS, or JavaScript files.
3. Restart the Ghost server to see your changes: ```ghost restart```

## Deployment of Custom Changes
1. Ensure your changes are committed to your repository.
2. Push the changes to the remote repository: ```git push origin main```
3. The changes will be deployed to your Ghost.io hosted site.

## Screenshots
Include screenshots of different parts of the website here. For example:

### Home Page:

Home Page: <img width="1511" alt="Screenshot 2024-07-09 at 16 57 46" src="https://github.com/MarineCrou/Victorias-website/assets/140711953/63266971-59ff-43f8-8f74-2022956c3306">
<img width="1441" alt="Screenshot 2024-07-09 at 16 58 18" src="https://github.com/MarineCrou/Victorias-website/assets/140711953/b4a4f460-9820-456e-986a-53e886095fa3">


