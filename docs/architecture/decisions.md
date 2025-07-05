# Architecture Decision Records

## 1. Static Site Generation
- **Status**: Approved
- **Context**: Need for zero-maintenance, high-availability solution
- **Decision**: Use GitHub Pages with vanilla JS/CSS
- **Consequences**: No server-side processing, all logic must be client-side

## 2. CI/CD Pipeline
- **Status**: Implemented
- **Context**: Automated quality assurance
- **Decision**: GitHub Actions with Node.js build step
- **Consequences**: Additional setup but enables testing/linting
