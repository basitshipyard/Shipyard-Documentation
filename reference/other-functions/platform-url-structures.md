# Platform URL Structures

## Definition

All URLs within Shipyard follow a consistent format that's built on internal IDs and names. When used in combination with the [Platform Environment Variables](platform-environment-variables.md), this can be a useful way to link a user directly to an area of the platform that you want them to view, edit, or run manually.

The below is a list of the most common URL structures that may be needed.

| Purpose | URL Structure |
| :--- | :--- |
| View All Projects | https://app.shipyardapp.com/{org\_name}/projects |
| View all Blueprints | https://app.shipyardapp.com/{org\_name}/blueprints |
| View a Single Blueprint | https://app.shipyardapp.com/{org\_name}/blueprints/{blueprint\_id}/vessels |
| View Vessels in Single Project | https://app.shipyardapp.com/{org\_name}/projects/{project\_id}/vessels |
| View Fleets for a Single Project | https://app.shipyardapp.com/{org\_name}/projects/{project\_id}/fleets |
| View Logs for a Single Vessel | https://app.shipyardapp.com/{org\_name}/projects/{project\_id}/vessels/{vessel\_id}/logs |
| View Single Log for a Vessel | https://app.shipyardapp.com/{org\_name}/projects/{project\_id}/vessels/{vessel\_id}/logs/{log\_id} |


