# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Development
It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## How to run the site
Select the index.html file within VSCode
Press ctrl+shift+p or cmd+shift+p to open the command palette
Run the command 'Live Preview: Start Server' to start the server
The website is viewable locally via the link http://127.0.0.1:3000/

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers
Can you do a test of the current color contrast (text/background), report the results of the test, and then fix it by changing the assigned colors?
- Black on green is not very easy to read. Fixed by changing the background color to white. 

The content is still not very accessible — report on what happens when you try to navigate it using a keyboard.
- All interactive elements are highlightable by pressing tab and selectable by pressing enter, except for the 'Show Comments' button. This was fixed by changing the tag of the element from div to button.

Can you update the article text to make it easier for screen reader users to navigate?
- All text present in 'font' tags were changed to use h1/2/3 tags. Labels were added to pair with text inputs. Untagged lines of text were added to p tags.

The navigation menu part of the site could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.
- Tag changed from div to nav.

The images are currently inaccessible to screen reader users. Can you fix this?
- Alt text added to each image.

The audio player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?
- Transcription of the audio file added.

The audio player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio?
- If the audio player fails to load, the user is given a link to download the mp3.

The input element in the search form at the top could do with a label, but we don't want to add a visible text label that would potentially spoil the design and isn't really needed by sighted users. How can you add a label that is only accessible to screen readers?
- A label was added which is invisible to typical users but screen readers will pick up.

The data table is not currently very accessible — it is hard for screen reader users to associate data rows and columns together, and the table also has no kind of summary to make it clear what it shows. Can you add some features to your HTML to fix this problem?
- Added a table summary and defined the top row as column headers.

Can you list two more ideas for improvements that would make the website more accessible?
- Made the navbar links look more like buttons.
- Added a return to top button in the bottom right of the screen which returns the user to the top of the page.