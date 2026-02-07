# Contributing to Task Timer

Thank you for your interest in contributing to Task Timer! We welcome contributions from everyone. This document provides guidelines and instructions for contributing.

## Code of Conduct

Please note that this project is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How to Contribute

### Reporting Bugs

Before creating a bug report, check the issue list to ensure it hasn't already been reported. When submitting a bug report, include:

- **Clear description** of what the bug is
- **Steps to reproduce** the issue
- **Expected behavior** vs. **actual behavior**
- **Screenshots or screen recordings** if applicable
- Your **browser and OS** information
- Any **error messages** from the browser console

### Suggesting Features

Feature suggestions are always welcome! When proposing a feature:

- Describe the feature and expected behavior
- Explain the use case and why it would be beneficial
- Provide examples if possible
- Check existing issues to avoid duplicates

### Submitting Pull Requests

1. **Fork the repository** and create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** to the HTML file or related code

3. **Test thoroughly** in multiple browsers:
   - Chrome/Edge
   - Firefox
   - Safari
   - Mobile browsers

4. **Commit with clear messages**:
   ```bash
   git commit -m "Add feature: clear description of changes"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request** with:
   - Description of changes
   - Reference to related issues (#XX)
   - Before/after screenshots if applicable
   - Testing details

## Development Guidelines

### Code Style

- Use clear, descriptive variable and function names
- Add comments for complex logic
- Keep functions focused and reusable
- Follow existing code patterns

### Browser Compatibility

- Ensure changes work in modern browsers (last 2 versions)
- Test on both desktop and mobile devices
- Use standard HTML5/JavaScript features

### Performance

- Minimize impact on app load time
- Avoid unnecessary DOM manipulations
- Test with the browser's performance tools

### Accessibility

- Ensure keyboard navigation works properly
- Maintain sufficient color contrast
- Use semantic HTML elements
- Test with screen readers

## Questions?

Feel free to open an issue with the "question" label or start a discussion. We're happy to help!

## License

By contributing, you agree that your contributions will be licensed under the same GPL v3 License that covers the project.
