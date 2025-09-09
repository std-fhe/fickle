# The fickle command-line utility

The fickle tool is an FHE (fully-homomorphic encryption) CLI (command-line
interface).

It provides a way to run various FHE programs on various "FHE Processors"
locally on your computer or on the network somewhere.

Since FHE is a field that is rapidly developing and involves very expensive
computation, there are numerous efforts to design and build custom hardware
accelerators. Hence, the "FHE processor" may be a CPU, GPU, TPU, FPGA, ASIC, or
even more exotic forms of hardware.

Likewise, the software libraries, SDKs, bindings, and other mechanisms for
writing FHE programs are rapidly changing.

In this ecosystem, the fickle CLI and fickle-server gRPC API provide a common
and consistent set of tools and infrastructure to easily and rapidly experiment
with FHE programs.
