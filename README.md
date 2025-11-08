# Updatest Community Feedback

Welcome to the Updatest community feedback repository! This is where you can report bugs, request features, ask questions, and discuss improvements for [Updatest](https://updatest.app).

You can also join us on [Discord](https://discord.gg/BRk3vvKk9Z).

## About Updatest

Updatest is a native macOS app written in SwiftUI that keeps your apps up to date from sources like: Homebrew, Mac App Store and Sparkle. Updatest also helps you adopt your existing applications to Homebrew management for easy update management.

**🚨 This repository is for feedback only - source code is not available here.**

## How to Contribute

### 🐛 Report a Bug

Found something broken? [Create a bug report](../../issues/new?template=bug_report.md) with:

- Steps to reproduce
- Expected vs actual behavior
- Your macOS version and Updatest version
- Any relevant screenshots or logs

### 💡 Request a Feature

Have an idea to make Updatest better? [Submit a feature request](../../issues/new?template=feature_request.md) with:

- Clear description of the feature
- Use case or problem it solves
- Any mockups or examples (optional)

### ❓ Ask a Question

Need help or have general questions? [Start a discussion](../../issues/new?template=question.md) or check existing issues first.

### 🗳️ Vote on Features

Use GitHub reactions (👍 👎) on issues to show support for features or bugs you care about. This helps prioritize development.

## Before You Post

1. **Search existing issues** - your issue might already be reported
2. **Check the FAQ** below for common questions
3. **Use appropriate labels** - they help organize and prioritize issues

## FAQ

### General

**Q: Where can I download Updatest?**
A: Visit [updatest.app](https://updatest.app) for download links and more information.

**Q: Is Updatest free?**
A: Updatest has a 14 day free trial. Pricing information is available on our website at [updatest.app](https://updatest.app).

**Q: What macOS versions are supported?**
A: Updatest requires macOS 15.0 (Sequoia) or later.

### Troubleshooting

**Q: Updatest says Homebrew isn't installed, but I have it**
A: Updatest checks for Homebrew in standard locations:

- `/opt/homebrew/bin/brew` (Apple Silicon)
- `/usr/local/bin/brew` (Intel)

If you installed Homebrew elsewhere, Updatest may not find Homebrew. You can reinstall Homebrew from [brew.sh](https://brew.sh).

**Q: Why isn't my app showing up after discovery?**
A: Updatest only scans `/Applications` for `.app` bundles. Apps in other locations or non-standard formats may not be detected.

**Q: An app is showing Homebrew Available but the wrong cask**
A: You can manually override the suggested cask name using 'Manual Cask' at any time.

### Privacy & Security

**Q: What data does Updatest collect?**
A: Updatest operates entirely locally on your Mac. No data is sent to external servers except for fetching Homebrew cask information from the official Homebrew API.

**Q: Is it safe to link my existing apps?**
A: Yes. Updatest uses standard Homebrew commands and doesn't modify your existing applications. It simply tells Homebrew to manage them going forward.

## Support

- 🌐 **Website**: [updatest.app](https://updatest.app)
- 📧 **Email**: [hello@hugeideas.ca](mailto:hello@hugeideas.ca)
- 🐛 **Bug Reports**: [Create an issue](../../issues/new?template=bug_report.md)

## Labels

We use these labels to organize issues:

- `bug` - Something isn't working correctly
- `enhancement` - New features or improvements
- `question` - General questions or support requests
- `documentation` - Improvements to docs or help text
- `good first issue` - Easy issues for new contributors
- `priority-high` - Critical bugs or important features
- `priority-low` - Nice-to-have improvements
- `wontfix` - Issues we've decided not to implement
- `duplicate` - Duplicate of another issue

## Code of Conduct

Please be respectful and constructive in all interactions. We're here to make Updatest better together!

---

Made with ❤️ by [Huge Ideas](https://hugeideas.ca)
