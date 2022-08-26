# PicoBlaze3-examples

## Needed tools:
This repository was tested with [opbasm](https://kevinpt.github.io/opbasm/) to compile the examples and [opbsim](https://kevinpt.github.io/opbasm/rst/opbsim.html) to simulate the software on a PicoBlaze3 simulator. If installation does not work out of the box, make sure to check the open issues and merge requests of their GitHub repositories. If that does still not make things work, you can create an issue in this repository to ask for help.

## Compilation
Change the directory into the example directory and run the following command:
```shell
opbasm -3 <example-name>.psm
```

Make sure to replace `<example-name>` with the name of the example you want to compile.

## Simulation
Make sure you compiled the example before you want to execute it.
Change the directory into the example directory and run the following command:
```shell
<path-to-opbsim>/opbsim --pb3 -m:<example-name>.mem
```

Make sure to replace `<example-name>` with the name of the example you want to simulate.
Make sure to replace `<path-to-opbsim>` with the path to your opbsim executable.


