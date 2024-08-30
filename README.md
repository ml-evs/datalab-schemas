# datalab-schema

Core schemas for datalab.

## Website

[https://datalab-org.github.io/datalab-schema](https://datalab-org.github.io/datalab-schema)

## Repository Structure

* [examples/](examples/) - example data
* [project/](project/) - project files (do not edit these)
* [src/](src/) - source files (edit these)
  * [datalab_schema](src/datalab_schema)
    * [schema](src/datalab_schema/schema) -- LinkML schema
      (edit this)
    * [datamodel](src/datalab_schema/datamodel) -- generated
      Python datamodel
* [tests/](tests/) - Python tests

## Developer Documentation

<details>
Use the `make` command to generate project artefacts:

* `make all`: make everything
* `make deploy`: deploys site
</details>

## Credits

This project was made with
[linkml-project-cookiecutter](https://github.com/linkml/linkml-project-cookiecutter).
