# Shared Github Actions

## coding-standard.yml
This workflow is for checking the coding standards of a Magento 2 module. It runs when called by another workflow `workflow_call`.

## integration.yml
This workflow is for running integration tests on a Magento 2 module with various Magento and PHP versions.
It also runs when called by another workflow and takes two inputs `module_name` and `composer_name`.

## mess-detector.yml
This workflow is triggered by another workflows using the `workflow_call`.
It sets up the PHP Mess Detector to analyze Magento code for potential issues, helping to maintain high code quality.

## phpstan.yml
The `phpstan.yml` file sets up a GitHub Actions workflow for running PHPStan on a Magento 2 project.
PHPStan is a static analysis tool that detects potential bugs and code quality issues.

## unit.yml
This workflow is for running unit tests on a Magento 2 module with various Magento and PHP versions.
It also runs when called by another workflow and takes two inputs `module_name` and `composer_name`.
