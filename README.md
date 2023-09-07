# How To Use

1. Clone this repository

2. Configure config.toml file inside /config folder and change this value:
```
  url = "https://git.example.com"
  token = "<REPLACE_WITH_YOUR_GITLAB_RUNNER_REGISTRATION_TOKEN>"
```
Or you can just modify the configuration

3. Bring up docker compose file '''docker compose -d```
4. You can either just using single runner or concurrent runner using custom config.toml
