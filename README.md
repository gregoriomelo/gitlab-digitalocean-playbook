### Setting up Gitlab on DigitalOcean

You need `dopy` installed: [here's how to](https://github.com/boxtape/boxtape/issues/6)

This playbook relies on Ansible < 2, as the DigitalOcean API has changed.

You need to set the following env vars:

    DO_CLIENT_ID # DigitalOcean's V1 API client id (https://cloud.digitalocean.com/generate_api_key)
    DO_API_KEY # DigitalOcean's V1 API key (https://cloud.digitalocean.com/generate_api_key)
    GITLAB_SSH_PUBLIC_KEY # The SSH key that will be deployed in the Gitlab instance
