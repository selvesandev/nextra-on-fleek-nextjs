# Nextra Docs Template 

This is a template for creating documentation with [Nextra](https://nextra.site).

[**Live Demo →**](https://old-russia-early.functions.on-fleek.app/)

[![](.github/screenshot.png)](https://old-russia-early.functions.on-fleek.app/)


## Local Development

First, run `pnpm i` to install the dependencies.

Then, run `pnpm dev` to start the development server and visit localhost:3000.

# Deployment on Fleek

Get a PAT (Personal Access Token). Run `fleek PAT create`, give it a name, login in to the platform, and copy your PAT.

Then run `export FLEEK_TOKEN=<your personal access token>` in your terminal to set your environment variables.


Then create a project ID. Run `fleek projects create`, give it a name, and copy your ID.

Then create a `fleek.json` file. Paste this in:

```console
{
    "FLEEK_PROJECT_ID": "<project_id>"
}
```

Then run `fleek-next deploy`

## License

This project is licensed under the MIT License.
