# Your first website — six steps

You are about to have a real website, live on the internet, with your name on
it. It takes about five minutes and you do not need to know how to code.

You do not need to install anything. Everything below happens in your browser.

---

## Before you start

Two things, both free, both two minutes:

1. A **GitHub account** — [github.com](https://github.com)
2. Your **Cal Poly ChatGPT** login — go to [chatgpt.com](https://chatgpt.com),
   click *Log in*, enter your Cal Poly email, choose **Cal Poly San Luis Obispo SSO**

---

## The six steps

### 1. Click the green **Use this template** button

It is at the top right of this page. Choose **Create a new repository**.

> _[SCREENSHOT: top of the repo page with the green button circled]_

### 2. Name it and click **Create repository**

Any name works. `my-first-site` is fine. Leave everything else alone.

### 3. Turn your website on

In your new repository: **Settings** → **Pages** (left sidebar) →
under *Source* choose **Deploy from a branch** → pick **main** → **Save**.

> _[SCREENSHOT: the Pages settings panel with Source set to main]_

### 4. Wait about a minute, then open your site

Refresh the Settings → Pages screen. A link appears at the top that looks like:

```
https://YOUR-USERNAME.github.io/my-first-site/
```

Click it. **That is your website. It is live. Anyone in the world can open it.**

> If you get a 404, wait another 30 seconds and refresh. The first build is
> the slow one.

### 5. Change something

Go back to your repository, click **index.html**, then click the **pencil icon**
(top right of the file). Find your name near the top and change it.
Scroll down and click **Commit changes**.

> _[SCREENSHOT: the pencil / edit icon on a file view]_

### 6. Refresh your site

Give it a minute, then refresh. It changed. That loop — edit, commit, refresh —
is everything you will do for the rest of the semester.

---

## Now the actual session

Open ChatGPT and ask it for a website. Anything you want.

**If ChatGPT gives you a whole page** (its answer starts with `<!DOCTYPE html>`),
open `index.html`, select everything, delete it, and paste theirs in. That is
normal and expected.

**If ChatGPT gives you a piece** — a section, a form, a list — paste it between
the two clearly marked lines in the middle of `index.html`.

Then do it again, but this time fill in [`SPEC.md`](SPEC.md) first and give
ChatGPT those six lines instead of a one-line prompt. Compare the two.

That comparison is the entire lesson.

---

## If something looks broken

| What you see | What it is |
|---|---|
| **404 page not found** | The first build takes about a minute. Wait and refresh. If it persists, check the file is named exactly `index.html` — all lowercase. |
| **Site did not change** | It caches for a minute. Hard refresh: `Ctrl+Shift+R` on Windows, `Cmd+Shift+R` on Mac. |
| **The page looks wrecked** | You probably pasted a whole page inside the markers. Undo it — go to the file, click **History**, open the version before your change, and copy it back. Or grab an officer; it takes ten seconds. |
| **Cannot find the pencil icon** | Click the file name first, *then* look at the top right of the file box. |
| **No laptop** | Pair up with whoever is next to you. Put both names in the footer and both of you ship it. |

---

## Ask

Post in **#help** in the CPVC Slack. No question is too basic — half the room
is doing this for the first time today, and the other half was doing it for the
first time last semester.
