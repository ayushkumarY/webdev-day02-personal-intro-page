# Day 2: HTML Foundations — Personal Introduction

This example is a small personal introduction page that can grow into a resume-style page. Open `index.html` in a browser and read the source alongside the page.

## Learning goals

By the end of this practice, you should be able to:

- Explain the purpose of `<!doctype html>`, `<html>`, `<head>`, `<title>`, and `<body>`.
- Use headings, paragraphs, line breaks, and emphasis to structure text.
- Group related content in `div` elements and identify groups with `id` and `class`.
- Recognize semantic containers such as `header`, `main`, `section`, and `footer`.
- Inspect and fix a simple HTML mistake using browser DevTools.
- Save, format, and submit a small project with Git.

## Project tour

- `index.html` is the working reference page. The name, course, education details, skills, and interests are fictional examples. Replace them with your own details when you make your version.
- The document starts with the HTML doctype, language, character encoding, responsive viewport, and page title.
- The page uses headings and paragraphs for readable content, `strong` for emphasis, and nested `div` elements to group related education facts.
- Semantic elements show the role of each page area. The `id` values identify sections, while `data-section` demonstrates a custom data attribute.
- `style.css` contains the page design, linked from `index.html`. Its numbered comments group the rules into page defaults, the introduction banner, content cards, and mobile layout. Try changing a color or spacing value and refresh the page to see the result.

## Build in class

Work through these steps in order. Save and refresh the page after each change.

| Step | What to do | Suggested commit message |
|---|---|---|
| 1 | Create `index.html` with a doctype, `html`, `head`, page title, `body`, and a few headings. | `feat: add basic html structure` |
| 2 | Add paragraphs, `br`, `hr`, `strong`, and `em`. Build About, Education, and Skills sections. | `feat: add intro content` |
| 3 | Group the sections with `div` elements. Add meaningful `id` and `class` values, plus one `data-*` attribute. | `refactor: group content in divs` |
| 4 | Copy the page to `broken.html`. Introduce one small HTML error, find it with DevTools, then fix it. Keep the corrected version. | `fix: debug broken html` |
| 5 | Format the file, tidy the folder, update this README for your own project, and push your repository. | `docs: add readme` |

After practising with `div`, try using semantic elements such as `header`, `main`, `section`, and `footer` where their meaning fits. The working reference already shows one semantic version.

## Assignment — create your own similar project

Use this page as a **reference for structure and learning**, then create your own personal introduction page. Do not submit a renamed copy: write your own content and make your own choices about the sections and presentation.

1. Create a new GitHub repository with this exact name pattern:

   `rollno-firstname-webdev-day01-setup-practice`

   Replace `rollno` with your roll number and `firstname` with your first name, in lowercase. For example: `23-anaya-webdev-day01-setup-practice`.
2. Create an `index.html` containing a valid HTML document structure and a clear page title.
3. Include a personal introduction and at least three useful sections, such as About, Education, Skills, Goals, or Interests.
4. Use headings and paragraphs appropriately. Include examples of `strong` or `em`, and use semantic containers such as `header`, `main`, `section`, and `footer`.
5. Add at least one section `id`, one `class`, and one `data-*` attribute. Make sure each has a sensible purpose.
6. Open the page in a browser, check that it is readable, and correct any HTML mistakes.
7. Add a `README.md` that explains what your project is and how to open it. Include a screenshot of your finished page in the README itself. Add the screenshot image to your repository (for example, in a `screenshots/` folder), then embed it with Markdown, such as:

   ```markdown
   ![Screenshot of my personal introduction page](screenshots/personal-intro.png)
   ```
8. Commit your work with clear messages and push it to GitHub.

### Submit

- [ ] Personal introduction page with a title and clear headings
- [ ] Resume-style content using text elements and semantic containers
- [ ] Valid, working HTML page
- [ ] README with a short project description and opening instructions
- [ ] GitHub repository link using the required repository name pattern
- [ ] Screenshot image added to the repository and displayed inside the README

**Submit your repository link and screenshot to your instructor.** Do not include private information such as your phone number or home address.

## Run the example

No installation is needed. Open `index.html` in any modern web browser. To edit it, use a code editor such as VS Code.

