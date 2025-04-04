# ZR Security Recipe Installation Guide

To install the ZR Security recipe, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Ahead of running `composer require zr/RECIPE_NAME` - ensure the below has been added to the root `composer.json` **installer-paths**
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
4. Run the following command to execute the ZR Security recipe installation:

    ```sh
    ddev drush recipe recipes/custom/ZR-security-bundle
    ```

This command will execute the ZR Security recipe installation.
