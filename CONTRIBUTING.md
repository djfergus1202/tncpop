# Contributing to BioMed Research Suite Ultimate

First off, thank you for considering contributing to BioMed Research Suite! It's people like you that make this tool better for the scientific community.

## 🤝 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples**
- **Describe the behavior you observed and expected**
- **Include screenshots if applicable**
- **Include your browser version and operating system**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide a detailed description of the suggested enhancement**
- **Explain why this enhancement would be useful**
- **List any similar implementations you know of**

### Pull Requests

1. Fork the repo and create your branch from `main`
2. Make your changes
3. Test your changes thoroughly
4. Update documentation if needed
5. Submit a pull request

#### Pull Request Process

1. **Update the README.md** with details of changes if applicable
2. **Update the version number** following semantic versioning
3. **Ensure code quality**:
   - Code is well-commented
   - Follows existing code style
   - No console errors
   - Works on multiple browsers

4. **Write a clear commit message**:
   ```
   feat: Add new protein database entry for ABC-1
   
   - Added ABC-1 protein with 2.0Å resolution
   - Included active site residues and druggability score
   - Updated documentation with new protein details
   ```

## 💻 Development Setup

1. Clone your fork:
   ```bash
   git clone https://github.com/your-username/biomed-suite-ultimate.git
   cd biomed-suite-ultimate
   ```

2. Start a local server:
   ```bash
   python -m http.server 8000
   ```

3. Open `http://localhost:8000` in your browser

4. Make your changes to `index.html`

5. Test thoroughly on:
   - Chrome
   - Firefox
   - Safari
   - Edge

## 📋 Code Style Guidelines

### JavaScript
- Use ES6+ features
- Use `const` and `let`, not `var`
- Use meaningful variable names
- Add comments for complex logic
- Keep functions small and focused

### CSS
- Use CSS variables for theme colors
- Follow BEM naming convention where appropriate
- Maintain responsive design
- Test on multiple screen sizes

### React Components
- Use functional components with hooks
- Keep components focused and reusable
- Use descriptive prop names
- Add PropTypes or comments for prop documentation

## 🧪 Testing Checklist

Before submitting:

- [ ] Code runs without errors
- [ ] All modules function correctly
- [ ] Export functions work (JSON/CSV)
- [ ] Responsive design is maintained
- [ ] No console warnings or errors
- [ ] Works on Chrome, Firefox, Safari
- [ ] Mobile view is functional

## 📝 Commit Message Guidelines

Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, etc.)
- `refactor:` - Code refactoring
- `perf:` - Performance improvements
- `test:` - Adding tests
- `chore:` - Maintenance tasks

Examples:
```
feat: Add new cell line MCF-10A to cell dynamics module
fix: Correct binding affinity calculation for Mode 3
docs: Update README with new deployment instructions
style: Format CSS with proper indentation
refactor: Simplify docking parameter validation
perf: Optimize canvas rendering for better FPS
```

## 🎯 Focus Areas for Contributions

We especially welcome contributions in these areas:

### High Priority
- Additional protein structures (with validated data)
- More FDA-approved drug compounds
- Enhanced visualization features
- Performance optimizations
- Bug fixes

### Medium Priority
- Additional cell lines
- New simulation types for video module
- Improved analytics and charts
- Documentation improvements
- Accessibility enhancements

### Future Features
- PDB file import/export
- ADMET predictions
- Machine learning integration
- Batch processing capabilities
- API integrations

## 🔬 Scientific Accuracy

When contributing scientific content:

1. **Cite your sources** - Include references for protein data, drug information, etc.
2. **Validate data** - Ensure parameters are scientifically accurate
3. **Use standard formats** - Follow PDB conventions, SMILES notation, etc.
4. **Document assumptions** - Clearly note any simplifications or assumptions made

## 💬 Community

- Be respectful and inclusive
- Welcome newcomers and help them get started
- Follow the [Code of Conduct](CODE_OF_CONDUCT.md)
- Ask questions in GitHub Discussions
- Share your use cases and success stories

## 📜 Code of Conduct

### Our Pledge

We pledge to make participation in our project a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity, level of experience, nationality, personal appearance, race, religion, or sexual orientation.

### Our Standards

**Positive behavior includes:**
- Using welcoming and inclusive language
- Being respectful of differing viewpoints
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards others

**Unacceptable behavior includes:**
- Harassment, trolling, or derogatory comments
- Public or private harassment
- Publishing others' private information
- Other conduct inappropriate in a professional setting

## 📞 Questions?

Feel free to:
- Open an issue for questions
- Start a discussion in GitHub Discussions
- Reach out via email (listed in README)

---

## 🙏 Thank You!

Your contributions make this project better for researchers, educators, and students worldwide. Every contribution, no matter how small, is valued and appreciated.

**Happy Contributing! 🚀**
