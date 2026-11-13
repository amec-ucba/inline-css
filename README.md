# 💻 Inline Styling

Starter files for the inline CSS coding exercise in Web Design 1. You will style a page about
**Apollo**, a social-media-famous British Shorthair cat, using only `style` attributes, publish it
with GitHub Pages, and then paste your code into a Canvas discussion reply.

This repo also includes the editor and Git configuration and the pull request template that every
assignment in this course uses.

> [!NOTE]
> `.editorconfig`, `.gitattributes`, `.gitignore`, `.noai`, and the `.github` and `.idea`
> folders are setup files that keep assignments consistent. Leave them alone. `index.html` and
> `apollo_01.png` – `apollo_04.png` are your starter content — keep them in the repo.

## 📋 Assignment Requirements

> [!IMPORTANT]
> **Start here: [read ASSIGNMENT.md →](.github/ASSIGNMENT.md)**

It has the overview, a guide to the companion videos in Canvas, the grading criteria, and a final checklist. Read it before you start, and check it again before you submit.

## ✅ At a Glance

Every assignment follows the same steps. Each guide has screenshots for every step.

| Step | What you do                                                                | Guide                                         |
|------|----------------------------------------------------------------------------|-----------------------------------------------|
| 0    | **First assignment only:** install and set up WebStorm                     | [WebStorm Setup](.github/WEBSTORM_SETUP.md)   |
| 1    | Create your repo from this template, clone it, and make a `develop` branch | [Getting Started](.github/GETTING_STARTED.md) |
| 2    | Build your page in the root folder                                         | [Where Your Files Go](#-where-your-files-go)  |
| 3    | Commit and push often, then turn on GitHub Pages                           | [Publishing](.github/PUBLISHING.md)           |
| 4    | Open a pull request into `main` and post its URL in the Canvas discussion  | [Submitting](.github/SUBMITTING.md)           |

## 📂 Where Your Files Go

Create your files in the **root folder** of this repo — the same folder as this README.
GitHub Pages publishes from the root, so `index.html` has to live there or your site will 404. Your files should look like this:

```
index.html
apollo_01.png
apollo_02.png
apollo_03.png
apollo_04.png
```

There is no `css/` folder in this exercise. Every style goes in a `style` attribute inside
`index.html`, because that's all Canvas allows when you paste your code into the discussion.

## 🤖 AI Policy

Work on this assignment must be your own. Do not use AI coding assistants — including
GitHub Copilot, Cursor, ChatGPT, Claude, or JetBrains AI Assistant — to generate,
complete, or rewrite your code.

You should be able to explain any line of your submission. You may be asked to do so.

This repo includes a `.noai` file, which disables JetBrains AI Assistant for the project
in IDEs like WebStorm. Leave it in place. It is a reminder of the policy above, not a
substitute for it — following the policy is still your responsibility.

> [!NOTE]
> The `.noai` file does **not** turn off WebStorm's local Full Line code completion. Turn that
> off yourself as part of the [one-time setup](.github/WEBSTORM_SETUP.md) (step 5).

> [!CAUTION]
> Late or missing submissions are graded on what is in the pull request at the deadline, so push your final commits
> before you submit.
