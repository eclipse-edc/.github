# Eclipse Dataspace Components .github

This repository contains common workflows and templates for the EDC projects.

## Release

To release all the components, run the [`platform-prepare-release.yml`](./.github/workflows/platform-prepare-release.yml)
workflow to prepare the release in all the repositories.

After it finishes, [`platform-release.yml`](./.github/workflows/platform-release.yml) can be triggered, and all the 
repositories will be released in the correct order.
