# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](code-of-conduct.md). By participating in this
project you agree to abide by its terms.

---

A sample submission looks something like this:

```markdown
- [My Great App](https://apps.apple.com/...) `Free` - A brief description of what the widget does. ([Preview](https://link.to/preview.jpg)) `Small` `Medium`
```

Or, if you have multiple widget types, you can use a bulleted list to differentiate.

```markdown
- [My Great App](https://apps.apple.com/...) `Free`
  - A brief description of what the first widget does. ([Preview](https://link.to/preview1.jpg)) `Small` `Medium`
  - Another description of what the second widget does. ([Preview](https://link.to/preview2.jpg)) `Large`
```

Ensure your pull request adheres to the following guidelines:

- **Only widgets that are well designed and offer clear benefit to the user will be accepted.**
- You must include a direct link to the App Store. Redirects for analytics or affiliates are not allowed.
- Each app must list how it expects users to pay for it in USD (or the appropriate currency if region-locked outside of the US), such as `Free`, `$2.99`, `$4.99/month with trial`, `$49.99/year`, etc. **If your app has a subscription, even if optional, the subscription price MUST be listed.**
- Each widget must have a clear, concise description of what it does. Aim for a short single sentence.
- Each widget is strongly recommended to include a preview. You can include a screenshot in an app-specific subfolder in the [Screenshots] folder (e.g. `Screenshots/Twitter/preview.png) or it may link to something like a tweet, Instagram post, YouTube video, etc. demonstrating the widget, but the preview MUST focus on the widget primarily.
- Each widget is strongly recommended to include the sizes it supports.
- Your app must be published and available when the pull request is merged. If your app is pending release, you may submit a pull request with the "Unreleased" label.
- If your app is open source, please feel free to add a link to the repository alongside the App Store link, so people can find your project!

Thank you for your suggestions!

## Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md)
on the different ways you can update your PR so that we can merge it.
