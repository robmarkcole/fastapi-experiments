# fastapi-experiments
Repo to try out things like devcontainers, codespaces and simple (non aws) deployment options. Want a workflow where we can develop and package using docker containers and deploy to an internet accessible with a simple deployment experience and authentication handled somehow.

### Deploy on deta
* Tryout https://fastapi.tiangolo.com/deployment/deta/ 
* Annoyingly install script does not add deta to PATH, had to export manually
* Initially receive `{"errors":["Unauthorized"]}` from browser but the API is running and can query it via deta UI
* Run `disabled http auth` then can access vi browser
* Deta also host a simple json db which could be useful

### devcontainers