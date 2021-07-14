# check_spheres
The repository manages the spheres that check uses for militarizing, make a pull request to update the alliances for the community.

## Contributing

To contribute you can just make a pull request updating the alliance ids or adding or removing blocs. It must be approved to be used, and once it is, it will reflect inside the check application. Please only make changes you know are truthful and any changes you do make will be fact-checked.

## Format

The spheres.json file is a JSON config that has the following structure:

```json
[
  {
    "name": "Name of the sphere",
    "alliances": [
      0000,
      0001,
      0002
    ]
  }
]

```

That is an array of spheres, each with a name and a list of alliance ids.

*If you modify it make sure you are using valid JSON*
