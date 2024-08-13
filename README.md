# Tutorial Explorer Template

Use this template to create your own downloadable coding tutorials! Just download it as a ZIP and start editing. For the best experience, make sure your students have the [Tutorial Explorer extension from Simple Dev](https://marketplace.visualstudio.com/items?itemName=simpledev.tutorialexplorer) installed.

Feel free to edit this README too after you've read the rules below.

## Rules
- Use Markdown to write your lessons
- Put all of your lessons inside the `.tutorial` folder
- If you have a lot of lessons, you can use subfolders inside the `.tutorial` folder
- Put a number at the beginning of each lesson file name so that they stay in order (e.g. 1-prerequisites.md, 2-install.md, 3-setup.md, etc.)
- Uncomment the rules in `settings.json` before publishing
- Publish your tutorial to GitHub when you're done! Beginner students can download your tutorial as a ZIP and intermediate students can clone the repo

## settings.json
The settings.json file currently has 4 rules:

- Automatically opens Markdown files in the `.tutorial` folder in a Markdown Preview
- Prevents students from double clicking the Markdown Preview to get to the raw Markdown file
- Prevents the `.tutorial` folder from expanding in the normal Explorer when viewing the lesson files
- Sets the lesson files to readonly to prevent students from editing them

## Replit compatibility
If you would also like to be able to use your tutorial on Replit, DO NOT use subfolders inside the `.tutorial` folder. Replit can use the `.tutorial` folder as long as there aren't subfolders inside it.
