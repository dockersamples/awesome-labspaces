# Contributing

If you have created a Labspace and want to the list, we'd love to add it!

## Listing requirements

The following requirements are in place to ensure listed Labspaces are relevant to the community:

1. Both the published Labspace (Compose file) and the source content must be available in publicly available repositories/registries

    - Acceptable: a public GitHub content repo publishes its Compose file to a public repo on Docker Hub
    - Acceptable: a public GitHub content repo publishes its Compose file to a public repo on GHCR (GitHub Container Registry)
    - Unacceptable: a private GitHub content repo publishes its Compose file to a private repo on Docker Hub
    - Unacceptable: a private GitLab content repo publishes its Compose file to a public repo

2. Content must be generally useful and not specific to a particular business or organization

    - Acceptable: a Labspace focused on the project created by a specific company or organization
    - Unacceptable: a Labspace focused on how development is to be completed within a specific company or organization

3. The content must be oriented on training and education of tech-related topics

    - Acceptable: Teaching about Docker and containers
    - Acceptable: Teaching about reverse proxies and other networking skills
    - Unacceptable: Teaching artwork, home improvement, or other non-technical skills

4. The published Labspace must use the Labspace infrastructure wherever possible

    - Acceptable: Using the Labspace infrastructure without modification
    - Acceptable: Swapping out the provided workspace with a customized workspace specific to the lab
    - Unacceptable: Removing the Docker Socket Proxy or other components for no apparent reason


## Process to add a listing

If you'd like to add a listing, complete the following steps:

1. Fork this repository

2. Update the `catalog.yaml` file with the listing of your Labspace

3. Submit a PR with your new entry!

From there, your listing will be evaluated per the listing requirements above.
