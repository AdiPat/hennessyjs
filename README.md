# 👽 HennessyJS

## 🌟 Introduction

HennessyJS is an innovative, open-source Generative AI scripting environment inspired by GenAIScript by Microsoft. It provides developers with a powerful toolset for creating, managing, and deploying AI-driven applications using JavaScript.

## 💡 Inspiration & Problem Statement

HennessyJS is an open-source Generative AI scripting environment designed to address the challenges developers face when integrating AI capabilities into their projects. As the field of Gen AI scripting lacks comprehensive tooling, HennesyJS aims to contribute to this space by providing a JavaScript-based framework that simplifies AI development workflows.

## 🚀 Usage

```javascript
// Example HennesyJS script
import { def, $, defSchema } from "hennessyjs";

// Define context
def("FILE", env.files, { endsWith: ".pdf" });

// Define data schema
const schema = defSchema("DATA", { type: "array", items: { type: "string" } });

// Execute AI task
$`Analyze FILE and extract data to JSON using the ${schema} schema.`;
```

## 🛠️ Development Setup

1. Clone the repository:

   ```
   git clone https://github.com/hennesyjs/hennessyjs.git
   ```

2. Install dependencies:

   ```
   cd hennesyjs
   npm install
   ```

3. Set up your environment variables:

   ```
   cp .env.example .env
   ```

   Edit the `.env` file with your API keys and configurations.

4. Run the development server:
   ```
   npm run dev
   ```

## 🧪 Testing

Run the test suite:

```
npm test
```

## 📚 Documentation

For detailed documentation, visit our [official docs](https://docs.hennesyjs.com).

## 🤝 Contributors

We welcome contributions from the community! Please check our [Contribution Guidelines](CONTRIBUTING.md) for more information on how to get started.

## 📜 License

HennesyJS is open-source software licensed under the [MIT license](LICENSE).

## 🔗 Links

- [GitHub Repository](https://github.com/hennesyjs/hennesyjs)
- [npm Package](https://www.npmjs.com/package/hennesyjs)
- [Documentation](https://docs.hennessyjs.com)

## 🙏 Acknowledgements

HennesyJS is inspired by the great work done by the GenAIScript team (Microsoft) and the broader AI community. We're standing on the shoulders of giants to bring you this powerful tool.
