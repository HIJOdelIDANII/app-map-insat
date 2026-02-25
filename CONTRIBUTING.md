# Contributing to Map INSAT

Thanks for contributing! Follow the workflow below to keep things organized.

## Workflow

### 1. Clone the repository

```bash
git clone git@github.com:HIJOdelIDANII/app-map-insat.git
cd app-map-insat
```

### 2. Create a new branch

Always create a branch from `main`. Name it after the feature or fix you're working on.

```bash
git checkout main
git pull origin main
git checkout -b your-branch-name
```

**Branch naming examples:**
- `feature/add-search-bar`
- `fix/marker-position`
- `data/update-building-coords`

### 3. Make your changes

Work on your branch locally. Commit often with clear messages.

```bash
git add <files>
git commit -m "short description of what you did"
```

### 4. Push your branch

```bash
git push origin your-branch-name
```

### 5. Open a Pull Request

1. Go to the repository on GitHub.
2. Click **"Compare & pull request"** for your branch.
3. Fill in:
   - **Title** — a short summary of the change.
   - **Description** — what you changed and why.
4. Submit the pull request.

### 6. Code review

- At least one team member should review the PR before merging.
- Address any requested changes by pushing new commits to the same branch.

### 7. Merge

Once approved, the PR gets merged into `main`. Delete your branch after merging.

## Rules

- **Never push directly to `main`.** Always use a pull request.
- Keep pull requests small and focused on a single change.
- Pull the latest `main` before starting new work.
