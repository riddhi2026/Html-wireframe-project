Personal Portfolio Website

A simple, clean, and responsive personal portfolio website created using HTML5 and CSS3. This project presents personal information, skills, projects, education, certifications, and contact details in a structured portfolio layout.

📌 Project Overview

This portfolio website is designed to showcase a developer's:

Personal introduction

About Me information

Technical skills

Projects

Educational background

Certified courses

Contact information

The website uses a simple grid-based layout with borders, typography, colors, and responsive CSS to create a professional portfolio page.

🛠️ Technologies Used

HTML5

CSS3

CSS Grid

CSS Flexbox

CSS Media Queries

CSS Gradients

CSS clip-path

📂 Project Structure
portfolio/
│
├── index.html
└── README.md

✨ Website Sections
1. Navigation Bar

The navigation bar contains:

Portfolio logo

Home

About Me

Skills

Project

Education

Contact

Hire Me button

The navigation links use HTML anchor links to move to different sections of the page.

2. Hero Section

The hero section introduces the portfolio owner.

It contains:

Introduction

Name

Professional field

Short description

Profile image

Example:

<h1>Hello I'm</h1>
<h2>Your Name</h2>
<h3>Your field Name</h3>

3. About Me

The About Me section contains:

Profile image

Personal description

Highlighted text using the <mark> element

The section uses CSS Grid to divide the image and text areas.

4. Skills

The Skills section currently displays four skills:

C

HTML5

CSS3

Bootstrap

Each skill is represented using a colored CSS shape.

5. Projects

The Projects section contains three sample projects:

Crypto / Food UI

Food Delivery

Off-Road Cars

CSS gradients are used to create the project backgrounds without requiring separate project images.

6. Education

The Education section contains:

10th SSC — Kasturba Vidyabhavan

12th HSC — Kasturba Vidyabhavan

Diploma Computer Engineering — Vidhyadeep University

7. Certified Courses

The portfolio displays two certified courses:

GIM — Red & White Multimedia Education

Master Full Stack Web Developer — Red & White Multimedia Education

8. Contact

The Contact section contains:

Mobile number

Email address

LinkedIn ID

The current values are placeholder information and can be replaced with real contact details.

9. Footer

The footer contains:

Portfolio logo

Navigation links

Contact information

📱 Responsive Design

The website includes a responsive layout using:

@media (max-width: 768px)


On smaller screens:

Navigation links wrap

Hero content becomes vertically arranged

About section becomes a single column

Skills change to two columns

Projects become a single column

Education becomes a single column

Certificates become a single column

Contact information becomes a single column

Footer columns become vertically arranged

🎨 Design Features

The website uses:

Times New Roman typography

White background

Gray borders

Blue section headings

Red and blue hero text

CSS Grid layouts

Flexbox alignment

CSS gradients

Responsive media queries

Minimal and simple visual styling

🖼️ Images

The current portfolio uses external image URLs for the profile images.

For a more reliable website, images can be downloaded and stored locally.

Recommended structure:

portfolio/
│
├── index.html
├── README.md
└── images/
    ├── profile.jpg
    └── about.jpg


Then use:

<img src="images/profile.jpg" alt="My Profile">

🚀 How to Run

No installation or additional dependencies are required.

Step 1

Download or clone the project.

Step 2

Open the project folder.

Step 3

Open:

index.html


in any modern web browser.

✏️ Customization

You can customize the portfolio by replacing the placeholder content.

Change Name
<h2>Your Name</h2>


Replace Your Name with your actual name.

Change Profession
<h3>Your field Name</h3>


Replace it with your profession or specialization.

Change About Me

Edit the text inside:

<div class="about-text">

Change Skills

Add or remove skills inside:

<div class="skills">

Change Projects

Edit the project names inside:

<div class="projects">

Change Education

Update the content inside:

<div class="education">

Change Contact Details

Replace the placeholder:

+91 0123456789
xyz12@gmail.com
xyz12


with your actual contact information.

⚠️ Current Limitations

The Hire Me button does not currently perform an action.

Project cards are currently visual placeholders.

Contact information is placeholder data.

LinkedIn is displayed as text rather than an active link.

The welcome marquee is disabled using CSS.

External profile images depend on their source URLs being available.

🔮 Future Improvements

Possible improvements include:

Add JavaScript functionality

Add working Hire Me button

Add project links

Add GitHub and LinkedIn links

Add downloadable resume

Add contact form

Add project images

Add animations

Add dark mode

Add skill progress indicators

Improve accessibility

Add SEO metadata

📄 License

This project is created for personal and educational purposes. You can modify and customize the source code for your own portfolio.

👤 Author

Your Name

Field: Your Field Name

Email: xyz12@gmail.com

LinkedIn: xyz12
