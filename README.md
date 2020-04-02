# Translations for foundation.mozilla.org

[![Build Status](https://travis-ci.org/mozilla-l10n/fomo-l10n.svg?branch=master)](https://travis-ci.org/mozilla-l10n/fomo-l10n)

Process foundation.mozilla.org's translations and upload them to S3.

## Contributing
Visit the following projects to contribute translations:
- https://pontoon.mozilla.org/projects/mozilla-foundation-website/
- https://pontoon.mozilla.org/projects/privacy-not-included/
- https://pontoon.mozilla.org/projects/mozilla-festival/

## Updating dependencies for this project
*Django's version must be the same as the foundation site.*
Use [pip-tools](https://github.com/jazzband/pip-tools) to update dependencies:
- Create a virtual-env: `python3 -m venv venv `
- Install pip-tools: `pip install pip-tools`
- Edit the `requirements.in` file
- Run `pip compile`
- Open a PR with both `requirements.in` and `requirements.txt`
