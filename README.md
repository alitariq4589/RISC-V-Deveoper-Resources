# RISC-V Software Developer's resources
This repository is created for the community to add vendor-agnostic RISC-V software resources info/list to the Cloud-V website (https://cloud-v.co) for everyone working on RISC-V. This contains operating systems for RISC-V application processors (which may or may not be discontinued by vendors), software binaries compiled from sources, etc.

The complete list of SBCs' operating system and software binary releases is stored at https://cloud-v.co/risc-v-resources.

## Contributing to the list

If you have found a new resource that you think will be great to add to the list, you are welcome to create a PR in this repository with a reference link where you found the resource and add the resource to the list. If it is an operating system, it will be added to the list after authenticating the source (because we do not want to add anything malicious). If it is a binary software application, it will be first compiled for RISC-V from the source before adding. There are two ways source code can be compiled from binary.

1. You can compile the source code on the RISC-V compute instance yourself using Cloud-V CI _(you will have to add all the required information which is described at https://cloud-v.co/contactus in your PR and I will give you access to Cloud-V CI with one RISC-V compute instance)_
2. You can provide me the source code and I will compile it on one of the RISC-V compute instances

Once the source code is successfully compiled, the PR will be merged.

_NOTE: Please comply with the table formatting_
