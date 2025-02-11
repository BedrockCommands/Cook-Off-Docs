# Contributing to Documentation

This guide will help you set up everything needed to edit our documentation, even if you've never coded before!

## Setup Steps (One-time only)

### Install Python
   1. Go to [Python's download page](https://www.python.org/downloads/)
   2. Click "Download Python" (get the latest version)
   3. Run the installer
   4. **Important**: Check "Add Python to PATH" during installation

### Install Material for MkDocs
   1. Open Command Prompt (press Windows key, type "cmd", press Enter)
   2. Copy and paste this command:
```bash
pip install mkdocs-material
```
## Editing the Documentation

### Download the project
   1. Go to our [GitHub page](https://github.com/BedrockCommands/Cook-Off)
   2. Click the green "Code" button
   3. Click "Download ZIP"
   4. Extract the ZIP file somewhere on your computer
   5. **Advanced**: If you actually want to make a pull request you will have to fork the repository and do these changes in your [fork](https://docs.github.com/de/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository)

<!-- Please Ignore the mess below it didn't want to order the numbers correctly -->
### Preview the project
   1. Open Command Prompt
   2. Navigate to where you extracted the files:
```bash
cd path/to/cook-off/docs
```
3\. Start the preview server:
```bash
mkdocs serve
```
4\. Open your web browser and go to: [http://127.0.0.1:8000](http://127.0.0.1:8000)

### Edit the documentation
   - All documentation files are in the `docs` folder
   - Files end with `.md`
   - Open them with any text editor
   - Every time you save, the website will update automatically!

## Submit Your Changes

### Using GitHub (Advanced)
If you made a fork, push the changes to the fork. You can now make a [pull request](https://docs.github.com/de/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

### Using Discord (Beginner)
If you don't have a github account or don't want to go through the troubles, you can also contribute by sending the files on discord! Make sure to write a small description of what you changed

## Need Help?

If you get stuck, reach out on our [Discord server](https://discord.gg/SYstTYx5G5)!

## Writing Tips

### Documents use Markdown formatting:
- `# Heading`
- `## Subheading`
- `- Bullet point`
- `1. Numbered list`
- `**Bold text**`
- `*Italic text*`

A quick [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) might help!