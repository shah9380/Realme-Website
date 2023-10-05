
# Realme Website Clone

[Feel Free to Explore](https://shah9380.github.io/Realme-Website/)

## Table of Contents

- [Realme Website Clone](#realme-website-clone)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Screenshots](#screenshots)
  - [Tools and Technologies Used](#tools-and-technologies-used)

## Introduction

This project is a clone of the Realme website's header section. It replicates the header design and functionality of the Realme website. The header is an essential part of a website as it provides navigation and access to different sections of the site.

The header of a website typically contains the logo, navigation links, search functionality, and other important elements that help users navigate the site easily. This clone project aims to recreate the header of the Realme website, including its responsive design and interactivity.

## Features

- Fully responsive header that adapts to different screen sizes.
- Navigation links for various sections of the website.
- Search functionality for users to search for specific content.
- Dropdown menus with subcategories for a user-friendly experience.
- Mobile menu toggle for small screens.

## Screenshots

**Desktop View:**
![Header](https://github.com/shah9380/Realme-Website/assets/130676464/c15e82ae-065f-4aef-8ffe-a8cf3748fb49)


**Mobile View:**

![mobile-header](https://github.com/shah9380/Realme-Website/assets/130676464/ea7740a5-73eb-4354-acb9-b2e94ddf2d75)

## Tools and Technologies Used

- HTML: Used for structuring the header section of the website.
- CSS: Used for styling the header and making it responsive.
- Tailwind CSS: A CSS framework for rapid development and easy styling.
- Font Awesome: For adding custom icons to the header.
- JavaScript: For implementing interactive features like dropdown menus and mobile menu toggle.

This clone project closely mimics the Realme website's header section, providing a similar user experience and functionality. It demonstrates the use of HTML, CSS, and JavaScript to create a responsive and interactive header for a website.

1. **About and Service Section (`<section>`):**
   - This section contains information about "DaretoLeap."

2. **Title (`<h1>`):**
   - The title "DaretoLeap" is displayed at the top of this section.

3. **Two Content Blocks:**
   - There are two content blocks side by side, each containing information and a background image.
   - Each content block is represented by a `<div>` with a background image set using inline CSS (`style="background-image: url(...);"`).
   - Inside each content block, there's a title (e.g., "About realme" and "Our Service") and a description.

4. **"View More" Links (`<a>`):**
   - Each content block includes a "View More" link, presumably leading to more detailed information.

5. **Footer (`<footer>`):**
   - This section represents the footer of the webpage.

    ---Desktop Footer
    ![Footer](https://github.com/shah9380/Realme-Website/assets/130676464/f9dca8de-a5e0-465a-bf36-93a66ab2435e)

   ---Mobile-Footer
    ![Mobile-Footer](https://github.com/shah9380/Realme-Website/assets/130676464/bf671277-1c91-49c7-b19a-91aafebacf1f)


7. **Footer Content:**
   - The footer is divided into several parts, including free shipping, cash on delivery, secure payment, warranty policy, and contact information.
   - Each part is represented by a `<div>` with an icon, title, and description.
   - The footer also includes a "Chat Support" button, operating hours, a phone number, and social media icons.

8. **Mobile and Desktop Navigation:**
   - There's navigation for both mobile and desktop screens. Mobile navigation is in the form of dropdowns that appear when you click on buttons.
   - Desktop navigation consists of lists of recommended products, support links, about realme links, and contact links.

10. **Copyright Notice:**
   - The copyright notice "© 2018-2023 realme. All Rights Reserved." is displayed at the bottom.

This HTML structure creates a webpage with sections for information about "DaretoLeap," product recommendations, support links, and contact information. Users can navigate to different parts of the website and access detailed information about realme products and services. The webpage is designed to be responsive, with different layouts for mobile and desktop screens.

## Java script functioning

1. **Dropdown Menu Functions:**

    - You have a series of functions (e.g., `showDropdownOptionsUser`, `showDropdownOptionsNewLaunch`, etc.) for toggling the visibility of dropdown menus. These functions use `getElementById` to target specific elements with IDs like "optionsUser," "optionPop1," etc., and toggle the "hidden" class to show or hide them.

    - The `Hiding1`, `Hiding2`, etc. functions appear to be used to specifically hide certain dropdown menus by targeting their respective elements and toggling the "hidden" class.

2. **Image Slider Functions:**

    - You have two sets of functions for handling image sliders: one for regular images (`image` class) and one for mobile images (`imagemob` class).

    - `displayimg`, `displayimgmob`, and `currentSlide`, `currentSlidemob` functions manage the display of images in the slideshow. They take an argument `n` to determine which image to display.

    - `nextimg` and `nextimgmob` functions allow you to navigate to the next or previous image in the slideshow by changing the `imageno` or `imagemob` variable and then calling the appropriate `displayimg` or `displayimgmob` function.

    - The slideshow also uses dots (presumably for navigation). The code updates the "active" class on the current dot to indicate the currently displayed image.

3. **CSS Classes:**

    - The functions toggle the "hidden" class on various elements. This class likely has CSS rules that control the visibility of the dropdown menus and images.

4. **Dropdown Toggle Arrows:**

    - The functions for showing dropdown menus also toggle the visibility of arrow elements (e.g., "arrow-down1" and "arrow-up1") to indicate whether the dropdown is expanded or collapsed.

Overall, your code appears to be a combination of JavaScript functions and HTML/CSS classes to create interactive dropdown menus and image sliders on a web page. If you have any specific questions or need further assistance with this code, please let me know.

Feel free to explore the code and customize it further to suit your needs.

---

**What We Learned:**

1. **Tailblocks for Rapid Development:** We learned how to use Tailblocks, a set of pre-designed, customizable UI components built with Tailwind CSS. Tailblocks allowed us to create stylish and responsive elements quickly, saving us valuable development time.

2. **JavaScript for Carousel Creation:** We gained knowledge in JavaScript to implement carousels for image sliders. By utilizing JavaScript functions, we were able to create interactive and dynamic image sliders that enhance user experience on the website.

3. **Responsive Web Design with Media Queries:** We mastered the art of making our webpages responsive. By incorporating CSS media queries, we ensured that our website adapts to various screen sizes and devices, providing an optimal viewing experience for users on both desktop and mobile.

4. **Tailwind CSS for Styling:** We harnessed the power of Tailwind CSS to style our web elements efficiently. Tailwind CSS's utility-first approach enabled us to style components and pages quickly without writing extensive custom CSS.

**Exploration and Resources:**

1. **Stack Overflow:** We frequently turned to Stack Overflow, a valuable resource for developers, to find solutions to various coding challenges and to learn from the experiences of other developers. It provided us with insights and solutions to numerous technical issues.

2. **Flowbite for Tailblocks:** During our project, we explored Flowbite, a library that complements Tailwind CSS and provides additional UI components. It offered us even more options for creating attractive and functional web elements.

3. **Font Awesome for Icons:** To enhance the visual appeal and functionality of our website, we used Font Awesome to easily incorporate icons. This icon library provided a wide range of icons that seamlessly integrated into our design.

In summary, your project involved learning and applying various tools and techniques for efficient web development, from using Tailblocks and JavaScript for dynamic elements to creating responsive designs with media queries and leveraging external resources like Stack Overflow, Flowbite, and Font Awesome to enhance your web project. This blend of learning and exploration contributed to the success of your web development endeavor.


##About Team
Our team members collaborated exceptionally well to tackle the challenges encountered during the project's creation. We faced issues with linking pages, creating the carousel, implementing the header popup, and managing overflow on team pages. 

Let's show our appreciation to Priyanshu, our mentor, for their invaluable guidance. Priyanshu not only provided daily updates but also fostered unity within the team throughout this project.

Great job, team, for the outstanding collaboration and a big thank you to Priyanshu for being an incredible mentor! 🙌
Note: This project is a clone for educational purposes and is not affiliated with the Realme brand. All trademarks and copyrights belong to their respective owners.
