# terminal-scripts
A collection of terminal scripts to carry out tasks I do often

## Installation
Simply clone this repo and the scripts should all be available. The repo
contains a [`modules.sh`](modules.sh) which defines a variable listing all the
different modules, it is therefore possible to add them all to your `PATH`
variable throgh

```bash
dir=...

source ${dir}/modules.sh

for module in ${SCRIPT_MODULES[@]}; do
  export PATH="${PATH}:${dir}/${module}"
done
```
