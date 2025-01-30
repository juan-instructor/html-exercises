# 🚀 HTML challenge and exercises

## 📖 Pre-requisites

Before starting this challenge, you should be familiar with the following sections from the [MDN Web Docs](https://developer.mozilla.org/en-US/)

[HTML Images](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_images)

[HTML Video and Audio](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_video_and_audio)

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/HTML_table_basics)

### Challenge #1: Mozilla splash page

If you have not done it already, please work on [Mozilla Splash Challenge](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Mozilla_splash_page).

> [!NOTE]
> Make sure you are doing the exercises locally (on your computer and your server running).

This exercise should be your top priority.

### Challenge #2 Structuring a planet data table

If you have not done it already, please work on [Planet data table](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Planet_data_table).

> [!NOTE]
> Make sure you are doing the exercises locally (on your computer and your server running).

### 🎯 Challenge #3: Event Schedule Table

#### 📌 Overview

In this challenge, you will create an **Event Schedule Table** for a fictional tech conference. Your task is to structure a table that displays information about different conference sessions, including the speaker, time, and topic.

#### 📚 Prerequisites

Before starting, review the following MDN Web Docs articles:

- [HTML Tables Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables)
- [HTML Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
- [HTML Video and Audio](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)

#### 📝 Scenario

You are helping organize a **Web Development Conference** and need to present a **daily schedule** for the event. Attendees should be able to quickly see the session times, topics, and speakers.

#### 🎯 Task

Your goal is to **create a table** that represents the schedule for **Day 1** of the conference.

---

#### 🛠️ Instructions

1. Create an HTML file (`index.html`) and structure the document with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`.
2. Inside the `<body>`, create a `<table>` element with the class `"schedule"`.
3. The table should have the following **columns**:
   - **Time** (When the session happens)
   - **Topic** (What the session is about)
   - **Speaker** (Who is presenting)
   - **Duration** (How long it lasts)
   - **Room** (Where it takes place)
4. Inside the `<thead>` section, define the column headers (`<th>` elements).
5. Inside the `<tbody>`, add the following **schedule rows (`<tr>`)**:

   | Time                | Topic                                | Speaker        | Duration                | Room      |
   | ------------------- | ------------------------------------ | -------------- | ----------------------- | --------- |
   | 09:00 AM - 10:00 AM | Future of JavaScript                 | John Doe       | 1 hour                  | Main Hall |
   | 10:30 AM - 11:30 AM | CSS Animations                       | Jane Smith     | 1 hour                  | Room A    |
   | 12:00 PM - 01:00 PM | Building Accessible Web Apps         | Chris Johnson  | 1 hour                  | Room B    |
   | 02:00 PM - 03:30 PM | Web Security Best Practices          | Alex Lee       | **1.5 hours** (rowspan) | Main Hall |
   | 04:00 PM - 05:00 PM | AI and the Future of Web Development | Samantha Green | 1 hour                  | Room A    |

6. Add a `<caption>` to describe the purpose of the table:
   > "Schedule for Day 1 of the Web Development Conference."
7. Use **row spanning (`rowspan`)** for a session that lasts **more than an hour** (e.g., the 02:00 PM session).
8. Use **column spanning (`colspan`)** to merge two table cells in the header if needed.
9. Include a **footer row (`<tfoot>`)** at the bottom summarizing the total number of sessions for the day.

---

#### 🌟 Bonus Features

- Add **speaker profile images** in the **Speaker** column.
- Embed a **YouTube video** below the table that introduces the conference.
- (Only if you feel comfortable) Style the table using **CSS** to make it more visually appealing.

---

#### 🔍 Hints & Tips

- Use `<th>` for the table headers.
- Make sure the **rowspan** attribute is correctly used for long sessions.
- Add a `<tfoot>` section to summarize the event details.
- Ensure all **images have `alt` text** for accessibility.

---

🚀 **Ready to build your conference schedule? Good luck!**

### 🎯 Challenge #4: Build a Blog Post Page with Multimedia

#### 📌 Overview

In this challenge, you will create a **blog post page** using **semantic HTML** while embedding images and videos. This exercise will help you understand the importance of structuring content properly using elements like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.

---

#### 🛠️ Instructions

1. Create an **HTML file** (`index.html`).
2. Inside the `<body>`, structure the page using **semantic HTML elements**.
3. Your **blog post page** should include the following sections:

   ##### 1️⃣ Header

   - Use a `<header>` element containing:
     - A **blog title** inside an `<h1>` tag.
     - A **navigation menu** (`<nav>`) with at least **three links** (`<a>` tags): Home, About, and Contact.

   ##### 2️⃣ Main Content

   - Use a `<main>` element to hold the **blog article**.
   - Inside `<main>`, create an `<article>` that includes:
     - A **title** (`<h2>`) for the blog post.
     - A **publication date** using the `<time>` element.
     - A **hero image** (`<img>`) with an appropriate `alt` text.
     - A few **paragraphs** (`<p>`) explaining the topic.
     - A **YouTube video** (`<iframe>`) embedded inside the content.
     - A **blockquote** (`<blockquote>`) featuring a quote related to the article’s topic. See [Advanced Text Features](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Advanced_text_features)

   ##### 3️⃣ Sidebar

   - Use an `<aside>` element to include:
     - A **small author bio** with an image (`<img>`).
     - A list (`<ul>`) of **related articles** (these should be simple text links).

   ##### 4️⃣ Footer

   - Use a `<footer>` element that contains:
     - A **copyright notice** (`<p>`).
     - A link to the **blog’s social media** (e.g., Twitter, GitHub).

### Challenge #5: Space Exploration Challenge 🚀

#### Overview

In this challenge, you will apply your knowledge of HTML to build a splash page about **Space Exploration**. You'll add images, a video, and use **semantic HTML elements** to structure your page correctly.

#### Learning Resources

Before starting, make sure to read the following sections from MDN Web Docs:

- [HTML Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images)
- [HTML Video and Audio](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio)
- [HTML Semantic Elements](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

---

#### 🎯 Project Brief

Your task is to complete a **Space Exploration Splash Page**. This page aims to provide exciting information about space missions, space travel, and the universe. However, **no images or videos** have been added yet—**this is your job!** 🎨

#### 🚀 Steps to Complete

#### 1️⃣ Add a Logo to the Header

Inside the `<header>` element, insert an `<img>` element that will embed the **NASA or SpaceX logo**.

#### 2️⃣ Embed a Space Video

Just inside the `<main>` element, embed a **YouTube video** about space exploration:

Use the appropriate **YouTube embedding code**, and set the width to **500px**. _Tip:_ If you don't know how to embed a YouTube video, search for **"Embed a YouTube video in HTML"**.

#### 3️⃣ Add Navigation Links

Inside the `<nav>` element, create an unordered list `<ul>` with three links:

- Home
- Missions
- Gallery

Make sure those links work and there is a page setup for the intended content.

#### 4️⃣ Insert Images into the "Missions" Section

Inside the `<section>` with the class `missions`, you will find three `<article>` elements. Each article represents a different **space mission**:

1. Apollo 11 🚀
2. Mars Rover 🛸
3. James Webb Telescope 🔭

Your task is to **add an image** to each article to represent its mission. Ensure the images are **400px wide**.

#### 5️⃣ Display an Astronaut Image in the Footer

At the bottom of the page, inside the `<footer>`, insert an image of an astronaut floating in space.

---

#### 🛠️ Hints & Tips

- Use the **W3C Nu HTML Validator** to check your HTML for errors.
- **Don't use CSS yet**—just focus on adding and structuring content.

---

#### 🌟 Example Layout

Here’s an idea of what your completed page should look like:

- **Header:** Contains the NASA or SpaceX logo.
- **Navigation Bar:** Includes links for Home, Missions, and Gallery.
- **Main Section:** Contains a **YouTube video** and three articles, each with an image.
- **Footer:** Displays an **astronaut image**.

---

#### 🔥 Stretch Goals (Optional)

- Add an **alt attribute** to all images for better accessibility.
- Look up **figure and figcaption** elements to enhance your layout.
- Experiment with **HTML tables** to display mission data.

---

Happy coding! 🚀🌌✨
