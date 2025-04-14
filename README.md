# Chocolatine GitHub Actions Workflow
This repository contains a custom GitHub Actions workflow designed to automate essential development tasks, including coding style checks, program compilation, testing, and repository mirroring. The workflow is tailored for Epitech projects, however, some functions can be useful in the everyday life of all programmers.

# Features:
### Automated Coding Style Checks:
- Leverages the Epitech coding style checker to ensure code quality.

### Program Compilation Validation: 
- Verifies that the project compiles successfully and produces the required executables.

### Automated Testing:
- Runs project-specific unit tests to validate functionality.

### Repository Mirroring: 
- Securely mirrors the repository to an Epitech-Hosted Git repository using SSH authentication.

### Trigger Rules:
- Executes on push and pull_request events, with exclusions for specific branch patterns.

# Key Highlights:
- Fully self-contained workflow with no external dependencies beyond actions/checkout and pixta-dev/repository-mirroring-action.

- Secrets management ensures sensitive data like SSH keys are securely handled.

- Modular design with job dependencies for streamlined execution.
