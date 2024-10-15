## Environment Variables
* `process.env` 
* Lets us store dynamic values for things like database name
* Can be defined at workflow, job, or step level
* Can be used in code and in the GitHub Actions workflow
* Accessible via interpolation and the `env` context object


## Secrets
* Same dynamic values, but should not be exposed anywhere
* Example: database credentials, API keys, etc.
* Secrets can be store on repository-level or via GitHub Environments
* Secrets can be references via the `secrets` context object.