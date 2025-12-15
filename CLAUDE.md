# full-stack-application-management_f4559a67

## Project Overview

<a href="https://github.com/fastapi/full-stack-fastapi-template/actions?query=workflow%3A%22Test+Docker+Compose%22" target="_blank"><img src="https://github.com/fastapi/full-stack-fastapi-template/workflows/Test%20Docker%20Compose/badge.svg" alt="Test Docker Compose"></a> <a href="https://github.com/fastapi/full-stack-fastapi-template/actions?query=workflow%3A%22Test+Backend%22" target="_blank"><img src="https://github.com/fastapi/full-stack-fastapi-template/workflows/Test%20Backend/badge.svg" a

## Tech Stack

- **TypeScript**: 76%
- **Python**: 24%


## Project Structure

```
📄 LICENSE
📄 README.md
📄 SECURITY.md
📁 backend
  📄 Dockerfile
  📄 README.md
  📄 alembic.ini
📄 copier.yml
📄 deployment.md
📄 development.md
📄 docker-compose.override.yml
📄 docker-compose.traefik.yml
📄 docker-compose.yml
📁 frontend
  📄 Dockerfile
📁 hooks
  📄 post_gen_project.py
📁 img
  📄 dashboard-dark.png
  📄 dashboard-items.png
  📄 dashboard.png
  📄 docs.png
  📄 github-social-preview.png
📄 release-notes.md
📁 scripts
  📄 build-push.sh
  📄 build.sh
  📄 deploy.sh
  📄 generate-client.sh
  📄 test-local.sh
```

## Development Commands

```bash
# Install dependencies
poetry install  # or: pip install -r requirements.txt

# Run tests
pytest

# Format code
black . && ruff check --fix .
```

## Key Patterns & Conventions

- Follow PEP 8 style guidelines
- Use type hints for function signatures
- Prefer dataclasses for data structures
- Use strict TypeScript configuration
- Prefer interfaces over type aliases for object shapes
- Use functional components with hooks for React

## Important Context for AI Agents

When working with this codebase:

- Total files: 198
- Total lines: 12348
- Primary language: TypeScript

### Do's
- Read relevant source files before making changes
- Follow existing code patterns and conventions
- Write tests for new functionality
- Keep commits atomic and well-described

### Don'ts
- Don't introduce new dependencies without discussion
- Don't change formatting/style unless specifically requested
- Don't remove existing functionality without confirmation
