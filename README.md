**[See it live →](https://calpolyvibecoding-01.github.io/cpvc-starter/)**

# Your first website — six steps

You are about to have a real website, live on the internet, with your name on
it. It takes about five minutes and you do not need to know how to code.

You do not need to install anything. Everything below happens in your browser.

---

## Before you start

One thing to have, it's free:

1. A **GitHub account** — [github.com](https://github.com)

---

## The six steps

### 1. Click the green **Use this template** button

It is at the top right of this page. Choose **Create a new repository**.

<img width="932" height="98" alt="image" src="https://github.com/user-attachments/assets/02747e67-fcc0-496a-ac82-cfd9e24af473" />


### 2. Name it and click **Create repository**

Any name works. `my-first-site` is fine. Leave everything else alone.

### 3. Turn your website on

In your new repository: **Settings** → **Pages** (left sidebar) →
under *Source* choose **Deploy from a branch** → pick **main** → **Save**.

<img width="934" height="477" alt="image" src="https://github.com/user-attachments/assets/e8d430c1-9458-49ec-8711-652a83791d8f" />


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

<img width="701" height="259" alt="image" src="https://github.com/user-attachments/assets/10c995b5-198a-433c-9a7f-acbe969d0c6d" />


## Now the actual session

Open **[Gemini](https://gemini.google.com)** and sign in with a Google
account. The free version is all you need today.

### Round one — the one-liner

Ask for a website in one sentence. Anything you want. Then paste the
constraint block underneath it:

> make me a personal website
>
> Give me one complete HTML file. All CSS in a `<style>` tag. You may link
> one Google Font. No frameworks, no other external files, no build step.
> Return only the code.

Copy the result using the **copy button** on the code block — don't
click-and-drag, you'll grab the explanation text too. Paste into
`index.html`, commit, refresh your site.

It'll be okay. Not great. That's the point.

### Round two — the spec

Now fill in [`SPEC.md`](SPEC.md). Six lines. Then:

> Build me a website from this spec:
> [paste your six lines]
>
> Give me one complete HTML file. All CSS in a `<style>` tag. You may link
> one Google Font. No frameworks, no other external files, no build step.
> Return only the code.

Same copy, paste, commit, refresh.

**Now compare the two. That comparison is the entire lesson.** Same tool,
same model, same person. The only thing that changed is that you wrote it
down first.

### Round three — make it better

One more, and this is the round people skip:

> make the hero full height, tighten the spacing, and use one accent color
> instead of three

Copy, paste, commit, refresh. Iterating isn't cheating — it's the last step
of The Loop, and it's where output stops looking generated.

### Where to paste

**If Gemini gives you a whole page** — the answer starts with
`<!DOCTYPE html>` — open `index.html`, select everything, delete it, paste
theirs in. Normal and expected.

**If Gemini gives you a piece** — a section, a form, a list — paste it
between the two marked lines in the middle of `index.html`.

### The one tip that changes everything

The weakest line in most people's spec is **"What it looks like,"** because
it's tempting to write moods: *"forest aesthetic with beach vibes."* Models
turn moods into generic layouts.

Write structure instead:

> Sections in this order: hero, story, three highlights, contact. One accent
> color, deep green. Full-height hero, lots of whitespace. Should look like a
> clean personal site, not a resume.

Same six lines. Completely different result.

---

## If something looks broken

| What you see | What it is |
|---|---|
| **404 page not found** | The first build takes about a minute. Wait and refresh. If it persists, check the file is named exactly `index.html` — all lowercase. |
| **Site did not change** | It caches for a minute. Hard refresh: `Ctrl+Shift+R` on Windows, `Cmd+Shift+R` on Mac. |
| **The page looks wrecked** | You probably pasted a whole page inside the markers. Undo it — go to the file, click **History**, open the version before your change, and copy it back. Or grab an officer; it takes ten seconds. |
| **Cannot find the pencil icon** | Click the file name first, *then* look at the top right of the file box. |
| **No laptop** | Pair up with whoever is next to you. Put both names in the footer and both of you ship it. |

