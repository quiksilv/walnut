# walnut

Three workflow files:

* build

Builds and tests the backend FastAPI and frontend vuejs. Only when tests pass then stage will run.

* stage

Deploys code to a staging server. Code is still under review in dev branch. When dev branch is merged with main then it will trigger a review.

* deploy

Deploys code to the production server only when the code passes review. Also deploys vuejs code to Cloudflare pages.
