# Contributing to Ultimate OSINT Hub

First off, thank you for considering contributing to Ultimate OSINT Hub! It's people like you that make this resource valuable for the entire OSINT community.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Adding New Tools](#adding-new-tools)
- [Reporting Broken Links](#reporting-broken-links)
- [Improving Documentation](#improving-documentation)
- [Style Guidelines](#style-guidelines)
- [Pull Request Process](#pull-request-process)

## Code of Conduct

This project and everyone participating in it is governed by our commitment to creating a welcoming environment. By participating, you are expected to uphold this code:

- Be respectful and inclusive
- Focus on what is best for the community
- Show empathy towards other community members
- Use welcoming and inclusive language

## How Can I Contribute?

### 🔧 Adding New Tools

We're always looking for new OSINT tools to add! Here's how:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b add-tool/tool-name`
3. **Add your tool** to the appropriate category in `README.md`
4. **If applicable**, add the tool to `index.html` in the JavaScript tools array
5. **Commit your changes**: `git commit -m 'Add [Tool Name] to [Category]'`
6. **Push to the branch**: `git push origin add-tool/tool-name`
7. **Open a Pull Request**

#### Tool Entry Format (README.md)

```markdown
| **Tool Name** | Brief description of what the tool does | [toolname.com](https://toolname.com/) |
```

#### Tool Entry Format (index.html)

```javascript
{ 
    name: "Tool Name", 
    description: "Brief description of what the tool does", 
    url: "https://toolname.com/", 
    category: "category-name", 
    tags: ["tag1", "tag2"], 
    pricing: "free" // or "freemium" or "paid"
}
```

### 🔗 Reporting Broken Links

Found a broken link? Please help us fix it!

1. **Open an Issue** with the title: `[Broken Link] Tool Name`
2. Include:
   - The tool name
   - The broken URL
   - If known, the new/correct URL
   - The category where it appears

### 📝 Improving Documentation

Documentation improvements are always welcome:

- Fix typos and grammatical errors
- Improve tool descriptions
- Add missing information
- Update outdated content
- Add tutorials or guides

### 🎨 Design Improvements

Have ideas to improve the web interface?

- UI/UX enhancements
- Accessibility improvements
- Mobile responsiveness fixes
- Performance optimizations

## Adding New Tools Checklist

Before submitting a new tool, please verify:

- [ ] The tool is publicly accessible
- [ ] The tool is related to OSINT/research
- [ ] The link is correct and working
- [ ] The tool isn't already listed
- [ ] The description is accurate and concise
- [ ] The category is appropriate
- [ ] For paid tools, the pricing model is noted

## Style Guidelines

### Tool Descriptions

- Keep descriptions concise (under 100 characters ideal)
- Focus on what the tool does, not marketing language
- Use present tense ("Searches for..." not "Will search for...")
- Avoid superlatives unless factually accurate

### Categories

Use existing categories when possible:
- `people` - People search and background checks
- `social` - Social media platforms and analysis
- `username` - Username search across platforms
- `email` - Email lookup and verification
- `phone` - Phone number lookup
- `domain` - Domain and website analysis
- `ip` - IP address and network tools
- `image` - Image analysis and reverse search
- `geo` - Geolocation and mapping
- `business` - Business and corporate intel
- `breach` - Data breach search
- `search` - Search engines and archives

### Pricing Tags

- `free` - Completely free to use
- `freemium` - Free tier with paid options
- `paid` - Requires payment to use

## Pull Request Process

1. Ensure your PR description clearly describes the changes
2. Link any relevant issues
3. Update the README.md if adding new tools
4. Update index.html if the tool should appear in the web interface
5. Verify all links are working
6. Request review from maintainers

### PR Title Format

- Adding tool: `Add [Tool Name] to [Category]`
- Fixing link: `Fix broken link for [Tool Name]`
- Documentation: `Docs: [Brief description]`
- Feature: `Feature: [Brief description]`

## Questions?

Feel free to open an issue with the `question` label if you have any questions about contributing.

---

Thank you for helping make Ultimate OSINT Hub better! 🔍
