# LaTeX Resume Template

This is a simple, clean, one-page LaTeX resume template based on the structure used by Wassim Benaissa, originally inspired by Awesome-CV and sb2nov's resume.

It uses the Helvetica font and is designed for a professional look with minimal clutter.

## Features

*   Clean, single-column layout
*   Minimal spacing for maximum content
*   Uses Helvetica font
*   Easy-to-customize sections (Experience, Education, Skills, etc.)
*   FontAwesome icons for contact information

## How to Use

1.  **Clone or download** this repository/directory.
2.  **Edit `template.tex`**: Open the `template.tex` file in your favorite LaTeX editor.
3.  **Fill in your information**: Replace all the placeholder text (like `[Your Name]`, `[Job Title]`, `[Company Name]`, `% Comments indicating where to add content`, etc.) with your actual details.
    *   Follow the comments within the file for guidance on what to put in each section.
    *   Use the `\\entry` command for Experience, Projects, and Education items.
    *   Use `itemize` environments for bullet points under each entry.
4.  **Compile the LaTeX file**: Use a LaTeX compiler (like `pdflatex`, included in distributions like TeX Live, MiKTeX, or MacTeX) to generate the PDF:
    ```bash
    pdflatex template.tex
    ```
    You might need to run it twice to ensure cross-references (like page numbers, if any) are correct.
5.  **Customize (Optional)**:
    *   Change the accent color in the `\\definecolor{accent}` line.
    *   Modify section titles or add/remove sections as needed.
    *   If you prefer a different font, uncomment one of the other font packages (like `lato` or `sourcesanspro`) and comment out `\\usepackage{helvet}`.

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
