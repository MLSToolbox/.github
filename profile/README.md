# MLSToolbox
Repository with general information about MLSToolbox. The aim of MLSToolbox is to provide a set of tools to support the development of Machine Learning Systems (MLS).

# Documentation

You can find all the information you need in our [WIKI!](https://github.com/MLS-Toobox/mls_toolbox/wiki).

# Components

| Repository | Name | Description |
| ---| ---- | ----------- |
| [mls_toolbox_client](https://github.com/MLS-Toobox/mls_toolbox_client) | MLSToolbox editor client | An Angular-based component for displaying the graphical interface and for requesting the services provided by the MLSToolbox tools|
| [mls_toolbox_server](https://github.com/MLS-Toobox/mls_toolbox_server) | MLSToolbox editor server | A Flask-based component for redirecting the mls_toolbox_client requests to the services provided by the MLSToolbox tools |
| [mls_code_generator](https://github.com/MLS-Toobox/mls_code_generator) | MLS Pipeline code generator | A Python component for mainly generating Python code for the ML pipelines represented in the editor |
| [mls_lib](https://github.com/MLS-Toobox/mls_lib) | MLS Library | A Python library containing object classes, used in the generated code, representing the structure and the main concepts required to instantiate any pipeline, its stages and the tasks that these stages perform |
| [mls_code_assessment](https://github.com/MLS-Toobox/mls_code_assessment) | MLSToolbox editor server | A Python component for assessing the quality of Python ML pipelines manually implemented |

# Contributing
See the MLSToolbox Contribution Guidelines [here](https://github.com/MLS-Toobox/mls_toolbox/blob/main/CONTRIBUTING.md).
