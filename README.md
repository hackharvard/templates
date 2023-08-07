# mail

These are `mjml` templates for HackHarvard Firebase emails. Use the VS Code MJML extension for exporting to `html`. The bracketed variables are using Handlebars syntax.

| Name                    | Input                                                                |
| ----------------------- | -------------------------------------------------------------------- |
| `application-submitted` | `[app.name, app.link]`                                               |
| `action`                | `[app.name, app.link, action.name, action.link, action.description]` |
