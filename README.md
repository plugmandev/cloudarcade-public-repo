# CloudArcade Public Repository
A list of GitHub repository links for external plugins for CloudArcade

### Plugin Requirements
Your plugin must meet the following requirements in order to qualify to be listed:
- The GitHub repository must be public.
- The plugin must be free to use, and premium features are optional.
- The plugin must not touch or modify any original files of CloudArcade. Read the documentation: [https://docs.cloudarcade.net/developer](https://docs.cloudarcade.net/developer)
- You need official permission from the author of CloudArcade: [RedFoc](https://codecanyon.net/user/redfoc)

### Repository File Structure
Your plugin repository must follow these requirements:
- All default plugin files must be placed in the root of the repository.
- Plugin repo name must follow this format: **pluginname**-plugin-cloudarcade
- Repo structure should look like this:
  ```
  root
  ├── assets
  │   ├── css
  │   │   └── CSS Files
  │   ├── images
  │   │   └── Images
  │   └── js
  │       └── JS Files
  ├── controllers
  │   └── PHP Files
  ├── uploads
  │   └── Plugin Uploads
  ├── info.json // Plugin Information
  ├── page.php // Admin Page
  └── public.php // Public Page
  ```
