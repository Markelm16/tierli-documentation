## Versioning
API used to get recent updates and check if current client version is updated.

| Attribute | Type     | Description        |  Possible values |
|-----------|----------|--------------------|------------------|
| platform  | `string` | Client's platform  | mobile           |
| version   | `string` | Client's version   |                  |

### Responses
| Response           | Description                                         |
|--------------------|-----------------------------------------------------|
| updated            | User has the newest version of the app.             |
| update_optional    | A new update is available .                         |
| update_recommended | Updating is recommended to use the latest features. |
| update_required    | User must update the app to use online features.    |
