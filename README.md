# Drupal Recipe Cookbook 2025

### Composer Notes, Required Modules
[Per recipe_author_guide.md](https://git.drupalcode.org/project/distributions_recipes/-/blob/1.0.x/docs/recipe_author_guide.md)
"Any field storage that's applicable to multiple content types goes in its own recipe."
TODO - Add Serialized CSV / Views Export Data modules to composer.json template - needed for Views recipes.

Syntax for using Terminus with Recipes on Pantheon:
```
terminus drush -- recipe ../vendor/upenn-chas/drupal-recipe-cookbook/ingredients/profile/id_key   
```

# Ingredients

## content_types
- TID Technical Info Doc
- Transaction
- Resource
- [Mailing List](https://github.com/upenn-chas/recipes/tree/main/ingredients/content_types/mailing_list)
  - Mailing List (Reference: Mailing List Taxonomy)
  - Subscription Header field_subscription_header
  - Subscriber Additions field_subscriber_additions
  - Subscription Footer field_subscription_footer
  - List Email field_list_email
  - Remote URL field_remote_url
- Shift
- General Event

## feeds
  - community
  - community_type
  - mailing_list_migration

## fields
 - banner_landscape
 - banner_portrait
 - community_logo_icon
 - community_logo_text
 - community_type
 - highlight_color
 - short_name

## profile
 - 8digit
 - id_key
 - mailing_list_sender
 - mailing_list_subscriber
 - position
 - primary_community

## roles:

Roles can be managed through a series of Drush shell scripts.

## taxonomy
 - community
 - community_type
 - mailing_list

## feeds

- Communities
- Locations
- Resources
- Mailing List Taxonomy
- Mailing List
- Schedules
- Events

## eca_models

-  Taxonomy Access Validation - ECA
-  Resource Access Validation - ECA

## views
- [community_sections](https://github.com/upenn-chas/recipes/tree/main/ingredients/views/community_sections) 
- By Position Reporting
- By Role, Community Reporting
- Calendar Context URL Path Filter
- By Resouce, Request Calendar
- By Transaction (Moderation)
