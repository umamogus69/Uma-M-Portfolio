# Make it yours

Work through these in order. Everything you need to change is marked
with an `<!-- EDIT: ... -->` comment in `index.html`.

## 1. Colors & fonts (2 min, no code experience needed)

Open `css/theme.css`. Change the hex values under `:root`. Try one of
the alternate palettes near the bottom of the file — copy a block over
the defaults and save. Refresh your browser to see it update.

## 2. Your name and intro

In `index.html`, find and edit:
- `<title>` in the `<head>` — shows in the browser tab
- `.nav-name` — your name in the top nav
- `.hero-eyebrow` — your role ("Computer Science student", "Aspiring
  backend engineer", whatever's true for you)
- The `<h1>` — your name + a one-line hook. What do you want someone
  to know about you in one sentence?
- The paragraph under it — 1-2 sentences of context

## 3. About section

Rewrite the two paragraphs under `id="about"`. This can be more
personal than the hero — how you got into CS, what you're into outside
of it.

Replace `images/profile-placeholder.svg` with a real photo:
1. Add your photo to the `images/` folder (e.g. `profile.jpg`)
2. Update the `src` on the `<img class="about-photo">` line

## 4. Projects

Each project is one `<article class="project-card">` block. To edit
one: change the `<h3>` title, the description, the `<span class="tag">`
list, and the link's `href`.

To add a new project, copy an entire `<article>...</article>` block
and paste it before `</div>` (closing the `.project-grid`). Use
`featured` on the class of at most one card — it spans the full width,
good for your best project.

Don't have 3 projects yet? Class assignments count. A half-finished
side project counts. Pick what best shows how you think.

## 5. Skills

Edit the `<li>` items in the `.skills-list`. Keep it to things you
could actually talk about in an interview.

## 6. Contact

Update the `href`s in `.contact-links` to your real email, GitHub,
LinkedIn, and resume link. If you don't want to link a resume yet,
delete that `<li>`.

## 7. Deploy

Once it looks right locally, follow the "Deploying with GitHub Pages"
section in `README.md`.
