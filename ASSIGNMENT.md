# 📄 Inline Styling

Style a page about **Apollo**, a social-media-famous British Shorthair cat, using inline CSS,
then paste your code into a Canvas discussion reply where it renders as styled content.

## 🎯 Overview

In this coding exercise, you'll keep building your CSS skills with **inline styles**: CSS
applied directly to a single HTML element with the `style` attribute.

So far, you've used HTML for structure and separate CSS files for styling. That is still the
standard, preferred way to build a website when you control the files. External CSS keeps
your code cleaner, more organized, and much easier to update. Inline styles are usually not
the right choice for a whole site built from scratch.

Inline CSS is still worth learning, though. Many sites are built with a **CMS** (Content
Management System), which lets people create and update content without editing the site's
code. Canvas is one example and WordPress is another. In these tools you often work inside a
text editor, discussion board, or content block where you can write HTML but can't touch the
site's CSS files. Inline CSS lets you style your content right inside the HTML you write.

You'll start by adding inline styles in VS Code so you can see how they work. Then you'll
copy your code into a Canvas discussion reply, where your HTML renders as styled content.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the discussion page. They
> walk you through every step, so watch them there instead of working from this file alone.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Add CSS to individual elements with the `style` attribute
- Write several CSS declarations in one `style` attribute, separated by semicolons
- Style text, lists, sections, quotes, and images with inline CSS
- Use the code view in a CMS (Canvas) to paste and edit HTML
- Explain when inline CSS is useful and why external CSS is usually the better choice

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this exercise's discussion page in **Canvas**, not in this
repo. Watch them **in order** and follow along. Pause whenever you need time to finish a
step. It's normal to pause, rewind, and rewatch parts of a coding demonstration.

| Video | What you will do |
| --- | --- |
| **Inline CSS 01 — Coding** | Open the starter file in VS Code and add inline styles to the HTML elements. You'll style the `<blockquote>` and `<cite>` on your own afterward. |
| **Inline CSS 02 — Canvas** | Copy your code into a Canvas discussion reply using the **</>** code view, upload an image of Apollo, and style the image. |

Need a refresher on how inline CSS works? Rewatch the
[Inline CSS introduction lecture](https://ucba.mediaspace.kaltura.com/media/Lecture+-+Inline+CSS/1_co75nsjy).

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> CSS, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files:** don't download the ZIP. Create your own repo from this
>   template and open it with GitHub Desktop, as described in the
>   [README](README.md#-getting-started).
> - **Publishing:** your styled `index.html` also has to be live on GitHub Pages, with a
>   pull request, as described in the [README](README.md#-publishing-to-github-pages).
> - **Submitting:** you still post your reply in the Canvas discussion. Add your pull
>   request URL to the bottom of that reply, as described in the
>   [README](README.md#-submitting-the-assignment).

## 🛠️ Steps

### Part 1 — Add Inline Styles in VS Code

1. Open the repo **folder** in VS Code.
2. Follow along with **Inline CSS 01 — Coding** to add inline styles to the HTML elements in
   `index.html`.
3. Style the `<blockquote>` and `<cite>` **on your own**. Experiment with size, font, color,
   alignment, spacing, or anything else that makes the quote look good.
4. Replace the `<!-- Add an image of Apollo here -->` comment with an `<img>` of Apollo.
   Use one of the starter images (`apollo_01.png` – `apollo_04.png`), give it useful `alt`
   text, and style it with a `style` attribute.
5. Commit, push, and publish to GitHub Pages.

> [!NOTE]
> Use only `style` attributes. Don't add a `<style>` block or a linked CSS file. Canvas
> won't let you use either one, and that's the point of this exercise.

### Part 2 — Transfer to Canvas and Add an Image

1. In VS Code, press <kbd>Ctrl</kbd> + <kbd>A</kbd> (Windows) or <kbd>Cmd</kbd> +
   <kbd>A</kbd> (Mac) to select all of your code, then <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> +
   <kbd>C</kbd> to copy it.
2. Go to the **CE14: Inline Styling** discussion in Canvas and click the red **Reply**
   button.
3. Click the **</>** code view button in the lower-right corner of the editor.
4. Paste your HTML into the code view.
5. Upload an image of Apollo to your post. Canvas can't see the image files on your
   computer, so `src="apollo_01.png"` won't work there. Use Canvas's image upload instead.
6. Go back into the code view and style the image.

### Part 3 — Post & Review

1. Add your pull request URL to the bottom of your reply (see the
   [README](README.md#-submitting-the-assignment)).
2. Post your reply, then review it to make sure everything looks correct.
3. If something looks wrong, click **Edit**, go back to the **</>** code view, and fix it.

## 📂 Starter Files

| File | Purpose |
| --- | --- |
| `index.html` | The Apollo content. Add your inline styles here. |
| `apollo_01.png` – `apollo_04.png` | Photos of Apollo. Use one or more on your GitHub Pages site. |

## 🧮 Grading

| Criteria | Points |
| --- | --- |
| Inline styles from the video are applied to the page's elements (heading, paragraphs, link, section, list) using `style` attributes | 3 |
| The `<blockquote>` and `<cite>` are styled on your own with several CSS declarations | 2 |
| An image of Apollo is added with useful `alt` text and styled with inline CSS | 2 |
| The styled reply is posted in the Canvas discussion and renders correctly | 2 |
| The page is live on GitHub Pages and the pull request URL is in your Canvas reply | 1 |
| **Total** | **10** |

## ✅ Before You Submit

- [ ] Every style is written in a `style` attribute — no `<style>` block or linked CSS file
- [ ] Each `style` attribute has its declarations separated by semicolons
- [ ] The `<blockquote>` and `<cite>` are styled
- [ ] `index.html` has an image of Apollo with useful `alt` text and inline styles
- [ ] The page is live on GitHub Pages and the URL is in your pull request
- [ ] Your styled reply is posted in the Canvas discussion, with an uploaded, styled image
- [ ] Your pull request URL is at the bottom of your Canvas reply

## 🛠️ Troubleshooting

- **A style isn't showing up:** check for a missing semicolon between declarations, a
  missing colon between property and value, or a missing closing quote on the `style`
  attribute.
- **A style disappears after posting in Canvas:** Canvas removes some CSS properties for
  security. Try a different property to get a similar look.
- **The image is broken in Canvas:** Canvas can't load `apollo_01.png` from your computer.
  Upload the image through the Canvas editor.
- **The image is broken on GitHub Pages:** make sure the file name in `src` matches exactly,
  including `.png`, and that the image is in the root folder with `index.html`.

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [Inline CSS introduction lecture](https://ucba.mediaspace.kaltura.com/media/Lecture+-+Inline+CSS/1_co75nsjy)
- [MDN — The `style` attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Global_attributes/style)
- [MDN — CSS syntax](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/What_is_CSS)
- [MDN — `<blockquote>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/blockquote)
- [Canvas — How do I use the HTML view in the Rich Content Editor?](https://community.canvaslms.com/t5/Canvas-Basics-Guide/How-do-I-use-the-HTML-view-in-the-Rich-Content-Editor/ta-p/612)

---

The AI policy and submission instructions are in the [README](README.md).
