# Updating The Site

## Triggering the update

The site is updated through the use of a GitHub action that triggers on a push to the `main` brach with a tag that looks like `v1.0.0` This is a way of versioning the site and should follow the [Semantic Versioning](https://semver.org/) standard. This will trigger the action to run and update the site.

## Updating the SOP folder

The SOP folder is a submodule and can simply be updated through the use of `git submodule update --remote`. This will update the submodule to the latest commit on the `main` branch of the SOP repository. You can also use VSCode to update the submodule by opening the site's repository. This will not trigger the site update.

## Updating the site style

The site uses a customized Just the Docs theme that is stored in a separate repository [located here](github.com/sci-Fi-Fantasy-Alliance/just-the-docs) and is used when the site is published. To update the site style you will need to edit and update the theme repository and then trigger the site repository to update with a new version.
