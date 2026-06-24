drupal-quick is a Composer-based scaffolding tool for Drupal. Point it at a config.dq.yml file and it provisions a site, generates a themed front-end, and applies recipes — from a blank DDEV install to a deployable static site in a single command.

The repose available are:

- drupal-quick — the Composer package. Contains the dq-init, dq-install, and drush dq:scaffold / dq:static / dq:cleanup commands, the recipe registry, and all documentation.
- dq-starterkit — a drupal-theme starterkit. Tailwind CSS v4 + Vite build pipeline with bundled design skins. dq:scaffold generates a real theme from it; it is not used directly.
- recipe-* — standalone drupal-recipe packages (recipe-blog, recipe-project). Each recipe adds a content type, views, and theme assets that dq:scaffold injects into the generated theme.
