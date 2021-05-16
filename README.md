# drupaleasy-d9install

## DrupalEasy Drupal 9 install profile

This is a basic Drupal 9 install profile that demonstrates the basic functionality of an install profile.

This project is from the "Installation profiles" lesson of Drupal Career Online, as 12-week, 3x/week Drupal 
training course. More info at https://www.drupaleasy.com/dco

### Usage

1. Download the installation profile and place in your project root.

2. Add the following to the "repositories" section of your project's composer.json file:

```
        {
            "type": "path",
            "url": "drupaleasy-d9install"
        }
```

Note: Be sure to use composer validate to confirm your syntax is correct.

3. Add the ultimike/drupaleasy-d9install dependency to your project: using `composer require ultimike/drupaleasy-d9install:"dev-master"`

4. Run the Drupal installer, selecting the "DrupalEasy Drupal 9 install profile".
