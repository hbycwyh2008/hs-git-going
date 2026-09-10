# HS Git Going — Independent Rebuild

Practice the Git workflow by rebuilding it independently.

## Task

Clone this repository:

```bash
git clone https://github.com/hbycwyh2008/hs-git-going.git
```

> Remember: there must be a **space** between `git clone` and the HTTPS URL.

Enter the repository:

```bash
cd hs-git-going
```

Create and switch to your own branch **before creating the new file**:

```bash
git switch -c js-yourName
```

Replace `yourName` with your own name.

Create:

```text
index.js
```

Add a small amount of valid JavaScript code, then run:

```bash
git add index.js
git commit -m "Add JavaScript file"
git push origin js-yourName
```

## Verify on GitHub

Make sure:

- Your branch is named `js-yourName`
- `index.js` is on your branch
- Your commit is visible
- You did **not** push the change directly to `main`

## Required Workflow

```text
clone
→ create branch
→ create index.js
→ git add
→ git commit
→ git push origin js-yourName
→ verify on GitHub
```

## Final Step

After completing the rebuild, create a new repository on your own GitHub account for a real project.

Choose:

- a clear repository name
- an appropriate visibility setting
- a `README.md`
- an appropriate `.gitignore`
- an appropriate license

Add the link to your new repository to your Homework file.

## Evidence

- Your `js-yourName` branch in this repository
- Your `index.js` file and commit
- Your new GitHub repository link
