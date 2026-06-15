# ivanhurba.github.io

Personal portfolio site built with Jekyll and hosted on GitHub Pages.

## Local preview

Requires Ruby and Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000).

## Deploy to GitHub Pages

1. Create a repository named `ivanhurba.github.io` on GitHub.
2. Push this repo to the `main` branch:

```bash
git remote add origin git@github.com:ivanhurba/ivanhurba.github.io.git
git push -u origin main
```

3. In the repo **Settings → Pages**, set source to **Deploy from branch** → `main` → `/ (root)`.

GitHub builds Jekyll automatically — no separate build step needed.

## Adding projects

Edit `projects.md` and duplicate a `.project-card` block for each project. Put images in `assets/images/` and reference them in markdown:

```markdown
![Alt text](/assets/images/my-project.png)
```
