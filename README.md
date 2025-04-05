# Vibe Code Fresh Start

A simple starting point for building AI-powered projects. This template helps you plan and organize your project before diving into code.

## What's This For?

This repository helps you:
- Plan your project properly before coding
- Keep your documentation organized
- Work efficiently with AI tools
- Follow best practices from the start

## What's Included

### 📝 Documentation Templates
The `docs` folder contains templates to help you plan your project:
- Product Requirements - What are you building and why?
- User Requirements - Who will use it and how?
- Software Requirements - How should it be built?

### 🤖 AI Assistant Rules
The `.cursor` folder contains guidelines that help AI tools understand:
- How to help with your specific type of project
- Best practices to follow
- Common patterns and solutions

## How to Use This Template

1. **Start with Planning**
   - Use the templates in `docs` to write down your project ideas
   - Take time to think through what you want to build
   - Plan out who will use it and how
   - Fill out your project requirements in the documentation files

2. **Set Up Project Documentation**
   - Complete the Product Requirements Document (what you're building)
   - Write the User Requirements Document (who will use it)
   - Create the Software Requirements Specification (how to build it)
   - Set the project docs rule to "always" in `.cursor/rules/use-project-docs.mdc`

3. **Configure AI Assistance**
   - Look through the `.cursor/rules` to understand how AI can help
   - Customize these rules for your specific needs
   - Add new rules as your project grows

4. **Begin Building**
   - Once you have a clear plan, start building your project
   - Use the AI assistance to help guide you
   - Keep your documentation updated as you progress

## Project Structure

```
.
├── docs/                                    # Your project planning docs
│   ├── 00-project-setup-prompts.md         # Initial setup guidelines
│   ├── 01-product-requirements-document.md  # What you're building
│   ├── 02-user-requirements-document.md     # Who will use it
│   └── 03-software-requirements-specification.md  # How to build it
│
├── .cursor/                                 # AI assistant rules
│   └── rules/                              # Different types of rules
│       ├── backend/                        # Backend development rules
│       ├── frontend/                       # Frontend development rules
│       ├── specialized/                    # Special task rules
│       └── use-project-docs.mdc            # Project documentation rules
│
└── [your project folders]                   # Where you'll add your code
```

## Contributing

Have ideas to make this template better? We'd love your help! Feel free to:
- Suggest improvements
- Share your experience
- Submit changes

## License

This project is available under the MIT License - use it freely for your own projects! 