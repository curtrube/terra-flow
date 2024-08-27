# terra-flow

`terra-flow` is a GitHub actions workflow for running terraform.

## Requirements

- must support the main commands:
  - init Prepare your working directory for other commands
  - validate Check whether the configuration is valid
  - plan Show changes required by the current configuration
  - apply Create or update infrastructure
  - destroy Destroy previously-created infrastructure
- must utilize remote backend and state locking
- must support input variables
- must be able to set desired terraform version
