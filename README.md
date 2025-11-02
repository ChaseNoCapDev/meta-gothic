# Meta Gothic Framework

A comprehensive AI-guided TypeScript development framework with modular architecture.

## Overview

The Meta Gothic Framework is a collection of interconnected packages designed to facilitate AI-guided software development, with a focus on SDLC automation, Claude integration, and intelligent development tooling.

## Modules

This repository uses Git submodules to manage its various packages:

### Core Infrastructure
- **claude-client** - Claude CLI subprocess wrapper and session management
- **event-system** - Event-driven architecture and pub/sub messaging
- **file-system** - File system abstraction and utilities
- **logger** - Structured logging with Winston

### GraphQL & API
- **graphql-toolkit** - GraphQL utilities, DataLoader, and schema composition
- **github-graphql-client** - GitHub GraphQL API client with rate limiting and caching

### AI & Context Management
- **context-aggregator** - Intelligent context loading and optimization for AI
- **prompt-toolkit** - XML-based prompt templating system

### SDLC
- **sdlc-config** - YAML-based SDLC configuration management
- **sdlc-content** - Templates and knowledge base for SDLC phases
- **sdlc-engine** - State machine for SDLC workflow execution

### UI
- **ui-components** - React dashboard for monitoring and controlling the framework

### Framework
- **meta-gothic-framework** - Main framework integrating all modules

## Getting Started

### Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/ChaseNoCapDev/meta-gothic
cd meta-gothic
```

### Initialize Submodules (if already cloned)

```bash
git submodule update --init --recursive
```

### Update All Submodules

```bash
git submodule update --recursive --remote
```

## Development

Each module is independently versioned and maintained in its own repository. See individual module READMEs for specific development instructions.

## Architecture

The Meta Gothic Framework follows a modular architecture where each package has a clear responsibility and can be used independently or as part of the larger framework.

## License

MIT
