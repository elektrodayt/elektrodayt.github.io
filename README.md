🚀 Ignacy Tech – Official Website

Official landing page for the Ignacy Tech YouTube technology channel.
The project is hosted using GitHub Pages and designed as a simple, modern, and easily customizable website.

🌐 Live website:
https://ignacytech.github.io

✨ Features
🌙 Dark / Light Mode

Dark mode is enabled by default.
The toggle button is located in the top-left corner.

Behavior:

Dark mode: white background button with black text and 🌑 icon

Light mode: black background button with white text and ☀️ icon

All colors are controlled using CSS variables.

🌍 Language Switch (PL / EN)

The language switch button is located in the top-right corner.
Default language is Polish.

The switch updates:

Page title

Description text under the logo

Button labels

Footer text

Button styling:

Dark mode: white background with black text

Light mode: black background with white text

🔗 Social Media Buttons

The website includes buttons for:

YouTube (red – official YouTube color)

Discord (blue – official Discord color)

Instagram (gradient style)

All buttons include hover animations.

🐙 GitHub Repository Button

The GitHub repository button is located in the bottom-left corner.

Button text:

Polish: Repozytorium GitHub

English: GitHub Repository

Button styling:

Dark mode: white button with black text

Light mode: black button with white text

The button links directly to the project repository.

🖼️ Channel Logo

The channel logo is displayed at the top of the page.

Default file used:
channels4_profile.jpg

The image file must be located in the same directory as index.html.

🧭 Footer

The footer displays:
© 2026 Ignacy Tech

It also contains a clickable Privacy Policy link.
The privacy policy is stored in a separate file named privacy.html.

🔐 Privacy Policy

The privacy policy:

Is implemented as a separate HTML file

Is accessible from the footer

Supports both Polish and English

Does not use a cookie consent popup (EU-style informational notice)

⭐ Favicon

The website supports a favicon.

Required file:
favicon.ico

The file must be placed in the root directory of the project.
The favicon can be generated from the channel logo using an online favicon generator.

📂 Project Structure

ignacytech.github.io/
├── index.html
├── privacy.html
├── channels4_profile.jpg
├── favicon.ico
├── README.md
└── LICENSE

⚙️ Customization Guide
1️⃣ Change Channel Name

Edit the main heading in index.html:

<h1>Ignacy Tech</h1>

Replace Ignacy Tech with your own channel or brand name.

2️⃣ Change Text Under the Logo

Edit the description paragraph:

<p id="desc">Witaj na oficjalnej stronie kanału YouTube Ignacy Tech!</p>
3️⃣ Change Social Media Links

Update the URLs in the <a> tags in index.html:

YouTube

Discord

Instagram

GitHub Repository

4️⃣ Change Profile Image (Logo)

Replace the image file with your own logo or profile picture.
Rename the image file to your own filename including the extension (for example: logo.png, profile.jpg).

Update the image source:
<img src="yourfilename.extension" class="logo">

The image file must be located in the same folder as index.html.

5️⃣ Change Page Title (Browser Tab)

Edit the <title> tag in the <head> section:

<title>Your Channel Name - Technology Channel</title>

This title is displayed in the browser tab and search results.

6️⃣ Styling

All styling is defined directly inside the <style> section of index.html.

You can customize:

Background colors

Text colors

Button colors

Font sizes

Hover effects and animations

No CSS framework is required.

📄 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute the project.

🛠️ Technologies Used

HTML5
CSS3 (CSS Variables)
Vanilla JavaScript
GitHub Pages

📌 Project Status

Active
Maintained
Beginner-friendly
Fully customizable
