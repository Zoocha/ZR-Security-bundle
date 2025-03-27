# Zoocha Security Recipe Installation Guide

To install the Zoocha Security recipe, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Install the required composer dependencies by running the following command:

    ```sh
    composer require drupal/seckit drupal/metata drupal/length_indicator drupal/password_policy_history drupal/password_policy_length drupal/username_enumeration_prevention drupal/flood_control
    ```
4. Run the following command to execute the Zoocha Security recipe installation:

    ```sh
    ddev drush recipe recipes/custom/zoocha-secuirty-recipe
    ```

This command will execute the Zoocha Security recipe installation.
