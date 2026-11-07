Okay, here is a standard `CONTRIBUTING.md` file tailored for the "Awesome Starlette" list.

---

# Contributing to Awesome Starlette

First off, thank you for considering contributing to Awesome Starlette! Your help is essential for keeping this list valuable and up-to-date for the Starlette community.

Following these guidelines helps maintainers and the community understand your suggestion and incorporate it efficiently.

## Table of Contents

-   [Code of Conduct](#code-of-conduct)
-   [How Can I Contribute?](#how-can-i-contribute)
    -   [Suggesting a New Item](#suggesting-a-new-item)
    -   [Reporting Issues](#reporting-issues)
    -   [Improving Existing Items](#improving-existing-items)
-   [Submission Guidelines](#submission-guidelines)
    -   [Choosing the Right Category](#choosing-the-right-category)
    -   [Formatting](#formatting)
    -   [Criteria for Awesome](#criteria-for-awesome)
-   [Your First Code Contribution](#your-first-code-contribution)
-   [Pull Request Process](#pull-request-process)

## Code of Conduct

This project and everyone participating in it are governed by a basic code of conduct: be respectful, considerate, and helpful. We aim to foster an open and welcoming environment. Harassment or insulting behavior will not be tolerated.

## How Can I Contribute?

### Suggesting a New Item

Found a great Starlette extension, framework, tool, or resource that isn't listed? Awesome! Please check the following:

1.  **Search first:** Make sure the item isn't already on the list.
2.  **Check criteria:** Ensure the item meets the [Criteria for Awesome](#criteria-for-awesome).
3.  **Submit a PR:** Follow the [Pull Request Process](#pull-request-process) to add the item.

### Reporting Issues

-   Use the GitHub issue tracker to report typos, broken links, outdated information, or items that might no longer meet the criteria.
-   Provide as much context as possible.

### Improving Existing Items

-   Notice an inaccurate description, a missing docs link, or a better category? Submit a PR with the correction!

## Submission Guidelines

### Choosing the Right Category

-   Place your item under the most relevant existing category.
-   If no suitable category exists, feel free to suggest a new one within your Pull Request description. We can discuss it there.

### Formatting

Please adhere to the following format for consistency:

```markdown
- [Project Name](Link to Repository/Website) ★GitHub Stars (Optional but encouraged) - Brief, objective description. [Docs](Link to Docs) (If available).
```

-   **Project Name:** The official name of the project/resource.
-   **Link:** Direct link to the primary source (GitHub/GitLab repo preferred, official website otherwise). No shorteners.
-   **GitHub Stars:** Add `★` followed by the approximate star count (e.g., `★250`). This helps gauge popularity but isn't the main factor. It's okay if you don't add it - it's recomputed periodically using a script.
-   **Description:** A concise (usually one sentence) and objective summary. Focus on what it *does*. Avoid marketing buzzwords or subjective claims ("the best," "easiest").
-   **Docs Link:** Optional, but highly recommended. Link directly to the project's documentation.
-   **Order:** Keep items alphabetically sorted within each category.
-   **Emoji:** Use `⚠️` *before* the project name for projects that are explicitly archived, unmaintained, or deprecated (e.g., `⚠️ [Old Project](...)`).

### Criteria for Awesome

To be included, items should generally meet these criteria:

1.  **Relevance:** Directly related to Starlette (built on it, integrates with it, significantly useful for Starlette developers).
2.  **Usefulness:** Provides tangible value to the Starlette community.
3.  **Quality & Maintenance:**
    -   Generally, projects should be stable and reasonably maintained.
    -   Good documentation is a strong plus.
    -   While we aim for active projects, notable *unmaintained* projects that were historically important or still fill a unique niche *can* be included but *must* be marked with `⚠️`.
4.  **Uniqueness:** Offers distinct functionality or approach compared to other listed items, where possible.
5.  **Not Purely Commercial (Usually):** While tools with commercial aspects are okay (e.g., APM services), the list shouldn't become an advertising board. The primary link/focus should be on the tool/integration itself.

*Maintainers have the final say on whether an item fits the list.*

## Pull Request Process

1.  **Fork the repo:** Click the 'Fork' button on the [Awesome Starlette](https://github.com/your-username/awesome-starlette) repository (replace `your-username/awesome-starlette` with the actual repo path).
2.  **Clone your fork:** `git clone https://github.com/YOUR_USERNAME/awesome-starlette.git`
3.  **Make your changes:** Add your item(s) or fix the issue. Remember to follow the [Formatting](#formatting) and [Criteria](#criteria-for-awesome).
4.  **Commit your changes:** `git commit -m "Add: Cool Middleware project"` or `git commit -m "Fix: Broken link in Auth section"` (Use a descriptive commit message).
5.  **Push to your fork:** `git push origin`
6.  **Open a Pull Request:** Go to the original Awesome Starlette repository on GitHub and click 'New pull request'. Choose your fork and branch.
7.  **Describe your PR:** Fill in the PR template. Explain *what* you added/changed and *why* it belongs on the list (how it meets the criteria). Link to any relevant issues.
8.  **Submit:** Click 'Create pull request'.

Maintainers will review your PR. Be prepared to answer questions or make adjustments based on feedback. Thank you for your contribution!
