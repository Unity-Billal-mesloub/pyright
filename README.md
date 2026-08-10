![Pyright](https://github.com/Unity-Billal-mesloub/pyright/blob/main/docs/img/PyrightLarge.png)

# Static Type Checker for Python

Pyright is a full-featured, standards-based static type checker for Python. It is designed for high performance and can be used with large Python source bases.

Pyright includes both a [command-line tool](https://microsoft.github.io/pyright/#/command-line) and an [extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-pyright.pyright).


## Pyright Playground

Try Pyright in your browser using the [Pyright Playground](https://pyright-play.net/?code=MQAgKgFglgziMEMC2AHANgUxAEw0g9gHYwAuATgiRnBPgO4gDG%2BSBhIGZZ%2BZcjC7AEZZcVRlWzwSlKPzRoAniEFKUCslADmEEgDoAUPtwAzEAmzYAFAA8AXCGNp8lADQgF9x85IBKW-pBAkDIMEgBXMnZrEABqd0NQAAUEGBgoQk0zKTIQdNIBRiwUkBIILBgMZkJJBDJNMKQMQhJg6jC0Ejh0rLIw5qhGjmtClBIoIgNzKwBGNwAiOZ99IA).


## Documentation

Refer to [the documentation](https://microsoft.github.io/pyright) for installation, configuration, and usage details.


## Environment variables

If Pyright fails to create a temporary directory (for example in remote/server environments where the OS temp directory doesn't exist or isn't writable), you can override the temp directory root:

- `PYRIGHT_TMPDIR`: Absolute path to a directory that Pyright can use for temporary files/directories. Pyright will create it if needed.

Pyright otherwise relies on the platform temp directory (for example `TMPDIR`, `TMP`, `TEMP`, or the OS default).


## Community
Do you have questions about Pyright or Python type annotations in general? Post your questions in [the discussion section](https://github.com/Unity-Billal-mesloub/pyright/discussions).

If you would like to report a bug or request an enhancement, file a new issue in either the [pyright](https://github.com/Unity-Billal-mesloub/pyright/issues) or [pylance-release](https://github.com/Unity-Billal-mesloub/pylance-release/issues) issue tracker. In general, core type checking functionality is associated with Pyright while language service functionality is associated with Pylance, but the same contributors monitor both repos. For best results, provide the information requested in the issue template.


