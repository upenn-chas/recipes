# Drupal Recipe Cookbook 2025

# Composer Notes, Required Modules
[Per recipe_author_guide.md](https://git.drupalcode.org/project/distributions_recipes/-/blob/1.0.x/docs/recipe_author_guide.md)
"Any field storage that's applicable to multiple content types goes in its own recipe."

Syntax for using Terminus with Recipes on Pantheon
```
 terminus drush -- recipe ../vendor/upenn-chas/drupal-recipe-cookbook/ingredients/profile/position  
```

# User Profile Fields:

- Primary Community (Taxonomy Reference to Communities)
- Position Title
- Roles
- Subscriptions

# ContentTypes:

- TID Technical Info Doc
- Transaction
- Resource
- Subscription List
- Shift
- General Event

# Taxonomy:

- Community (primary reference Taxonomy)
- Community_Access (access control for Community) 

# Feeds Imports:

- Communities
- Locations
- Resources
- Roles
- Groups
- Schedules
- Events

# Workflows: 

-  Taxonomy Access Validation - ECA
-  Resource Access Validation - ECA

# Views:

- By Position Reporting
- By Role, Community Reporting
- Calendar Context URL Path Filter
- By Resouce, Request Calendar
- By Transaction (Moderation)
