# .github

Contains common files Github Action files

## Houston endpoints

Houston can be accessed through endpoint definitions in `shuttle.yaml`:

- `vars.houston.endpoints.modules`
- `vars.houston.endpoints.structure`
- `vars.houston.endpoints.health`

Any Shuttle plan or workflow in this repository can read these values and use them
when making endpoint-based Houston calls.
