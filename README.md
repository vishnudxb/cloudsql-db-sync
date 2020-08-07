# cloudsql-db-sync
Sync your staging db with production

*This github action can run as a schedule job to update your cloudsql staging db with the production.*

For example:

You have two gcp projects
  - staging
  - production

Both projects run cloudsql and you want your staging db should be updated with the production.*


#### Pre-requisite

- cloudsql instance for staging and production
- service account with right permission for cloudsql and gcs
