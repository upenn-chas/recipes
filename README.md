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
- [Mailing List](https://github.com/upenn-chas/recipes/blob/main/ingredients/taxonomy/community/recipe.yml)
  - Mailing List (Reference: Mailing List Taxonomy)
  - Subscription Header field_subscription_header
  - Subscriber Additions field_subscriber_additions
  - Subscription Footer field_subscription_footer
  - List Email field_list_email
  - Remote URL field_remote_url
- Shift
- General Event

## fields
 - [banner_landscape](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/banner_landscape/recipe.yml)
 - [banner_portrait](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/banner_portrait/recipe.yml)
 - [community_logo_icon](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/community_logo_icon/recipe.yml)
 - [community_logo_text](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/community_logo_text/recipe.yml)
 - [community_type](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/community_type/recipe.yml)
 - [highlight_color](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/highlight_color/recipe.yml)
 - [short_name](https://github.com/upenn-chas/recipes/blob/main/ingredients/fields/short_name/recipe.yml)

## profile
 - [8digit](https://github.com/upenn-chas/recipes/blob/main/ingredients/profile/8digit/recipe.yml)
 - [id_key](https://github.com/upenn-chas/recipes/blob/main/ingredients/profile/id_key/recipe.yml)
 - [mailing_list_sender](https://github.com/upenn-chas/recipes/blob/main/ingredients/profile/mailing_list_sender/recipe.yml) - TODO
 - [mailing_list_subscriber](https://github.com/upenn-chas/recipes/blob/main/ingredients/profile/mailing_list_subscriber/recipe.yml) - TODO
 - [position](https://github.com/upenn-chas/recipes/blob/main/ingredients/profile/position/recipe.yml)
 - [primary_community](https://github.com/upenn-chas/recipes/blob/main/ingredients/profile/primary_community/recipe.yml)

## roles:

Roles can be managed through a series of Drush shell scripts.

## taxonomy
 - [community](https://github.com/upenn-chas/recipes/blob/main/ingredients/taxonomy/community/recipe.yml)
  -- [pathauto](https://github.com/upenn-chas/recipes/blob/main/ingredients/taxonomy/community/config/pathauto.pattern.community_taxonomy.yml)
 - [community_type](https://github.com/upenn-chas/recipes/blob/main/ingredients/taxonomy/community_type/recipe.yml)
 - [mailing_list](https://github.com/upenn-chas/recipes/blob/main/ingredients/taxonomy/mailing_list/recipe.yml)

## feeds
- [community](https://github.com/upenn-chas/recipes/blob/main/ingredients/feeds/community/recipe.yml)
- [community_type](https://github.com/upenn-chas/recipes/blob/main/ingredients/feeds/community_type/recipe.yml)
- [mailing_list_migration](https://github.com/upenn-chas/recipes/blob/main/ingredients/feeds/mailing_list_migration/recipe.yml)

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
