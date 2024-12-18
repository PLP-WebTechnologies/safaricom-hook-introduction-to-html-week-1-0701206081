[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple webpage demonstrating basic HTML structure with text, images, and links">
    <title>Simple Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #f4f4f4;
            padding: 0.5rem 0;
            text-align: center;
        }
        nav a {
            margin: 0 1rem;
            text-decoration: none;
            color: #333;
        }
        section {
            padding: 1rem;
        }
        article {
            margin-bottom: 1.5rem;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>This is a simple webpage designed to demonstrate the use of basic HTML tags and semantic structure. It includes text, images, and links to make it functional and user-friendly.</p>
    </section>
    <section id="gallery">
        <h2>Gallery</h2>
        <article>
            <h3>Beautiful Nature</h3>
            <img src="https://i.ebayimg.com/images/g/QHoAAOSwVlJli~4L/s-l960.webp" alt="Nature Image" style="max-width:100%;" width = "50">
            <p>Explore the beauty of nature through stunning visuals.</p>
        </article>
        <article>
            <h3>Architecture Wonders</h3>
            <img src="https://media.istockphoto.com/id/506393198/photo/great-wall-of-china.jpg?s=612x612&w=0&k=20&c=cJti-RrdUUkLX_zgzi6KgPbgApHoxJtMJSvlRUYqOzg=" alt="Architecture Image" style="max-width:100%;" width = "50">
            <p>Marvel at the incredible architectural designs from around the world.</p>
        </article>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Feel free to reach out to us for more information.</p>
        <ul>
            <li>Email: <a href="mailto:val@gmai.com">val@gmai.com</a></li>
            <li>Phone: <a href="tel:+254 711 846 096">+254 711 846 096</a></li>
            <li>Address: 1842 Meru </li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2024 Simple Webpage. All rights reserved.</p>
    </footer>
</body>
</html>


