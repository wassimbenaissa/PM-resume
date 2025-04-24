# LaTeX Resume Template

This is a simple, clean, one-page LaTeX resume template based on the structure used by Wassim Benaissa, originally inspired by Awesome-CV and sb2nov's resume.

It uses the Helvetica font and is designed for a professional look with minimal clutter.

**Note:** The included `template.tex` file contains *example* content for a fictional Product Manager (Alex Chen) to illustrate how to fill out the template. You should replace all of this example information with your own.

## Features

*   Clean, single-column layout
*   Minimal spacing for maximum content
*   Uses Helvetica font
*   Easy-to-customize sections (Experience, Education, Skills, etc.)
*   FontAwesome icons for contact information
*   Includes example Product Manager content to get you started.

## How to Use

1.  **Clone or download** this repository/directory.
2.  **Edit `template.tex`**: Open the `template.tex` file in your favorite LaTeX editor.
3.  **Replace Example Information**: Replace all of Alex Chen's example details (name, contact info, experience, education, skills, etc.) with your own information.
    *   Pay attention to the structure used in the examples (e.g., using `\entry` for positions/degrees, `itemize` for bullet points, `\textbf` for skill categories).
    *   Adapt the sections and content to match your own background.
4.  **Compile the LaTeX file**: Use a LaTeX compiler (like `pdflatex`, included in distributions like TeX Live, MiKTeX, or MacTeX) to generate the PDF:
    ```bash
    pdflatex template.tex
    ```
    You might need to run it twice to ensure cross-references (like page numbers, if any) are correct.
5.  **Customize (Optional)**:
    *   Change the accent color in the `\definecolor{accent}` line.
    *   Modify section titles (`\section{...}`) or add/remove sections as needed.
    *   If you prefer a different font, uncomment one of the other font packages (like `lato` or `sourcesanspro`) and comment out `\usepackage{helvet}`.

## Dependencies

*   A LaTeX distribution (TeX Live, MiKTeX, MacTeX)
*   The following LaTeX packages (usually included in standard distributions):
    *   `geometry`
    *   `titlesec`
    *   `enumitem`
    *   `hyperref`
    *   `fontawesome5`
    *   `xcolor`
    *   `helvet` (or another font package)
    *   `microtype`

## License

This template is released under the MIT License. See the LICENSE file for details (or add one if desired). 
