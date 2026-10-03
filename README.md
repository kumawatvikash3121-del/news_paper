📰 Times of India – Newspaper Layout

A simple newspaper-style webpage created using HTML5 and CSS3. This project demonstrates the use of CSS multi-column layouts, borders, text alignment, and the HTML <marquee> element to create a newspaper-inspired design.

📌 Project Overview

The webpage is designed to look like a basic newspaper page. It contains:

A centered Times of India heading.

A scrolling news update section.

Multiple columns for displaying article content.

Centered article headings.

Justified paragraph text.

A beige background.

Borders around the scrolling news section.

🛠️ Technologies Used

HTML5

CSS3

📂 Project Structure
Times-of-India/
│
├── index.html
└── README.md

🚀 How to Run

Create a folder for the project.

Save the provided HTML code as index.html.

Save this documentation as README.md.

Open index.html in any modern web browser.

🎨 CSS Features
Multi-Column Layout

The project uses CSS column-count to divide content into three columns:

.three, .a {
    column-count: 3;
    column-gap: 40px;
    column-rule: 3px solid black;
}


column-count: 3 creates three columns.

column-gap: 40px adds space between columns.

column-rule adds a vertical line between the columns.

Newspaper Background

The webpage uses a beige background:

body {
    text-align: justify;
    background-color: beige;
}

News Update Banner

The <marquee> element is used to display a scrolling news update:

<marquee>
    <h2>Last Updated News Date: 30 july 2026</h2>
</marquee>


The marquee also has top and bottom borders:

marquee {
    border-top: 2px solid black;
    border-bottom: 2px solid black;
}

📄 Page Sections
1. Newspaper Title

The main heading displays:

Times of India

2. News Update

A scrolling banner displays the last updated news date.

3. First Article Section

The .three class creates a three-column layout containing headings and paragraphs.

4. Second Article Section

The .a class also creates three columns and contains multiple article sections with the heading Hello.

✨ Features

📰 Newspaper-inspired layout.

📑 Three-column content structure.

➖ Column separator lines.

📢 Scrolling news banner.

🎨 Beige page background.

📐 Justified text alignment.

🖥️ Simple HTML and CSS implementation.

💡 Possible Improvements

The project can be improved by:

Replacing <marquee> with a modern CSS animation because <marquee> is obsolete in HTML5.

Adding real news articles instead of placeholder Lorem ipsum text.

Adding images to articles.

Making the layout responsive for mobile devices.

Adding a navigation bar.

Using semantic HTML elements such as <header>, <main>, <article>, and <footer>.

Moving the CSS into a separate style.css file.

📜 License

This project is created for educational and practice purposes.
