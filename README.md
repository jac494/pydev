# pydev.sh

Shell script to add some repeatability across my different projects for creating python virtual environments and installing packages via requirements.txt

Usage:

1. Copy into a project directory (I typically create a `dev` subdirectory in the root of my project and place this file there)
2. Source this file: `source pydev.sh`

_Alternatively, a venv name can be passed in as the first command-line argument:_

```sh
source pydev.sh alt_venv_name
```
