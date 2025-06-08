````markdown
# Markdown Previewer

## Project Objective

Build a functional Markdown Previewer app similar to this demo:  
[https://markdown-previewer.freecodecamp.rocks/](https://markdown-previewer.freecodecamp.rocks/)

The app should allow users to write GitHub-flavored Markdown text and see a live HTML preview.

---

## Technologies Allowed

- Frontend Framework: **React** (recommended), but you can also use HTML, CSS, JavaScript, Bootstrap, SASS, Redux, or jQuery.
- External Libraries: Use the [Marked](https://cdnjs.com/libraries/marked) library to parse Markdown into HTML.
- Note: React 18 has known test incompatibilities; use React 17 if possible.

> ⚠️ Additional frameworks like Angular or Vue are not officially supported for this project.

---

## User Stories

Your app must satisfy the following:

1. **Textarea Editor**  
   A textarea element with `id="editor"` must be present.

2. **Preview Element**  
   An element with `id="preview"` must be present to display rendered HTML.

3. **Live Preview**  
   When typing into the `#editor`, the `#preview` updates live to show the parsed Markdown.

4. **GitHub-Flavored Markdown Support**  
   Markdown entered in `#editor` should render as HTML in `#preview` using the Marked library.

5. **Default Content on Load**  
   When the app loads, the `#editor` should contain default Markdown that includes:  
   - H1 heading  
   - H2 subheading  
   - Link  
   - Inline code  
   - Code block  
   - List item  
   - Blockquote  
   - Image  
   - Bold text  

6. **Rendered Default Content**  
   The default Markdown must be parsed and displayed in the `#preview` on page load.

---

## Optional Bonus

- Support carriage returns in Markdown to render `<br>` line breaks in the preview.

---

## Setup Instructions

You can develop your project in any environment, but here’s how to get started on **CodePen**:

1. Go to this CodePen template:  
   [https://codepen.io/freeCodeCamp/pen/MJjpwO](https://codepen.io/freeCodeCamp/pen/MJjpwO)

2. Click **Save** to fork your own copy.

3. Add your code to the HTML, CSS, and JavaScript panels.

4. To enable the FreeCodeCamp testing suite, add this script tag inside the `<body>` of your HTML panel:  
   ```html
   <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
```
5. Run your project and make sure **all tests pass**.

6. Submit the URL of your working project.

---

## Resources

* Marked Library CDN:

  ```html
  <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
  ```
* FreeCodeCamp Test Suite Documentation:
  [https://www.freecodecamp.org/learn/front-end-development-libraries/front-end-libraries-projects/build-a-markdown-previewer](https://www.freecodecamp.org/learn/front-end-development-libraries/front-end-libraries-projects/build-a-markdown-previewer)

---

## Happy Coding! 🎉

Feel free to customize styles and add your own personal touch to make the Markdown Previewer unique.

---

```
