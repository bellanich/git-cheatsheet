# Git It Right: A Complete Cheatsheet

**by: Bella Nicholson**

Interested in getting to know Git better? This repository offers[ a concise guide][compiled-cheatsheet-pdf] to the essential Git commands and theory, empowering you for efficient and effective Git usage.

Whether you're a Git novice looking to grasp the basics or an experienced developer in need of a quick reference, this cheatsheet has you covered. It provides a handy overview of Git commands, their applications, and explanations of core Git concepts. With this cheatsheet, you'll be well-prepared for version control in your software projects. Customize it by forking or downloading the repo and edit it in LaTeX. Happy version controlling!


<a href="happy-octocat">
   <img src="./src/images/NUX_Octodex.gif" width="300" height="300">
</a>

Image source: [GitHub's Octodex][octocat-gif]


## Usage

You have two options for using  this cheatsheet: download it as PDF or compile it from the source code.

### Option 1: Download cheatsheet as a PDF

You can download the PDF version of the cheatsheet by clicking [here][compiled-cheatsheet-pdf]. Feel free to print it or keep it as a handy reference.


### Option 2: Compile from Source

If you prefer to customize the cheatsheet, you can compile the LaTeX source files yourself. Follow the steps outlined below.

   1. **Prerequisites.** If you wish to compile LaTeX locally, then ensure that you have **(a)** [LaTeX][weblink-latex-project] installed on your system and **(b)** an integrated writing environment for LaTeX like [TexStudio][weblink-download-texstudio]. Alternatively, you can compile via a web-based application like [Overleaf][weblink-overleaf-homepage].

   2. **Clone the Repository.** Clone this repository to your local machine using Git.

#### Source code structure

All the LaTeX source code is located within the `src` directory. Here is a high-level walkthrough of its structure:

- The [src/main.tex][source-code-main.tex] file generates the cheatsheet PDF. This means importing all the necessary LaTeX packages, cheatsheet documents, and predefined document styling.
- The [src/sections/][source-code-sections-dir] directory holds the topic-specific cheatsheet contents.
- The [src/images/][source-code-images-dir] directory contains all the figures used in this repo.
- The [src/styling/][source-code-styling-dir] directory contains page formatting definitions, color definitions, and custom (style-specific) commands definitions.



## Contributing

If you'd like to contribute to this project by adding new commands, improving the layout, or fixing errors, please follow these steps:

1. Fork the repository.
2. Make your changes.
3. Create a pull request with a clear description of your changes.

If you have any questions, feedback, or suggestions, please don't hesitate to open an issue or contact me via [LinkedIn](https://www.linkedin.com/in/bella-nicholson/).


## Acknowledgements

All sources used to formulate the cheatsheet contents are included as hyperlinks. Here are some additional sources that I would like to call attention to:

 - **Inspiration.** This cheatsheet was inspired by the course contents of the [Git Complete: The definitive, step-by-step guide to Git Udemy Course](https://www.udemy.com/course/git-complete/) by [Jason Taylor](https://www.linkedin.com/in/jasongtaylor/). I've gone into further details about selected topics and included broader version control concepts.
 -  **Original cheatsheet template.** The original LaTeX cheatsheet template can be found [here](https://www.overleaf.com/latex/examples/matplotlib-and-random-cheat-sheet/yttxrcxntbht).
 -  **Formatting.** I used [the Shades of Purple color palette](https://github.com/ahmadawais/shades-of-purple-vscode#sops-syntax-colors) to make this cheatsheet more visually appealing.

## License

This Git Cheatsheet is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as needed.


[compiled-cheatsheet-pdf]: https://github.com/bellanich/git-cheatsheet/blob/main/git_cheatsheet.pdf
[octocat-gif]: https://octodex.github.com/nuxtocat/
[weblink-latex-project]: https://www.latex-project.org/
[source-code-main.tex]: ./src/main.tex
[source-code-sections-dir]: ./src/sections
[source-code-images-dir]: src/images
[source-code-styling-dir]: ./src/styling
[weblink-download-texstudio]: https://www.texstudio.org
[weblink-overleaf-homepage]: https://www.overleaf.com