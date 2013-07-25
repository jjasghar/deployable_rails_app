# Ops Exercise

## expectations
- deploy rails app [https://github.com/emadrid/deployable_rails_app.git](https://github.com/emadrid/deployable_rails_app.git)
  1. pull from git origin/master
  2. pull from arbitrary branch
- use RDS as database
- redundancy
  - kill a server and app still works
- load balanced
  - tail -f on production.log displays requests on both nodes
- config is sabotaged - you debug