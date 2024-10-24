<<<<<<< HEAD
Hello world
=======

# How to Fork and Push Commits to a Repository

This guide provides step-by-step instructions to fork a repository, make changes, and push commits to your fork on GitHub.

## 1. Fork the Repository

1. Go to the original repository:  
   [gdsai4903/COMP-3704](https://github.com/gdsai4903/COMP-3704).
2. Click the **Fork** button in the top-right corner.  
   This creates a copy of the repository under your GitHub account.

## 2. Clone Your Fork Locally

Open your terminal or Git Bash and run the following commands:

```bash
git clone https://github.com/YOUR-USERNAME/COMP-3704.git
cd COMP-3704
```

This clones the forked repository and navigates into the project folder.

## 3. Set Upstream to Track the Original Repository

This step ensures you can keep your fork updated with the latest changes from the original repository.

```bash
git remote add upstream https://github.com/gdsai4903/COMP-3704.git
git remote -v  # Verify the remote connections
```

## 4. Make Changes and Commit

1. Make the necessary changes to the code or project files.
2. Stage the changes:

   ```bash
   git add .
   ```

3. Commit the changes:

   ```bash
   git commit -m "Your descriptive commit message"
   ```

## 5. Push Changes to Your Fork

Push your committed changes to **your forked repository** on GitHub:

```bash
git push origin main
```

## 6. Create a Pull Request

1. Go to your fork on GitHub.
2. Click **Compare & pull request**.
3. Add a meaningful title and description, and click **Create pull request**.

## 7. Keep Your Fork Updated with the Original Repository

1. Fetch changes from the original repository:

   ```bash
   git fetch upstream
   ```

2. Merge the changes into your local branch:

   ```bash
   git merge upstream/main
   ```

3. Push the updates to your fork:

   ```bash
   git push origin main
   ```

## Troubleshooting

If you encounter merge conflicts:
1. Resolve conflicts manually in the affected files.
2. Stage the resolved files:

   ```bash
   git add .
   ```

3. Commit the merge:

   ```bash
   git commit -m "Resolved merge conflict"
   ```

4. Push the changes:

   ```bash
   git push origin main
   ```

---

This README provides clear instructions to help you fork, make changes, and collaborate efficiently on GitHub.
>>>>>>> e541cd7 (update readme)
