# The Snakemake-Workflows project

The Snakemake-workflows project is a joint effort to create workflows for common use cases of the [Snakemake workflow management system](https://snakemake.bitbucket.io). Snakemake-workflows has just started, and we are still in the phase to determine policies and best practices.


## Workflows

A list of all available workflows that are currently in development can be found [here](https://github.com/snakemake-workflows).

### Approved workflows

The following workflows have undergone a strict review and quality control process and are ready for production.

| Workflow | Domain | Authors |
| -------- | ------ | ------- |


## Documentation

### Join the team

Once the initiators have agreed on the procedure, it will be possible to join the team here.

### Contribute

Contributing is easy:

1. Join the team
2. Create a new repository for your workflow
3. Ensure that your workflow meets our guidelines.
3. Request a review [here]().

### Guidelines

1. A workflow repository shall consist of one Snakemake workflow.
2. The structure of the workflow should follow our [skeleton](https://github.com/snakemake-workflows/cookiecutter-snakemake-workflow).
3. Whenever possible, [Snakemake wrappers](https://snakemake-wrappers.readthedocs.io) should be used.
4. The workflow should be configurable via a well documented YAML-based configuration file and (when necessary) a sample sheet.
5. The workflow has to define an (integration-style) test case that is configured via the `.travis.yml` file in the skeleton.
