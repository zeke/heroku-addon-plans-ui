Heroku Addon Plans UI
=====================

Check it
--------

    git clone git@github.com:zeke/heroku-addon-plans-ui.git && cd heroku-addon-plans-ui && open lib/index.html

Design Principles
-----------------

- "Don't make me think"
- Simplicity for end-users is paramount.
- Simplicity for addon providers is key, but they're more adept.
- Provide prompts to prevent failures
- Don't make addons providers write plan descriptions
- Stay DRY everywhere: UI elements, views, and data

Advantages of this UI
---------------------

- Consumers can make comparisons between plans
- The data is clean
- Plan and Feature CRUD is managed in a single interface
- Rails is just an API
- CSS3
- Data attributes
- The end-user view and the admin view are the same (inputs)

Disadvantages of this UI
------------------------

- More architecture: PlanFeature
- More front-end business