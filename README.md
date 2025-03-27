Gundam Model Showcase
📌 Project Overview
This project is a Gundam Model Showcase website created using Bootstrap. It displays my collection, backlog, and completed builds in an engaging and responsive layout. The goal was to practice HTML, CSS, Accessibility, Responsive Design, and Bootstrap while creating a personal project centered around one of my hobbies: building Gunpla (Gundam plastic models).

🎯 Features
✅ Multi-Image Carousel – Showcases various Gunpla kits
✅ Backlog Section – Displays upcoming builds in a horizontal, image-based layout
✅ Gallery Section – Highlights completed builds with images and descriptions
✅ Fully Responsive Design – Works on desktops, tablets, and mobile devices
✅ Bootstrap-Powered Layout – Minimal custom CSS, utilizing Bootstrap components

Explanation of Each Section
1. Header and Navbar #Task1 and #5
The header contains a responsive navigation bar created with Bootstrap. It features a navbar with links to different sections of the website such as Home, Completed Builds, Backlog, and Wishlist & Fun Facts. There’s also a dropdown menu for categorizing Gunpla models (e.g., Master Grade, Real Grade, High Grade).

The navbar is styled with a dark background (bg-dark) and red text (text-danger).

The logo is clickable and labeled "Gunpla Journey."

The links adapt to different screen sizes using the navbar-expand-lg class.

2. New Banner Section #Task2
This section provides an overview of why the author got into Gunpla. The background is a static image (toonami.jpg), and the content is centered with a semi-transparent dark background for better readability.

The background image is set using inline CSS.

The section includes a heading, a paragraph explaining the personal connection to Gunpla, and a link to a YouTube trailer of the show that inspired the author.

The text is styled with Bootstrap's text-white for contrast against the background.

3. Single Carousel Section #Task 3
This section showcases Gunpla box art in a carousel. Each carousel item contains an image of a different Gundam, with a short description next to it.

The carousel is created using Bootstrap’s carousel component with carousel-inner and carousel-item classes.

Each carousel item has an image and a description inside a flex container. On larger screens, the image and text are arranged side by side.

The carousel is fully navigable with "Previous" and "Next" buttons for users to cycle through the images.

4. Multi-Image Carousel Section #Task 4
Similar to the single carousel section, this one displays multiple Gunpla images side by side. Each image is part of a carousel-item, which is wrapped inside a carousel-inner.

This carousel uses a grid layout with Bootstrap’s grid system (row, col-md-4), so it’s responsive and adjusts the number of images per row based on the screen size.

The images are wrapped inside Bootstrap columns, and navigation controls (Previous and Next) are available to cycle through the carousel items.

5. Completed Builds Section # Task 7
This section lists the completed Gunpla builds under various categories: Master Grade, Real Grade, and High Grade. Each category is represented by a Bootstrap column (col-md-4), and the models in each category are listed as items within an unordered list (<ul>).

The section has a dark background (bg-dark) with red text (text-danger) for contrast.

Each column is labeled with a heading and contains a list of completed Gunpla kits.

6. Backlog Section
This section lists the models that are yet to be built (i.e., the backlog). It is structured similarly to the completed builds section but includes images representing the kits. These images are wrapped inside Bootstrap columns for responsive design.

The section includes images of the kits, and users can visually compare the backlog to the completed builds.

7. Wishlist & Fun Facts # Task 7
The "Wishlist & Fun Facts" section is linked to a second HTML page, Gundam Model Showcase. It provides additional information and fun facts about the hobby and includes a wishlist of upcoming models the author plans to build. It’s a great way to expand on the content and provide a more detailed view of the Gunpla journey.

💡 What I Learned
In this project, I applied my previous knowledge of HTML, CSS, Accessibility, Responsive Design, and Bootstrap to build a well-structured, accessible, and fully functional web page. I used:

Bootstrap’s grid system for layout structuring

Carousel components for dynamic image slideshows

Typography and spacing utilities to keep styles minimal

Bootstrap’s responsiveness for a mobile-friendly experience

🛠 Building Tools

HTML5

Bootstrap 5

CSS (Minimal, only for minor styling adjustments)

Google Fonts

JQuery (For Bootstrap functionality)

For More updates check here: https://spacedandy15.github.io/atlas-bootstrap/