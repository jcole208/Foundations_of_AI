# Foundations of Artificial Intelligence: Literacy and Applications

The course textbook for **IDAI 200 – AI Fundamentals** at Maranatha Baptist University, compiled from the course's weekly reading pages (Preface and Chapters 1–7, Weeks 1–7).

## Live site

Hosted with GitHub Pages from the [`/docs`](./docs) folder on `main`:

**https://jcole208.github.io/Foundations_of_AI/**

(If the link above 404s, GitHub Pages hasn't been turned on for this repo yet — see below.)

## Repo contents

- `docs/index.html` — the complete merged textbook (Preface + Chapters 1–7), self-contained aside from the images below.
- `docs/*.jpg`, `docs/*.png` — every image referenced by `index.html`, packaged alongside it so the page renders correctly once hosted.
- `Foundations of AI.html` — the original single-file upload (same text content as `docs/index.html`, but without its images, since it was uploaded on its own).

## Enabling GitHub Pages (one-time, manual step)

This was pushed via an API-restricted proxy that can't flip repository settings, so Pages needs to be turned on by hand:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set **Branch** to `main` and the folder to **`/docs`**, then **Save**.
4. GitHub will publish the site at `https://jcole208.github.io/Foundations_of_AI/` within a minute or two.

## License

Licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), per the textbook's own Preface.
