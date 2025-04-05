# AI Project Kickstarter

A beginner-friendly template for starting new AI-powered coding projects. This repository helps you set up everything you need to start coding with AI assistance.

## Purpose

This repository gives you a ready-to-use starting point for AI coding projects. It includes:

- All the necessary folders and files to get started
- Templates for planning your project
- Settings for the Cursor AI coding assistant
- Best practices for working with AI

## Getting Started

### 1. Project Planning
First, create your project requirements using the templates in the `docs` folder:
   - Start with the Product Requirements Document (PRD) to define what you're building
   - Then create the User Requirements Document (URD) to describe who will use it
   - Finally, make the Software Requirements Specification (SRS) to plan how to build it

### 2. Basic Setup
Make sure you have these installed on your computer:
   - [Node.js](https://nodejs.org/) (version 18 or higher)
   - [Cursor IDE](https://cursor.sh/)
   - [Git](https://git-scm.com/)

### 3. Install Project Tools
Open your terminal and run:
```bash
# Install all the tools the project needs
npm install
```

### 4. Cursor IDE Setup
1. Open the project in Cursor IDE
2. Look through the `.cursor/rules` folder to see how AI will help you
3. You can customize these rules for your specific project

## Complete Project Structure

```
.
├── src/                           # Your code goes here
│   └── index.ts                   # Main entry point
│
├── dist/                          # Compiled code (created automatically)
│
├── docs/                          # Project documentation
│   ├── 00-project-setup-prompts.md    # AI prompts for setup
│   ├── 01-product-requirements.md      # What you're building
│   ├── 02-user-requirements.md         # Who will use it
│   └── 03-software-requirements.md     # How to build it
│
├── .cursor/                       # Cursor IDE settings
│   └── rules/                     # AI behavior rules
│       ├── backend/              # Rules for backend code
│       ├── frontend/             # Rules for frontend code
│       └── specialized/          # Rules for specific tasks
│
└── package.json                   # Project settings and tools
```

## Development

Here's how to work on your project:

- Type `npm run dev` in the terminal to start development mode
  - This will automatically update your code as you make changes
- Type `npm run build` to create the final version of your code
- Type `npm run clean` to remove any old compiled files

## Cursor IDE Features

This project comes with pre-configured AI assistance for:
- Building websites (Next.js, React, TypeScript)
- Creating servers (Node.js, MongoDB)
- Working with data
- Connecting to AI services (OpenAI, Convex)
- Writing documentation

## Main Tools Used

- **For Websites**: Next.js, React, TypeScript, Shadcn UI
- **For Servers**: Node.js, Express
- **For AI**: OpenAI, Convex
- **For Development**: Cursor IDE, GitHub

## How to Start Coding

1. Read through the documentation in the `docs` folder
2. Look at the AI rules in `.cursor/rules` to see how they can help
3. Follow the setup steps above
4. Start writing code with AI assistance in Cursor

## Want to Help?

We welcome contributions! If you have ideas to make this starter kit better, please feel free to:
1. Fork the project
2. Make your changes
3. Submit a pull request

## License

This project is free to use under the MIT License - see the LICENSE file for details. 