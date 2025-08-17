#f4f4f4;
    color: #333;
}

/* Header styles */
header {
    background: #007BFF; /* Bootstrap primary color */
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2em;
}

/* Navigation styles */
nav {
    margin: 20px 0;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* About section styles */
.about {
    padding: 20px;
    background: #fff;
    margin: 20px auto;
    max-width: 800px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.about h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

.about p {
    margin-bottom: 15px;
}

/* Skills section styles */
.skills {
    padding: 20px;
    background: #fff;
    margin: 20px auto;
    max-width: 800px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.skills h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

.skills ul {
    list-style: none;
}

.skills ul li {
    background: #007BFF;
    color: #fff;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
}

/* Projects section styles */
.projects {
    padding: 20px;
    background: #fff;
    margin: 20px auto;
    max-width: 800px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.projects h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

.project {
    margin-bottom: 15px;
}

.project h3 {
    font-size: 1.5em;
}

.project p {
    margin: 5px 0;
}

/* Contact section styles */
.contact {
    padding: 20px;
    background: #fff;
    margin: 20px auto;
    max-width: 800px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.contact h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

.contact form {
    display: flex;
    flex-direction: column;
}

.contact label {
    margin-bottom: 5px;
}

.contact input, .contact textarea {
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact button {
    padding: 10px;
    background: #007BFF;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact button:hover {
    background: #0056b3;
}

/* Footer styles */
footer {
    text-align: center;
    padding: 20px 0;
    background: #007BFF;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}
```

### Explanation of the CSS:

1. **Reset Styles**: The `*` selector resets margin and padding for all elements to ensure consistency across browsers.
2. **Body Styles**: Sets the font, line height, background color, and text color for the entire page.
3. **Header**: Styles the header with a background color, text color, and padding.
4. **Navigation**: Styles the navigation links to be inline and visually appealing.
5. **Sections**: Each section (about, skills, projects, contact) has a consistent style with padding, background color, margin, border-radius, and box-shadow for a card-like appearance.
6. **Skills**: Each skill is displayed in a colored box for emphasis.
7. **Projects**: Each project has its own styling for titles and descriptions.
8. **Contact Form**: Styles the contact form for user input with padding and border-radius.
9. **Footer**: Styles the footer to match the header.

### Usage:
To use this CSS, save it in a file named `styles.css` and link it in the HTML of Kevin Alvarado's portfolio like this:

```html
<link rel="stylesheet" href="styles.css">
```

Feel free to modify the styles according to Kevin's branding, preferences, or specific content in his CV.