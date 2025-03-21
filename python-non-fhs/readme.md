## Non-FHS Python
This flake,
- establishes a non-FHS environment for Python3
- support for compilation, wheels, and pre-commit
- activates virtual-environment upon load

### Notes
To extract the flake as a reusable dev environment on Github,
- use ```nix develop github:yourname/dev-flakes/v1?dir=python-non-fhs```