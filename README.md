# 🚀 Welcome to the Heartbeat of ILLA's GitHub Community!

Hey there! 👋 You've landed in the magical `.github` repository—the secret sauce behind the scenes of ILLA's thriving open-source ecosystem.

## 🎯 What's in here?

This special repository is our centralized hub for:

- 🌟 **Reusable GitHub Workflows:** Effortlessly consistent CI/CD pipelines across all our projects.
- 📋 **Issue & PR Templates:** Streamlined contributions and crystal-clear communication.
- 🤝 **Community Health Files:** Code of conduct, contributing guidelines, and more to ensure our community stays inclusive and vibrant.

## 🚧 Reusable Workflows? We've got you covered!

Our workflows are centralized, reusable, and ready-to-go. Simply reference them from your repositories, and voilà—standardized deployments and builds across the board!

Here's a quick example:

```yaml
jobs:
  build-and-deploy:
    uses: go-illa/.github/workflow-templates/**/**.yml@main
    with:
      environment: production
```

Just like magic! ✨

## 🌈 Contributing

Your ideas are gold! We're open to improvements, suggestions, and creative innovations.

- See something that can be better? Open an issue!
- Want to contribute? Submit a PR!

## 🧾 PR Requirements

Before submitting or updating your Pull Request, make sure to complete the following checklist:

1. **Assign a reviewer** to your PR.
2. **Add the correct priority and severity labels.**
3. Ensure all **Semaphore CI pipelines** and **GitHub workflow checks** have passed successfully.
4. Include the **Jira ticket description** in the **PR description**.
5. Make sure the **PR title** is valid, clear, and follows the naming convention.
6. Review and handle all **Gemini** and **Copilot** comments:

   * ✅ If the comment is valid, update your code accordingly.
   * 💬 If you disagree, provide a clear and reasoned explanation in a reply comment.
7. Once everything is complete, **request or re-request a review** from the assigned reviewer.

Let's grow together.

## 🌟 Community Guidelines

We cherish a welcoming, respectful, and inclusive community. Check out our [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing Guidelines](CONTRIBUTING.md) to be a part of something awesome.

## 📫 Need help or have questions?

We're here for you! Reach out through issues or discussions in this repository, and our friendly maintainers will gladly assist.

---

Made with 💖 by the team at **ILLA**. Happy coding!
