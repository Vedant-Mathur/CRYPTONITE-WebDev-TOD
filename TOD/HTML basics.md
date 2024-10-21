# HTML vs CSS vs JS
- **HTML (HyperText Markup Language)**:  
  - Structure: Defines the basic structure and content of a webpage.
  - Elements: Uses tags like `<div>`, `<h1>`, `<p>`, etc., to organize text, images, links, and other elements.

- **CSS (Cascading Style Sheets)**:  
  - Styling: Controls the visual presentation of HTML elements (colors, fonts, layout, spacing).
  - Syntax: Uses selectors (like `#id`, `.class`) to apply styles (`color: red;`, `font-size: 16px;`).

- **JavaScript (JS)**:  
  - Behavior: Adds interactivity and dynamic functionality to webpages (e.g., form validation, animations).
  - Execution: Runs in the browser and responds to user actions, like clicks and form submissions.



# **HTML Elements**
Define parts of a webpage (e.g., paragraphs, images).
- **Tags**: Enclose content within opening `<tag>` and closing `</tag>`. Void elements like `<img>` don’t need closing tags.
- **Semantic HTML**: Uses meaningful tags (like `<header>`, `<article>`) to improve accessibility and SEO.
- **Nesting**: Tags can be placed inside one another, forming a structure.

# HTML Boilerplate

- **Boilerplate Structure**: The basic template for every HTML document includes `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` elements.
- **DOCTYPE**: Declares HTML5 and helps browsers render the page correctly.
- **HTML Element**: The root element enclosing all content.
- **Head Element**: Contains meta-information, like `<meta charset="UTF-8">` and `<title>`.
- **Body Element**: Contains all visible content for users.
- **lang** specifies the language of the text content in that element
- **VS code shortcut**: !
# Working with Text

- **Introduction**: Most web content is text-based; this lesson covers essential HTML text elements.
- **Key Topics**:
  - Creating paragraphs using `<p>`.
  - Using headings from `<h1>` to `<h6>`.
  - Bold text with `<strong>` and italicized text with `<em>`.
  - Understanding nested elements and indentation.
  - Writing HTML comments using `<!-- comment -->`.
  - **VSC shortcut for comments**: Ctrl+/.
# Lists

- **Introduction**: This lesson focuses on creating and using lists in HTML.
- **Types of Lists**:
  - **Ordered Lists**: Use `<ol>` for numbered items.
  - **Unordered Lists**: Use `<ul>` for bullet points.
  - **Definition Lists**: Use `<dl>` for terms and descriptions.
  - **Element listing**: Use `<li>` for listing elements.
- **Nesting**: Lists can be nested within each other for complex structures.
# Links and Images

- **Introduction**: This lesson teaches creating links and embedding images in HTML, essential for navigating the web.
- **Anchor Elements**: Use the `<a>` tag with `href` to create links. 
- **Absolute vs. Relative Links**: Absolute links include the full URL, while relative links refer to paths within your site.
- **Security**: Use `target="_blank"` with `rel="noopener noreferrer"` for links to improve security and prevent tabnabbing.
- **Practice**: Create a directory for your project, set up `index.html`, and link to an `about.html` page for hands-on experience.
- **Metaphor**: Absolute links are like full directions to a location (URL), while relative links are simpler directions within a website.
- **Images**: Use the `<img>` tag with the `src` attribute to display images. The `alt` attribute provides alternative text if the image cannot load or for screen readers.
- **Parent Directories**: Use `../` to access files from a parent directory.
# Commit Messages

Commit messages play a crucial role in version control, offering context and clarity to code changes. Effective commit messages:
- Provide a brief but descriptive summary of changes.
- Follow a structure: subject line, body (optional), and footer (optional).
- Help future developers understand the code’s history and intent.

Good commit messages improve collaboration, debugging, and overall project maintainability. They should be concise yet informative, explaining **why** the changes were made.
