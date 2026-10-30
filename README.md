# MERN Development — Practical Lab Record

**Student:** Hemant Rathore  
**Roll No:** 2410303204  
**Course:** MERN Development

This repository contains the complete practical work arranged in the required
sequence from **LAB 01** to **LAB 15**. The exercises begin with Git and
terminal practice, then progress through HTML, forms, tables, CSS, Flexbox,
Grid, and responsive design.

## Contents

- [How to preview the HTML files](#how-to-preview-the-html-files)
- [Lab sequence](#lab-sequence)
- [Repository structure](#repository-structure)
- [Student details](#student-details)

## How to preview the HTML files

GitHub displays HTML files as source code for safety; it does not execute them
inside the repository page. Use one of these methods to view a practical in a
browser:

### Option 1: Python local server

Run the following commands from the repository root:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000), select a lab folder, and
open any `.html` file. For example:

```text
http://localhost:8000/LAB%2005/portfolio.html
```

### Option 2: VS Code Live Server

1. Open this repository in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click an HTML file and select **Open with Live Server**.
4. Use the browser preview to test links, forms, images, and responsive layouts.

The HTML files can also be opened directly in a browser, but a local server is
recommended because it handles relative links and images more reliably.

## Lab sequence

### LAB 01 — Git and local project setup

**Objective:** Create a small HTML project, initialize Git, configure local
identity, track files, and record commits.

**Practical work:**

- Create an `html-lab` directory.
- Initialize a repository with `git init -b main`.
- Configure local Git username and email.
- Create `index.html` from the terminal.
- Use `git status`, `git add`, `git commit`, and `git log --oneline`.

**File:** [`LAB 01/terminal-output.txt`](LAB%2001/terminal-output.txt)

**Concepts:** Git initialization, working tree, staging area, commits,
branches, local configuration, and commit history.

### LAB 02 — Git remote and cloning

**Objective:** Practice creating a bare remote repository, connecting it to a
local project, pushing a branch, cloning the remote, and checking history.

**Practical work:**

- Create a bare repository with `git init --bare -b main`.
- Add a remote with `git remote add origin`.
- Push the `main` branch.
- Clone the remote into a second directory.
- Verify the commit history with `git log --oneline`.

**File:** [`LAB 02/terminal-output.txt`](LAB%2002/terminal-output.txt)

**Concepts:** Bare repositories, remotes, push, clone, branch tracking, and
distributed version control.

### LAB 03 — HTML document and text elements

**Objective:** Build basic HTML documents and use headings and common text
formatting elements.

**Practicals:**

| File | Practical details |
|---|---|
| [`first.html`](LAB%2003/first.html) | Create a first HTML page with document structure and a personal greeting. |
| [`headings.html`](LAB%2003/headings.html) | Demonstrate heading levels from `h1` through `h6`. |
| [`text-format.html`](LAB%2003/text-format.html) | Practice paragraph text and inline formatting elements such as bold, italic, underline, and emphasis. |

**Concepts:** `doctype`, `html`, `head`, `body`, headings, paragraphs, semantic
text, and inline elements.

### LAB 04 — Attributes, layout, and attendance

**Objective:** Use HTML attributes and organize content into simple page
layouts while presenting attendance information.

**Practicals:**

| File | Practical details |
|---|---|
| [`attributes.html`](LAB%2004/attributes.html) | Use attributes such as `id`, `class`, `title`, and link-related attributes. |
| [`layout.html`](LAB%2004/layout.html) | Arrange page content using structural HTML sections. |
| [`attendance-fixed.html`](LAB%2004/attendance-fixed.html) | Present attendance values in a clear, readable layout. |

**Concepts:** HTML attributes, semantic sections, reusable classes, document
structure, and readable content organization.

### LAB 05 — Home page, portfolio, and images

**Objective:** Create introductory and portfolio pages and embed a local image
asset.

**Practicals:**

| File | Practical details |
|---|---|
| [`home.html`](LAB%2005/home.html) | Build a simple home page with introductory content and navigation. |
| [`portfolio.html`](LAB%2005/portfolio.html) | Create a portfolio page showing profile and project information. |
| [`portfolio-image.html`](LAB%2005/portfolio-image.html) | Add and display an image in a portfolio page. |
| [`images/photo.jpg`](LAB%2005/images/photo.jpg) | Local image asset used by the image practical. |

**Preview note:** Run the local server from the repository root so the image
relative path resolves correctly.

**Concepts:** Links, images, `alt` text, relative paths, page navigation, and
basic portfolio structure.

### LAB 06 — Semantic content pages

**Objective:** Build practical information pages using lists, questions and
answers, and menu-style content.

**Practicals:**

| File | Practical details |
|---|---|
| [`canteen-menu.html`](LAB%2006/canteen-menu.html) | Present food items and prices as a canteen menu. |
| [`faq.html`](LAB%2006/faq.html) | Create frequently asked questions and their answers. |
| [`shopping-list.html`](LAB%2006/shopping-list.html) | Build an organized shopping list using list elements. |

**Concepts:** Ordered and unordered lists, semantic grouping, headings,
question-and-answer content, and accessible page structure.

### LAB 07 — Personal profile pages

**Objective:** Create an about-me page with profile information, links, and
contact details.

**Practicals:**

| File | Practical details |
|---|---|
| [`about-me-task1.html`](LAB%2007/about-me-task1.html) | Create a basic personal introduction page. |
| [`about-me-task2.html`](LAB%2007/about-me-task2.html) | Extend the profile page with structured personal content. |
| [`about-me.html`](LAB%2007/about-me.html) | Build a complete profile page with an email contact link. |

**Concepts:** Personal information layout, headings, paragraphs, hyperlinks,
`mailto` links, and semantic HTML.

### LAB 08 — Forms and validation

**Objective:** Create interactive forms for selecting choices and signing up,
including required-field validation.

**Practicals:**

| File | Practical details |
|---|---|
| [`choices.html`](LAB%2008/choices.html) | Practice radio buttons, checkboxes, and selectable options. |
| [`signup.html`](LAB%2008/signup.html) | Build a signup form with common input types. |
| [`signup-required.html`](LAB%2008/signup-required.html) | Add `required` validation to prevent incomplete submission. |

**Concepts:** `form`, `label`, `input`, `select`, `textarea`, radio buttons,
checkboxes, submit controls, and browser validation.

**Preview note:** Open the pages in a browser and submit empty fields to see
the built-in validation behavior.

### LAB 09 — Marks tables and accessibility

**Objective:** Display student marks in tables and compare standard, average,
and accessible table implementations.

**Practicals:**

| File | Practical details |
|---|---|
| [`marks.html`](LAB%2009/marks.html) | Create a basic marks table with student data. |
| [`marks-average.html`](LAB%2009/marks-average.html) | Add average marks to the tabular presentation. |
| [`marks-accessible.html`](LAB%2009/marks-accessible.html) | Improve table semantics using accessible row and header markup. |

**Concepts:** `table`, `caption`, `thead`, `tbody`, `tr`, `th`, `td`, scope
attributes, tabular data, and accessibility.

### LAB 10 — CSS inclusion methods

**Objective:** Apply styles using inline CSS, internal CSS, and an external
stylesheet.

**Practicals:**

| File | Practical details |
|---|---|
| [`inline-internal.html`](LAB%2010/inline-internal.html) | Compare inline styles with a page-level `<style>` block. |
| [`linked.html`](LAB%2010/linked.html) | Connect an HTML page to an external stylesheet. |
| [`style.css`](LAB%2010/style.css) | Store reusable styles outside the HTML document. |

**Concepts:** CSS cascade, selectors, declarations, inline styles, internal
stylesheets, external stylesheets, and separation of concerns.

### LAB 11 — CSS variables, tokens, and units

**Objective:** Create reusable design values and understand common CSS units.

**Practicals:**

| File | Practical details |
|---|---|
| [`tokens-demo.html`](LAB%2011/tokens-demo.html) | Demonstrate reusable design tokens in a page. |
| [`tokens.css`](LAB%2011/tokens.css) | Define shared CSS custom properties for colors and spacing. |
| [`variables.html`](LAB%2011/variables.html) | Use CSS variables to keep styling consistent. |
| [`units.html`](LAB%2011/units.html) | Compare fixed and relative units such as `px`, `%`, `em`, `rem`, `vh`, and `vw`. |

**Concepts:** Custom properties, `var()`, design tokens, inheritance, fixed
units, relative units, and maintainable CSS.

### LAB 12 — Box model, cards, and scrolling

**Objective:** Practice the CSS box model and create card and scrollable
layouts.

**Practicals:**

| File | Practical details |
|---|---|
| [`box-model.html`](LAB%2012/box-model.html) | Demonstrate content, padding, border, and margin. |
| [`card.html`](LAB%2012/card.html) | Build a reusable card component with spacing and visual styling. |
| [`scroll.html`](LAB%2012/scroll.html) | Create a constrained area with overflow and scrolling behavior. |

**Concepts:** `box-sizing`, width and height, margin, padding, border,
overflow, component spacing, and visual hierarchy.

### LAB 13 — Flexbox layouts

**Objective:** Use Flexbox to align, centre, navigate, and wrap groups of
content cards.

**Practicals:**

| File | Practical details |
|---|---|
| [`centred-cards.html`](LAB%2013/centred-cards.html) | Centre cards horizontally and vertically with Flexbox. |
| [`nav-flex.html`](LAB%2013/nav-flex.html) | Build a navigation layout using flex direction, alignment, and spacing. |
| [`wrapping-cards.html`](LAB%2013/wrapping-cards.html) | Allow cards to wrap across rows when the viewport becomes narrow. |

**Concepts:** Flex containers, main axis, cross axis, `justify-content`,
`align-items`, `gap`, `flex-wrap`, and responsive alignment.

### LAB 14 — CSS Grid layouts

**Objective:** Build two-dimensional layouts for dashboards and image
galleries using CSS Grid.

**Practicals:**

| File | Practical details |
|---|---|
| [`grid-first.html`](LAB%2014/grid-first.html) | Create a first grid with rows, columns, and gaps. |
| [`dashboard-areas.html`](LAB%2014/dashboard-areas.html) | Define named grid areas for a dashboard-style layout. |
| [`gallery.html`](LAB%2014/gallery.html) | Arrange gallery items into a responsive grid. |

**Concepts:** Grid tracks, columns, rows, `gap`, `grid-template-areas`,
responsive placement, and two-dimensional layout.

### LAB 15 — Responsive and mobile-first design

**Objective:** Build pages that adapt to different screen sizes and use
responsive images and typography.

**Practicals:**

| File | Practical details |
|---|---|
| [`mobile-first.html`](LAB%2015/mobile-first.html) | Start with a small-screen layout and enhance it with media queries. |
| [`responsive-image.html`](LAB%2015/responsive-image.html) | Size an image so it adapts to its containing element. |
| [`responsive-text.html`](LAB%2015/responsive-text.html) | Adjust text sizes and layout for different viewport widths. |
| [`images/photo.jpg`](LAB%2015/images/photo.jpg) | Local image asset used by the responsive-image practical. |

**Concepts:** Mobile-first CSS, media queries, flexible widths, `max-width`,
responsive images, viewport behavior, and responsive typography.

## Repository structure

```text
LAB 01/  Git and local project setup
LAB 02/  Git remote and cloning
LAB 03/  HTML document and text elements
LAB 04/  Attributes, layout, and attendance
LAB 05/  Home page, portfolio, and images
LAB 06/  Semantic content pages
LAB 07/  Personal profile pages
LAB 08/  Forms and validation
LAB 09/  Marks tables and accessibility
LAB 10/  CSS inclusion methods
LAB 11/  CSS variables, tokens, and units
LAB 12/  Box model, cards, and scrolling
LAB 13/  Flexbox layouts
LAB 14/  CSS Grid layouts
LAB 15/  Responsive and mobile-first design
```

## Student details

All practicals use the following identity wherever a name and roll number are
required:

```text
Name: Hemant Rathore
Roll No: 2410303204
```

## License

This project is available under the [MIT License](LICENSE).
