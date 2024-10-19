### Task: Build and Style a Webpage About Your Favorite Animal Using External CSS

1. **Objective**: Learn how to create and link an external CSS file, then use it to style a multi-section webpage.
2. **Instructions**:
   - Create an HTML file that introduces your favorite animal.
   - Structure your HTML page with a heading, a description, a list of fun facts, and a photo of the animal.
   - Create an external CSS file to style your webpage.
   - Link the external CSS file to your HTML document.

3. **Requirements**:
   - **Background & Layout**: Change the background color of the page and add padding around the content.
   - **Title (H1)**: Style the title with a different font size, color, and center it.
   - **Description (Paragraph)**: Change the font size and font family of the description paragraph.
   - **Fun Facts (List)**: Style a list of at least 3 fun facts. Make the list items have custom bullet points and change the color.
   - **Image**: Add an image of the animal (you can use a placeholder image if needed) and style it with a border and some margin.
   - **Footer**: Add a footer with a background color and centered text.

4. **Example**:

**Step 1: Create the HTML file (save as `animal.html`)**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Favorite Animal: Elephants</title>
    <!-- Link to the external CSS file -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Page Title -->
    <h1>Elephants: The Gentle Giants</h1>

    <!-- Description Section -->
    <p>
        Elephants are the largest land animals on Earth. They are known for their intelligence, strong social bonds, and long trunks.
        They live in family groups, care for one another, and display emotions like joy and grief.
    </p>

    <!-- Fun Facts Section -->
    <h2>Fun Facts About Elephants</h2>
    <ul>
        <li>Elephants use their trunks for smelling, drinking, and grabbing things.</li>
        <li>An elephant's skin can be up to 2.5 cm thick!</li>
        <li>They can communicate with each other through vibrations.</li>
    </ul>

    <!-- Image Section -->
    <h2>Elephant in the Wild</h2>
    <img src="https://via.placeholder.com/300" alt="Elephant image">

    <!-- Footer Section -->
    <footer>
        © 2024 Elephant Enthusiasts Club
    </footer>

</body>
</html>
```

**Step 2: Create the CSS file (save as `styles.css`)**

```css
/* Set a background color and add padding */
body {
    background-color: #f0f8ff; /* Light blue background */
    padding: 20px;
    font-family: Arial, sans-serif; /* Global font family */
}

/* Style the main heading */
h1 {
    color: #4CAF50; /* Green color */
    font-size: 36px;
    text-align: center;
}

/* Style the paragraph */
p {
    font-size: 18px;
    line-height: 1.6;
    color: #333;
}

/* Style the subheadings */
h2 {
    color: #2f4f4f;
    font-size: 28px;
}

/* Style the list */
ul {
    list-style-type: square; /* Custom bullet points */
    color: #556b2f; /* Dark olive green */
}

li {
    margin-bottom: 10px;
}

/* Style the image */
img {
    display: block;
    margin: 20px auto;
    border: 5px solid #ddd;
    border-radius: 10px;
}

/* Style the footer */
footer {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
    font-size: 14px;
}
```

5. **How to run**:
   - Make sure both `animal.html` and `styles.css` are saved in the same folder.
   - Open the `animal.html` file in a web browser to see the styled webpage.

6. **Additional Challenge**:
   - Experiment with adding **hover effects** to the image.
   - Add a **different font** to your title using Google Fonts.

---

### Explanation:
- This task teaches students the basics of **external CSS** and how to structure a simple HTML webpage with different sections.
- The use of an external CSS file helps them understand how to separate styling from the content.
- The added complexity of different sections (like the image, list, and footer) allows students to practice applying different styles for various HTML elements.
  
Try  to add more fun facts, play with colors, fonts, and styles, and make the page their own!
