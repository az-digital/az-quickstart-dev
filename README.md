# az-quickstart-dev

Composer `require-dev` dependencies for Arizona Quickstart projects.

## No Tagged Releases

This repository does **not** use tagged releases.  
Instead, it relies on **[Composer branch aliases](https://getcomposer.org/doc/articles/aliases.md)** defined on specific release branches (e.g., `1.x`, `3.x`).

The `main` branch can be used with Composer in one of the following ways:

```json
"az-digital/az-quickstart-dev": "3.x-dev"
```

or: 

```json
"az-digital/az-quickstart-dev": "dev-main"
```

For Arizona Quickstart 2.14.x and below, use:

```json
"az-digital/az-quickstart-dev": "1.x-dev"
```

**This package includes the following contrib development modules.**

- [Devel](https://www.drupal.org/project/devel)
- [Migrate Devel](https://www.drupal.org/project/migrate_devel)
- [Configuration Inspector](https://www.drupal.org/project/config_inspector)
- [Upgrade Status](https://www.drupal.org/project/upgrade_status)
