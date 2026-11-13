# Your Short Story Archive

A simple, permanent home for your short stories. It's free to host on GitHub Pages, and you own every word of it.

Each story is a plain text file. When you add one, the site rebuilds itself within about a minute.

---

## One-time setup (about 15 minutes)

### 1. Create a GitHub account
Go to **github.com** and sign up. Choose your username carefully, because it becomes part of your free web address: `yourusername.github.io`.

### 2. Create a repository
1. Click the **+** in the top-right corner, then **New repository**.
2. Name it exactly **`yourusername.github.io`**, using your real username.
3. Set it to **Public**. (Free GitHub Pages hosting requires a public repository.)
4. Click **Create repository**.

### 3. Upload these files
1. On the new repository page, click **uploading an existing file**.
2. Unzip the folder you downloaded. Drag **everything inside it** into the browser window, including the folders that start with `_`.
   *Tip:* On a Mac, the folder may hide the `_` folders. Press **Cmd + Shift + .** in Finder to show them.
3. Click **Commit changes**.

### 4. Turn on GitHub Pages
1. In the repository, go to **Settings → Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
4. Wait a minute or two, then visit **https://yourusername.github.io**.

### 5. Make it yours
Open **`_config.yml`** on GitHub, click the ✏️ pencil icon, and change the `title`, `author`, `description` and `tagline`. Then edit **`about.md`** the same way.

---

## Adding a new story

1. Open the **`_stories`** folder in your repository.
2. Click **Add file → Create new file**.
3. Name the file after your story in lowercase, with dashes instead of spaces, ending in `.md`. For example, `the-long-winter.md`. The file name becomes the story's web address.
4. Copy the contents of **`STORY_TEMPLATE.md`** into the file, fill in the top section, and paste your story underneath.
5. Click **Commit changes**. Your story will be live in about a minute.

**Writing tips**
- Leave a blank line between paragraphs.
- Use `*italics*` and `**bold**`.
- Put `***` on its own line for a scene break (it shows as ⁂).
- To hide a story you're still working on, add `published: false` to its top section.

**To edit a story**, open its file and click the ✏️ pencil icon. **To delete one**, open it and choose **⋯ → Delete file**.

Delete the two sample stories (`the-lighthouse-keepers-daughter.md` and `inventory.md`) once you've added your own.

---

## Optional: use your own domain (like yourname.com)

1. Buy a domain from any registrar, such as Porkbun, Namecheap or Cloudflare. Most cost about $10–20 a year.
2. In your repository, go to **Settings → Pages → Custom domain**, enter your domain, and click **Save**.
3. Follow GitHub's instructions for adding DNS records at your registrar. Search for "GitHub Pages custom domain".
4. Once it works, tick **Enforce HTTPS**.

Your stories stay in your GitHub repository no matter which domain you use. If you ever want to leave GitHub, download the repository. It's just text files, and almost any static host can serve them, including Netlify and Cloudflare Pages.

---

## Featured story, sidebar and theme
- **Featured story:** set `featured:` in `_config.yml` to a story's exact title. Set it to `""` to hide the banner.
- **Sidebar:** edit your bio, Reddit username and book details under `sidebar:` and `book:` in `_config.yml`.
- **Book cover:** save an image as `assets/img/shadoweaver.jpg`, then set `cover: "/assets/img/shadoweaver.jpg"`. Until you do, a simple drawn cover is shown.
- **Theme:** the site is dark by default. Readers can switch to light with the ☀ button, and their choice is remembered. Colors are at the top of `assets/css/archive.css`.
- **Reading progress:** each reader's progress is saved in their own browser. Nothing is sent anywhere.

## Keeping a backup
On the repository's main page, click **Code → Download ZIP** now and then. That ZIP is a complete copy of your archive.

## Changing the look
Colors and fonts are at the top of `assets/css/style.css`. The site switches to dark mode automatically when a reader's device is set to dark mode.

## What's included
| File / folder | What it is |
|---|---|
| `_stories/` | Your stories, one file each |
| `_config.yml` | Site title, your name, and other settings |
| `about.md` | Your About page |
| `STORY_TEMPLATE.md` | Copy this to start a new story |
| `_layouts/`, `assets/` | Design files. You don't need to touch these |

The home page includes search plus genre and length filters. Every story shows its word count and reading time and links to the next and previous stories. The site also publishes an RSS feed so readers can follow new stories.
