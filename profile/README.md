# Welcome to t8ngs 🧪

> **"test eight things"** - Testing solutions that are simple, fast, and powerful.

We are a technology-focused organization dedicated to building innovative testing solutions and contributing to the open source community. Our mission is to make testing more accessible, efficient, and enjoyable for developers worldwide.

## 🚀 Our Flagship Project

### [@t8ngs/core](https://github.com/t8ngs/core)
[![npm version](https://badge.fury.io/js/@t8ngs%2Fcore.svg)](https://badge.fury.io/js/@t8ngs%2Fcore)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue.svg)](https://www.typescriptlang.org)

A lightweight, TypeScript-first testing framework core that provides the essential building blocks for creating test runners and testing frameworks. Inspired by modern testing practices, it offers:

- 🎯 **TypeScript First**: Built with TypeScript for excellent type safety and IntelliSense
- 📦 **Dual Module Support**: Works with both ESM and CommonJS
- 🔧 **Extensible Architecture**: Designed to be extended and customized
- 🚀 **Lightweight & Fast**: Minimal dependencies, maximum performance
- 🧪 **Event-driven System**: Rich event system for building reporters and plugins
- 🏷️ **Flexible Filtering**: Filter tests by tags, titles, or custom criteria

```typescript
import { Runner, Test } from '@t8ngs/core'

const runner = new Runner()
const test = new Test('should work correctly', (context) => {
  // Your test logic here
})

runner.add(test)
const summary = await runner.run()
```

## 🎯 Our Mission

- 🚀 **Innovation**: Developing cutting-edge testing solutions using modern technologies
- 🌐 **Open Source**: Contributing to the global developer community
- 📚 **Knowledge Sharing**: Promoting learning and collaboration in testing practices
- 🔧 **Quality**: Maintaining high standards in code quality and documentation
- ⚡ **Performance**: Building fast, efficient, and reliable testing tools

## 🛠️ Technologies We Love

- **TypeScript** - For type safety and developer experience
- **Node.js** - For robust backend solutions
- **Modern JavaScript** - ESM, async/await, and latest features
- **Testing Frameworks** - Building and improving testing ecosystems
- **Open Source** - Transparent, collaborative development

## 🤝 Get Involved

We welcome contributions from developers of all skill levels! Here's how you can get involved:

### 🌟 Star Our Repositories
Show your support by starring our projects - it helps us understand what the community finds valuable.

### 🍴 Fork & Contribute
- Check out our [contribution guidelines](https://github.com/t8ngs/core#contributing)
- Look for issues labeled `good first issue` or `help wanted`
- Submit pull requests with improvements, bug fixes, or new features

### 💬 Join the Conversation
- Open issues for bug reports or feature requests
- Share your ideas and feedback
- Help answer questions from other community members

### 📖 Documentation
Help us improve our documentation - from fixing typos to writing comprehensive guides.

## 📚 Resources

- 📦 **npm**: [@t8ngs/core](https://www.npmjs.com/package/@t8ngs/core)
- 📖 **Documentation**: Check individual repository READMEs for detailed guides
- 🐛 **Issues**: Report bugs or request features in the respective repositories
- 💡 **Discussions**: Join conversations about testing best practices

## 📬 Connect With Us

- 📧 **Maintainer**: [@JefteCosta](https://github.com/JefteCosta) (jefteamorim@gmail.com)
- 🐙 **GitHub Issues**: For questions, bug reports, or feature requests
- ⭐ **Follow us**: Stay updated with our latest projects and releases

## 📄 License

Our projects are typically released under the MIT License, promoting open collaboration and reuse. Check individual repositories for specific licensing information.

---

*Building better testing tools, one commit at a time.* 🚀
