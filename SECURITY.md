# Security Policy

## Reporting a vulnerability

Please **don't report security vulnerabilities through public issues, discussions or pull requests.**

Instead, report them privately in one of these ways:

1. **GitHub private vulnerability reporting (preferred).** Open the affected repository's **Security** tab and choose **Report a vulnerability**.
2. **Email** [support@codearchy.com](mailto:support@codearchy.com) with the subject line `SECURITY`.

Please include:

- the affected repository and version (for the extension, the version shown in VS Code)
- steps to reproduce, or a proof of concept
- the impact you think it has

We'll acknowledge your report within **3 business days** and keep you updated as we investigate. We'll let you know when a fix is released, and credit you if you'd like.

## Supported versions

Security fixes go into the **latest released version** of the CodeArchy VS Code extension and the current version of the website.

## Scope

CodeArchy reads your source code locally to build its diagrams. We're especially interested in issues that could:

- read or send source code, secrets or credentials somewhere the user didn't intend
- run code from an analysed repository
- break out of the VS Code webview's sandbox
