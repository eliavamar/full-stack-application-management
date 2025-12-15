# AGENTS.md

This file provides guidance for AI coding agents working on full-stack-application-management_4211f0b2.

## Dev Environment Tips

- Use `poetry install` to set up the Python environment
- Activate the virtual environment before running commands
- Use `poetry run <command>` to run commands in the virtual environment
- Run `npm install` or `yarn install` to install dependencies
- Use `npm run dev` to start the development server
- Check `package.json` for available scripts

## Testing Instructions

- Run `pytest` to execute all tests
- Use `pytest -v` for verbose output
- Use `pytest path/to/test_file.py::test_name` to run specific tests
- Check `.github/workflows` for CI configuration
- Fix any test or type errors before committing
- Add tests for new functionality you implement

## PR Instructions

- Title format: `[full-stack-application-management_4211f0b2] <descriptive title>`
- Always run linting and tests before committing
- Keep commits atomic and well-described
- Reference related issues in the PR description
- Request review from appropriate maintainers

## Code Style

- Follow PEP 8 style guidelines
- Use type hints for function parameters and return values
- Run `black .` and `ruff check --fix .` before committing
- Follow TypeScript strict mode guidelines
- Use ESLint and Prettier for formatting
- Prefer `interface` over `type` for object shapes

## Important Files

- `README.md` - Project documentation and setup instructions
- `pyproject.toml` - Python project configuration
- `tests/` - Test files
- `package.json` - Node.js dependencies and scripts
- `tsconfig.json` - TypeScript configuration
- `.github/workflows/` - CI/CD configuration
