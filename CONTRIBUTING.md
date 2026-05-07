# Contributing to the HCU-Vex Depot

Anyone can submit their VEXcode V5 C++ library to the official depot. Once added, teams can install your library by name:

```bash
vpm install your-library
```

## Requirements

Before submitting your library must:

- Be a public GitHub repository
- Use the [vpm-template](https://github.com/HCU-Vex/vpm-template) structure
- Have at least one tagged release (e.g. `v1.0.0`)
- Include a `vpm.json` at the root with `name`, `version`, `description`, and `author`
- Be written for VEXcode V5 C++

## How to Submit

1. Fork this repository
2. Add your library to `depot.json`:

```json
{
  "your-library": {
    "repo": "your-username/your-repo",
    "description": "A short description of your library"
  }
}
```

3. Open a pull request with the title `Add your-library`

Your library will be reviewed and merged as long as it meets the requirements above.

## Need Help?

Use the [vpm-template](https://github.com/HCU-Vex/vpm-template) to get started building a vpm-compatible library.
