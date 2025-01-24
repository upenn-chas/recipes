# Drupal Recipe Cookbook 2025

# Composer Notes, Required Modules
[Per recipe_author_guide.md](https://git.drupalcode.org/project/distributions_recipes/-/blob/1.0.x/docs/recipe_author_guide.md)
"Any field storage that's applicable to multiple content types goes in its own recipe."

Syntax for using Terminus with Recipes on Pantheon:
```
terminus drush -- recipe ../vendor/upenn-chas/drupal-recipe-cookbook/ingredients/profile/position 
terminus drush -- recipe ../vendor/upenn-chas/drupal-recipe-cookbook/ingredients/profile/id_key   
```

# User Profile Fields:

- Primary Community (Taxonomy Reference to Communities)
- [Position](https://github.com/upenn-chas/recipes/tree/main/ingredients/profile/position) A Position field for User Profiles.
- [ID Key](https://github.com/upenn-chas/recipes/tree/main/ingredients/profile/id_key) A text ID for User Profiles.
- [8 Digit](https://github.com/upenn-chas/recipes/tree/main/ingredients/profile/8digit) An 8 digit account key for User Profile field subscriptions.
- Subscriptions

# Roles:

# ContentTypes:

- TID Technical Info Doc
- Transaction
- Resource
- [Mailing List](https://github.com/upenn-chas/recipes/tree/main/ingredients/content_types/mailing_list)
  - Subscription Header field_subscription_header
  - Subscriber Additions field_subscriber_additions
  - Subscription Footer field_subscription_footer
  - List Email field_list_email
  - Remote URL field_remote_url
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
