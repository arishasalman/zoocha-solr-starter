# Zoocha Solr Search Recipe Installation Guide

To install the Zoocha Solr Search Recipe, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Install the required composer dependencies by running the following command:

    ```sh
    composer require drupal/search_api_solr drupal/facets
    ```
4. Run the following command to execute the Zoocha Solr Search Recipe installation:

    ```sh
    ddev drush recipe recipes/custom/zoocha-solr-search-starter
    ```

This command will execute the Zoocha Solr Search Recipe installation.
