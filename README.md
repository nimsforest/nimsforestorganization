# NimsforestOrganization - Organizational Structure Component

Creates organizational documentation structure based on YAML configuration. Focuses on customer value chain and strategic direction with three-level hierarchy.

## Quick Setup

```bash
git submodule add https://github.com/nimsforest/nimsforestorganization.git tools/nimsforestorganization
cd tools/nimsforestorganization
make nimsforestorganization-hello
make nimsforestorganization-init
```

## Commands

```bash
make nimsforestorganization-hello    # System compatibility check
make nimsforestorganization-init     # Create docs/organization/ structure from YAML
make nimsforestorganization-lint     # Validate organization structure
```

## Structure

Defined in `organization-structure.yml` - creates three-level folder hierarchy under `docs/organization/` for systematic organizational intelligence capture.