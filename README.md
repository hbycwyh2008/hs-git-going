# HS Git Going — Lesson & Homework

## 1. Lesson — Git Rebuild Notes

In your **Lesson folder**, create a Markdown file:

`git-rebuild-workflow.md`

Write the workflow we practiced today in your own words:

```text
clone → create branch → create index.js → add → commit → push
```

Explain what each step does.

### Two Easy-to-Miss Points

1. There must be a **space** between `git clone` and the HTTPS URL.

```bash
git clone https://github.com/hbycwyh2008/hs-git-going.git
```

2. **Create and switch to your branch before creating `index.js`.** When you push, push your own branch:

```bash
git switch -c js-yourName
git push origin js-yourName
```

---

## 2. Homework — Independent Rebuild

Complete the workflow independently in this repository:

```bash
git clone https://github.com/hbycwyh2008/hs-git-going.git
cd hs-git-going
git switch -c js-yourName
```

Then:

1. Create `index.js` and add a small amount of JavaScript.
2. Run:

```bash
git add index.js
git commit -m "Add JavaScript file"
git push origin js-yourName
```

3. Check GitHub and make sure your branch, file, and commit are visible.

### Homework Evidence

- Your `js-yourName` branch
- Your `index.js` file
- Your commit on GitHub
