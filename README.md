
# GuardBSD Documentation

**Project:** GuardBSD  
**Version:** 1.0.0 (Winter Saga)  
**Author:** Cartesian School - Siergej Sobolewski  
**Copyright:** 2025  
**Website:** www.guardbsd.org

## Documentation Structure

This documentation is organized into the following sections:

### 📐 Architecture
- [System Overview](architecture/overview.md) - High-level system architecture
- [µK-Space](architecture/uk-space.md) - Memory management microkernel
- [µK-Time](architecture/uk-time.md) - Scheduler and timer microkernel
- [µK-IPC](architecture/uk-ipc.md) - Inter-process communication microkernel
- [Multi-Architecture Design](architecture/multi-arch.md) - x86_64 and aarch64 support

### 🔌 API Reference
- [Syscall Reference](api/syscalls.md) - Complete syscall documentation
- [Capability System](api/capabilities.md) - Capability-based security
- [IPC Protocol](api/ipc-protocol.md) - Message passing interface

### 📚 Guides
- [Getting Started](guides/getting-started.md) - Quick start guide
- [Building GuardBSD](guides/building.md) - Build instructions
- [Development Environment](guides/dev-environment.md) - Setting up your environment
- [Testing Guide](guides/testing.md) - Running tests
- [Porting Guide](guides/porting.md) - Adding new architectures

### 📊 Diagrams
- [Project Structure](diagrams/project-structure.md) - Visual directory layout
- [Boot Sequence](diagrams/boot-sequence.md) - System initialization flow
- [Memory Layout](diagrams/memory-layout.md) - Address space organization
- [IPC Flow](diagrams/ipc-flow.md) - Message passing visualization

### 🛠️ Development
- [Coding Standards](development/coding-standards.md) - Code style and conventions
- [Git Workflow](development/git-workflow.md) - Branch and PR guidelines
- [Issue Management](development/issues.md) - GitHub Projects workflow
- [Release Process](development/release-process.md) - Version management

## Quick Links

- [Contributing Guidelines](../CONTRIBUTING.md)
- [License](../LICENSE)
- [GitHub Repository](https://github.com/cartesian-school/guardbsd)
- [Issue Tracker](https://github.com/cartesian-school/guardbsd/issues)

## Documentation Standards

All documentation follows these principles:

1. **Clarity**: Use simple, precise language
2. **Completeness**: Cover all aspects thoroughly
3. **Accuracy**: Keep in sync with code
4. **Examples**: Provide practical code examples
5. **Diagrams**: Use visual aids where helpful

## Building Documentation

Documentation is written in Markdown and can be viewed:

1. **On GitHub**: Navigate to the `docs/` directory
2. **Locally**: Use any Markdown viewer
3. **As HTML**: Generate with `mdbook` (future)

## Contributing to Documentation

See [CONTRIBUTING.md](../CONTRIBUTING.md) for guidelines on:
- Writing style
- Diagram creation
- Code examples
- Review process

## Version History

- **v1.0.0 (Winter Saga)** - Initial release documentation