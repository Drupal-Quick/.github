Drupal-Quick is a Composer-based scaffolding tool for Drupal. Point it at a config.dq.yml file and it provisions a site, generates a themed front-end, and applies recipes — from a blank DDEV install to a deployed static site in a few commands. See our [workflow docs](https://github.com/Drupal-Quick/drupal-quick/blob/main/docs/workflow.md).

Drupal-Quick even removes all references to itself and provides a blank slate for continued development

The repose available are:

- drupal-quick — the Composer package, drush commands, and documentation.
- dq-starterkit — a drupal-theme starterkit. Tailwind CSS v4 + Vite build pipeline with bundled design skins.
- recipe-* — standalone drupal-recipe packages. Each recipe adds config, dependencies, and theme assets that dq:scaffold injects into the generated theme.
