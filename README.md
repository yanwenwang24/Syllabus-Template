# Syllabus Template

A LaTeX template designed for course syllabi.

## File Structure

- [`syllabus.tex`](./syllabus.tex): The main entry point. Compile this file to generate the PDF.
- [`syllabus_style.sty`](./syllabus_style.sty): Contains all style definitions, packages, and custom commands.
- [`sections/`](./sections/): Directory containing individual `.tex` files for each section of the syllabus (e.g., Course Info, Policies, Schedule).
- [`assets/`](./assets/): Directory for images, such as the university logo.

## Usage

1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MacTeX, MiKTeX).

2. **Editing**:

    - Replace [`assets/logo.png`](./assets/logo.png) with your institution's logo.
    - Modify colors and layout in [`syllabus_style.sty`](./syllabus_style.sty).
    - Update course details in [`syllabus.tex`](./syllabus.tex) (e.g., `\coursename`, `\semester`).
    - Edit specific sections in the [`sections/`](./sections/) folder.

3. **Compilation**: Open [`syllabus.tex`](./syllabus.tex) in your LaTeX editor and compile using `pdflatex` or `xelatex`.

    ```bash
    pdflatex syllabus.tex
    ```
