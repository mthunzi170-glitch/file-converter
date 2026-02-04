# Contributing to File Converter

Thank you for your interest in contributing! This project thrives on community contributions. Here's how you can help:

## Getting Started

### 1. Fork & Clone
```bash
# Fork the repository on GitHub, then clone it
git clone https://github.com/your-username/file-converter.git
cd file-converter
```

### 2. Create a Branch
```bash
# Create a feature branch
git checkout -b feature/add-heic-conversion

# Or for fixes
git checkout -b fix/image-quality-issue
```

### 3. Make Your Changes
- Write clean, readable code
- Add comments for complex logic
- Test your changes thoroughly
- Follow the existing code style

### 4. Test Locally
```bash
python -m http.server 8000
# Visit http://localhost:8000 and test your changes
```

### 5. Commit & Push
```bash
git add .
git commit -m "Add HEIC image format support"
git push origin feature/add-heic-conversion
```

### 6. Create a Pull Request
- Go to GitHub and create a Pull Request
- Describe what you changed and why
- Link any related issues

## Code Guidelines

### JavaScript
```javascript
// Use clear, descriptive names
function convertImageFormat(file, targetFormat) {
    // Add comments for non-obvious logic
    // Keep functions small and focused
}

// Use const by default, let when needed
const MAX_FILE_SIZE = 500 * 1024 * 1024;
```

### HTML/CSS
- Use semantic HTML5 elements
- Use CSS custom properties for themes
- Mobile-first responsive design
- Maintain accessibility standards

## Types of Contributions

### 🎨 UI/UX Improvements
- Design improvements
- Better mobile experience
- Accessibility enhancements
- Dark mode refinements

### ⚙️ New Features
- Additional format support
- Conversion presets
- Batch processing
- Quality settings

### 🐛 Bug Fixes
- Conversion failures
- Browser compatibility
- Performance issues
- UI glitches

### 📚 Documentation
- README improvements
- Code comments
- Usage examples
- Troubleshooting guides

### ✅ Testing
- Test different browsers
- Test mobile devices
- Test large files
- Report edge cases

## Reporting Bugs

Found a bug? Please create an issue with:

```markdown
**Describe the bug:**
A clear description of what happens.

**Steps to reproduce:**
1. Upload a [file type]
2. Select [format]
3. Click Convert

**Expected behavior:**
What should happen.

**Actual behavior:**
What actually happens.

**Environment:**
- OS: Windows 10
- Browser: Chrome 120
- File size: 50MB

**Screenshots:**
[If applicable]
```

## Suggesting Features

Have an idea? Create an issue with:

```markdown
**Feature Request:**
Brief description of the feature.

**Use Case:**
Why would this be useful?

**Proposed Solution:**
How would this work?

**Alternatives:**
Other ways to solve this?
```

## Commit Message Guidelines

Use clear, concise commit messages:

```
Good:
✨ Add WebP to PNG conversion
🐛 Fix memory leak in canvas processing
📚 Update README with examples
♿ Improve keyboard navigation

Avoid:
fixed stuff
updates
changes
work
```

## Pull Request Process

1. Update README.md with any new features
2. Add tests if applicable
3. Ensure all existing features still work
4. Request review from maintainers
5. Address feedback promptly
6. Once approved, we'll merge!

## Development Setup

### Required
- A modern browser (Chrome, Firefox, Safari, or Edge)
- A text editor (VS Code recommended)
- Python 3.x (for local server)

### Optional
- Node.js (for npm http-server)
- Git (for version control)

## Performance Considerations

When adding features, keep performance in mind:

- Minimize DOM manipulations
- Debounce frequent events
- Lazy load heavy libraries
- Monitor bundle size
- Test on low-end devices

## Accessibility Standards

Follow WCAG 2.1 guidelines:

- Keyboard navigation support
- Screen reader friendly
- Sufficient color contrast
- Clear focus indicators
- ARIA labels where needed

## Community

- Be respectful and inclusive
- Help other contributors
- Share knowledge
- Celebrate improvements
- Have fun!

## Questions?

- Check existing issues first
- Ask in discussions
- Create a new issue if unsure
- Reach out to maintainers

## License

By contributing, you agree that your contributions will be licensed under its MIT License.

---

**Thank you for helping make File Converter better! 🎉**
