# Edin Durak - Frontend Developer CV

Welcome to my CV repository! This project highlights my skills and experience as a frontend developer. The CV is built using **HTML**, **CSS**, and **vanilla JavaScript**, featuring both **English** and **Bosnian** versions. The layout is responsive and print-ready for **A4 format (794px)**.

## Features
- **Two Language Versions**: You can switch between **English (default)** and **Bosnian** using the links provided at the top of the page. These links are hidden in the print layout to ensure a clean output.
- **A4 Print-Ready Layout**: The layout has been optimized for printing in **A4 format (794px width)**. Media queries adjust the layout for a perfect printout, with unnecessary elements hidden.
- **Responsive Design**: The design adapts seamlessly to desktop and mobile devices. For printing, the layout shifts to A4 dimensions with proper margins and formatting.

## View the CV
To view the CV in your preferred language, use the following links:
- [English Version](./index.html)
- [Bosnian Version](./bosnian-version.html)

## Download the PDF
To download the CV as a PDF:
1. Open either the **English** or **Bosnian** version using the links above.
2. Use your browser's **Print** function and select **Save as PDF**.
3. For Bosnian, select the Bosnian version before printing.

The language selection links are automatically hidden when printing, ensuring a clean, professional printout.

---

## How the CV Was Built

### Layout Modification for A4 Printing (794px)
The CV is optimized for A4 printing using the following CSS techniques:
- **Media Queries for Print**: Specific media queries adjust the layout when printing. The layout is constrained to a maximum width of **794px**, ensuring it fits perfectly on an A4 page.
  
  ```css
  @media print {
    body {
      width: 794px;
      margin: 0 auto;
    }

    .language-selector {
      display: none;
    }

    .no-print {
      display: none;
    }
  }
  ```

- **Page Breaks**: Used CSS properties to control page breaks, ensuring content does not split awkwardly across pages when printed.

  ```css
  @media print {
    .section {
      page-break-inside: avoid;
    }
  }
  ```

- **Font Sizes and Margins**: Optimized typography and margins for print readability.

---

### Project Details
- **HTML5 and CSS3**: The CV structure is built with semantic HTML5 and styled using CSS3. No JavaScript frameworks were used, keeping it lightweight and simple.
- **Mobile-First Approach**: The CV was designed with a mobile-first approach and adapts smoothly to different screen sizes.
- **Google Fonts and FontAwesome**: The CV uses the `Open Sans` font from Google Fonts for a clean, professional look, and icons from FontAwesome for visual enhancement.
- **Follows Best Coding Practices**: The project follows a clean, maintainable structure with comments and separation of concerns.

### How the Language Switch Works
- The project contains two separate HTML files:
  - `index.html` (for English).
  - `bosnian-version.html` (for Bosnian).
- Both versions share the same design and structure but contain text in different languages.
- The user can toggle between the two language versions via the links at the top, which are hidden when printing to avoid clutter.

### Steps to Download PDF Version
To download a PDF of the CV:
1. **Open** the respective HTML file (either English or Bosnian).
2. **Use** the browser's **Print** function and select **Save as PDF**.
3. **Ensure** the print layout is optimized by previewing before saving. The language selection links will be automatically hidden.

---

## GitHub Project Layout
Here’s an overview of the repository's structure:

```
├── index.html            # English version of the CV
├── bosnian-version.html  # Bosnian version of the CV
├── styles.css            # CSS file containing styles for both versions
├── README.md             # This file, explaining the project and usage
├── images/               # Folder containing any images used in the CV
```

### Key Files:
- `index.html`: The default English version of the CV.
- `index-bs.html`: The Bosnian version of the CV.
- `styles.css`: Shared stylesheet for both CVs, handling layout and responsive behavior.
- `README.md`: This file, explaining the project's purpose and how to use it.

---

## License
This project is open-source and available under the [MIT License](./LICENSE).

Feel free to use this as a template or inspiration for your own CV!

---

### Step-by-Step Development Process
1. **Created two HTML files**: `index.html` (English) and `bosnian-version.html` (Bosnian) to handle both language versions.
2. **Responsive design**: Developed the layout to adapt to different screen sizes using media queries and flexible units.
3. **Print optimization**: Used media queries to adjust the layout for A4 printing, hiding unnecessary elements like language selectors.
4. **File Upload to GitHub**: Uploaded all the necessary files to this repository, adhering to best practices for project structure and documentation.
5. **Added detailed documentation**: Explained the entire process in this `README.md` file, providing clear instructions for viewing, downloading, and understanding the code.

---

Thank you for visiting my CV repository. If you have any feedback or questions, feel free to open an issue or get in touch!



