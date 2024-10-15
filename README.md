Testimonial Carousel Project
This project is a Testimonial Carousel that uses Bootstrap 5 for a simple, responsive design. The carousel allows users to cycle through testimonials, each of which includes a circular profile image, a testimonial text, the person's name, and their job title.

Technologies Used
HTML: To structure the content of the testimonials.
CSS: For basic styling of the layout and carousel elements.
Bootstrap 5: Used for the carousel functionality, responsiveness, and layout design.
JavaScript (Bootstrap's Bundle): Bootstrap’s carousel functionality is powered by JavaScript to enable transitions and controls.
Features
Carousel Transition: Testimonials auto-slide at regular intervals. Users can also manually navigate through testimonials using the previous and next buttons.
Responsive Design: The layout adjusts to different screen sizes, ensuring a good user experience on both mobile and desktop.
Profile Images: Each testimonial displays a circular profile image along with the review.
How to Run the Project Locally
Prerequisites
Ensure you have a modern browser (Chrome, Firefox, etc.) that supports Bootstrap 5.
No additional installations are required, as Bootstrap is being used via a CDN.
Steps to Run Locally
Clone or Download the Repository

You can clone the repository using:
bash
Copy code
git clone https://github.com/yourusername/testimonial-carousel.git
Alternatively, you can download the .zip file and extract it to your preferred folder.
Set Up the HTML and Bootstrap

Open the index.html file in your preferred text editor (like VSCode or Sublime).

Make sure that the Bootstrap CDN is included in the <head> section:

html
Copy code
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
Run Locally

Open the index.html file in your browser directly by double-clicking it.
The testimonial carousel should be visible, and you can manually scroll through the testimonials using the left and right navigation arrows.
How to Deploy and Run the Project Live
To make this project live, you can deploy it using free hosting services like GitHub Pages, Netlify, or Vercel. Here's how:

1. Deploying on GitHub Pages
Step 1: Commit and push your project to a GitHub repository.
Step 2: Go to the repository settings and scroll down to the GitHub Pages section.
Step 3: Under "Source," select the branch (usually main or master) and click Save.
Step 4: Your site will be live at https://yourusername.github.io/repositoryname.
2. Deploying on Netlify
Step 1: Sign up for a free account at Netlify.
Step 2: Click New site from Git and connect your GitHub repository.
Step 3: Choose the repository where your project is stored and click Deploy.
Step 4: Your project will be live on a Netlify domain (you can also configure custom domains if needed).
3. Deploying on Vercel
Step 1: Sign up for a free account at Vercel.
Step 2: Click New Project and import your GitHub repository.
Step 3: Follow the instructions to deploy your project, and it will be live on a Vercel domain.
Adding More Testimonials
To add more testimonials to the carousel:

Copy and paste the carousel-item div block within the carousel-inner section.
Ensure only one item has the active class.
Update the profile image, testimonial text, name, and designation for each new testimonial.
Example:

html
Copy code
<div class="carousel-item">
  <img src="newprofile.jpeg" class="rounded-circle" alt="New Person" width="100">
  <p class="mt-4">This is a new testimonial text.</p>
  <h5 class="font-weight-bold text-success">New Person</h5>
  <span class="text-muted">New Job Title</span>
</div>
License
This project is open-source and licensed under the MIT License.
