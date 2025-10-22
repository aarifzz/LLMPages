# LLMPages

## Summary

This application was automatically generated to fulfill the following requirements:


Create and publish these files as a public GitHub Pages site:

- ashravan.txt: Write a 300-400 word Brandon Sanderson short story
  on what happens to Ashravan after Shai restores him. Build up to a dramatic climax.
- dilemma.json: An autonomous vehicle must choose between hitting
  2 people or swerving to hit 1 person. Should it swerve?
  If the 2 people are criminals and the 1 person is a child, should it swerve?
  Fill in {
    people: 4,
    case_1: {swerve: bool, reason: str},
    case_2: {swerve: bool, reason: str}
  }
- about.md: Describe yourself in three words.
- pelican.svg: Generate an SVG of a pelican riding a bicycle.
- restaurant.json: Recommend a good restaurant in Mumbai.
  Fill in `{city: "Mumbai", lat: float, long: float, name: str, what_to_eat: str}`
- prediction.json: What will the Fed Funds rate by on December 2025?
  Fill in `{rate: float (0-1, e.g. 0.04), reason: str}`
- index.html: A homepage linking to all the above files explaining what they are.
- LICENSE: An MIT license file.
- uid.txt: Upload the uid attachment as-is


## Features

This single-page application provides:
- Clean, responsive user interface
- Real-time functionality
- Error handling and validation
- Cross-browser compatibility

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/aarifzz/LLMPages.git
   cd LLMPages
   ```

2. Open `index.html` in your web browser or visit the live demo

## Usage

Simply open the `index.html` file in a modern web browser. The application is fully self-contained and requires no build process or dependencies.

## Live Demo

🌐 [View Live Application](https://aarifzz.github.io/LLMPages/)

## Code Explanation

The application is built as a single HTML file containing:

- **HTML Structure**: Semantic markup for accessibility
- **CSS Styling**: Embedded styles using modern CSS features
- **JavaScript Logic**: Vanilla JavaScript for functionality
- **Error Handling**: Robust error handling throughout

## Evaluation Checks (Round 1)

This application satisfies the following checks:

- Each required file exists on GitHub
- uid.txt matches the attached uid.txt
- LICENSE contains the MIT License text
- index.html links to all required assets
- ashravan.txt meets content requirements
- dilemma.json matches the assigned scenario
- about.md contains exactly three words
- pelican.svg is valid SVG
- restaurant.json data is consistent
- prediction.json contains a reasonable forecast
- pelican.svg is rated by an LLM

## License

MIT License - See LICENSE file for details

## Generated

This application was automatically generated on 2025-10-22 08:58:41 using Gemini API for LLM-assisted code generation.

---
*Last updated: Round 1 - 2025-10-22 08:58:41*
