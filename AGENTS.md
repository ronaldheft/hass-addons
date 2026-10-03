# Agent guidance

This repository is a Home Assistant add-on repository. `repository.yml` defines its repository metadata; the current add-on is `xfinity-data-usage/`, with its build and configuration metadata beside the Dockerfile. Read the affected add-on's files before changing its build or options.

No test suite, build script, or CI workflow is tracked. For YAML metadata changes, validate the edited YAML with an available local YAML parser. For image or add-on behavior changes, describe the missing local validation when the required builder is unavailable; do not substitute a deployment to a Home Assistant instance. Keep runtime configuration and credentials out of source examples.
