# BuildSight AI — public interactive prototype

Static demonstration for accelerator reviewers. No backend or LLM is included. All metrics and project names are synthetic. The Copilot is scenario-based, the risk scores are illustrative, and the what-if model uses placeholder coefficients. This is not an affiliated BI Group service.

## GitHub Pages (fastest)
1. Create a **public** GitHub repository, e.g. `buildsight-ai-demo`.
2. Upload `index.html` and `README.md` to the repository root and commit.
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. Wait for the published URL shown in Pages, then open it in a private browser window.

## GitLab Pages
Upload these files to a repository, then use the included `.gitlab-ci.yml` to publish the static site through GitLab CI/CD Pages. Verify the resulting URL in Deploy → Pages.

Do not upload confidential data, tokens, or secrets.
