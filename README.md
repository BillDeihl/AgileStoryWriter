# AgileStoryWriter - Creates Agile User Stories from Templates

## Project Overview

This open-source Python project aims to provide a simple and intuitive user interface for creating and managing Agile user stories. By offering a selection of customizable templates, this tool helps teams in defining clear and effective user stories for various scenarios, ranging from persona-driven to technical requirements.

### Key Features:
- **Template Selection**: Users can choose from several user story templates, including Role-Feature-Reason, Persona-Driven, Job Stories, and Technical Stories.
- **Data Storage**: Stories are stored locally, using dataframes for session persistence and JSON for long-term storage.
- **Export Functionality**: Ability to export stories to CSV format for easy import into tools like Jira.

### Intended Users
This tool is ideal for Agile teams, product owners, scrum masters, and anyone involved in software development or project management who seeks to streamline their story-writing process.

## User Story Templates

1. **Role-Feature-Reason Template**
   - Title: [Short description]
   - As a [Role],
   - I want [Feature],
   - So that [Reason].

2. **Persona-Driven Story Template**
   - Title: [Short description]
   - For [Persona Name],
   - Who [Persona description],
   - The [Feature],
   - Is a [Type of feature],
   - That [Key benefit].

3. **Job Story Template**
   - When [Situation],
   - I want to [Motivation],
   - So I can [Outcome].

4. **Technical Story Template**
   - Title: [Technical Task]
   - In order to [Technical goal],
   - As a [Development team],
   - I want [Technical task or feature].

### Data Normalization
The templates are stored in a normalized format, allowing for easy modification and extension.

## How to Contribute
We welcome contributions from the community! Whether it's adding new features, improving the UI, or suggesting new templates, your input is valuable.

### Contribution Guidelines
- **Fork the Repository**: Start by forking the repository and making your changes.
- **Follow Coding Standards**: Ensure your code adheres to the project's coding standards.
- **Write Clear Commit Messages**: Describe your changes clearly in your commit messages.
- **Pull Request**: Submit a pull request with a clear description of your changes.

## License
This project is free to use under the MIT License.

## Getting Started
Instructions on setting up the project locally, running the application, and using the UI will be provided here.
