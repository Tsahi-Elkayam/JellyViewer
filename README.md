# Jenkins Jelly Email Viewer

A powerful desktop-style web application for developing, editing, and previewing Jenkins Jelly email templates with real-time variable substitution and live preview capabilities.

![Jenkins Jelly Email Viewer](https://img.shields.io/badge/Jenkins-Jelly%20Email%20Viewer-blue?style=for-the-badge&logo=jenkins)

## ✨ Features

### 📁 **File Management**
- **Open Files**: Load individual `.jelly`, `.xml`, `.html`, and `.txt` files
- **Open Folders**: Import entire directories containing email templates
- **File Explorer**: Browse through loaded files with intuitive icons
- **Multi-file Support**: Work with multiple templates simultaneously

### ⚙️ **Variable Management**
- **Auto-detection**: Automatically extracts variables from Jelly scripts (e.g., `${BUILD_NUMBER}`)
- **Live Editing**: Modify variable values in real-time
- **Apply Changes**: See instant preview updates with new variable values
- **Common Variables**: Pre-configured with typical Jenkins variables

### 📝 **Editor & Preview**
- **Syntax Highlighting**: Code editor with Jelly/XML support
- **Three View Modes**:
  - **Editor**: Full-screen code editing
  - **Preview**: Live HTML email preview
  - **Split View**: Side-by-side editor and preview
- **Auto-save**: Changes persist while switching between files
- **Live Updates**: Preview updates automatically as you type

## 🚀 Getting Started

### Quick Start
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start editing the sample templates or load your own files

### Loading Your Templates
1. Click the **📄** button to open individual files
2. Click the **📁** button to open entire folders
3. Select your Jenkins Jelly email template files
4. Start editing and previewing!

## 📋 Supported File Types

- `.jelly` - Jenkins Jelly email templates
- `.xml` - XML-based email templates
- `.html` - HTML email templates
- `.txt` - Plain text templates

## 🎯 Use Cases

### **Jenkins Email Development**
Perfect for developing and testing Jenkins email notifications before deploying them to your Jenkins instance.

### **Template Testing**
Test how your email templates look with different variable values without triggering actual Jenkins builds.

### **Team Collaboration**
Share and review email templates with your team using the split-view mode.

### **Documentation**
Create documentation and examples of your email templates with various scenarios.

## 🛠️ Built With

- **HTML5** - Structure and layout
- **CSS3** - Modern dark theme styling
- **JavaScript** - Interactive functionality
- **File API** - Local file handling
- **No Dependencies** - Pure vanilla web technologies

## 📖 Sample Templates Included

The application comes with three sample Jenkins email templates:

1. **Build Notification** - Standard build success/failure notifications
2. **Test Results** - Test execution summaries with pass/fail counts
3. **Deployment** - Deployment success notifications

## 🔧 Common Jenkins Variables

The tool recognizes and provides defaults for common Jenkins variables:

- `BUILD_NUMBER` - Jenkins build number
- `PROJECT_NAME` - Project/job name
- `BUILD_STATUS` - Build result (SUCCESS, FAILURE, etc.)
- `BUILD_URL` - Link to build details
- `JOB_NAME` - Jenkins job name
- `BUILD_TIMESTAMP` - Build execution time
- `GIT_COMMIT` - Git commit hash
- `GIT_BRANCH` - Git branch name

## 💡 Tips & Best Practices

### **Variable Naming**
- Use uppercase letters and underscores for variable names
- Follow Jenkins environment variable conventions
- Use descriptive names that clearly indicate the variable purpose

### **Template Organization**
- Keep templates organized in folders by purpose (builds, deployments, tests)
- Use consistent naming conventions
- Include comments in your Jelly templates for team collaboration

### **Testing Scenarios**
- Test templates with both success and failure scenarios
- Try different variable combinations
- Check how templates render with long/short content

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

- Report bugs and issues
- Suggest new features
- Improve documentation
- Add support for additional template formats
- Enhance the user interface

## 📝 License

This project is open source and available under the MIT License.

## 🆘 Troubleshooting

### **Files Not Loading**
- Ensure your browser supports the File API (modern browsers do)
- Check that files are valid text files
- Try opening files individually if folder import fails

### **Variables Not Updating**
- Make sure to click "Apply Changes" after modifying variables
- Check that variable names match exactly (case-sensitive)
- Verify Jelly syntax: `${VARIABLE_NAME}`

### **Preview Not Showing**
- Switch to Preview or Split View mode
- Check for HTML syntax errors in your template
- Ensure the template contains valid HTML structure

## 🔗 Related Resources

- [Jenkins Documentation](https://www.jenkins.io/doc/)
- [Jelly Tags Reference](https://commons.apache.org/proper/commons-jelly/tags.html)
- [Jenkins Email Extension Plugin](https://plugins.jenkins.io/email-ext/)
- [Jenkins Environment Variables](https://www.jenkins.io/doc/book/pipeline/jenkinsfile/#using-environment-variables)

---

**Made with ❤️ for the Jenkins community**

*Simplify your Jenkins email template development workflow*