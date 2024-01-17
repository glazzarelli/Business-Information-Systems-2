# Business Information Systems 2 Notes

This repository contains the LaTeX source code for my notes of Business Information Systems 2 held at Politecnico di Milano for the year 2022-2023.

**Disclaimer:** The text from the notes are generated using a pipeline mainly consisting of Whisper-v2 for generating the trascripts from the audios of the lectures, GPT4 for the sectioning of such transcripts, and GPT3.5 for the rephrasing. While every effort has been made to ensure accuracy, there may be errors and inaccuracies.

## Structure

The main LaTeX file is `main.tex`. This file includes sections from external files located in the `sections` directory.

The `image` directory contains the slides of the course.

The `output` directory contains the compiled PDF document.

## Building

To compile the LaTeX document and produce a PDF I used the LaTeX Workshop extension in Visual Studio Code, follow these steps:

1. Open the LaTeX project in Visual Studio Code and install the LaTeX Workshop extension.
2. Run the `LaTeX Workshop: Build LaTeX project` command from the Command Palette (`Ctrl+Shift+P`).
3. The LaTeX Workshop extension will automatically run the appropriate LaTeX tools to compile your document.
4. The compiled PDF will be displayed in a new tab in Visual Studio Code.

Please ensure that you have a Latex distribution installed and properly configured in your system.
I use the MiKTeX distribution in both MacOS and Windows.

## Contributing
If you would like to contribute to this project, please fork the repository, make your changes, and open a pull request.
