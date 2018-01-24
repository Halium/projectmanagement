# Halium project management

This repository tracks ports, proposals, and project-wide bugs for Halium.

## Ports

[Device ports](https://github.com/Halium/projectmanagement/labels/Ports) are tracked in this repository.

To document a device port, use the template in the PORT-TEMPLATE file.

## Bugs

Bugs in the [Halium stack](http://docs.halium.org/en/latest/Planning.html#the-stack-proposal) are also tracked in this repository.

* Android Source
  * [halium-5.1](https://github.com/Halium/projectmanagement/labels/Halium-5.1-source)
* [Reference rootfs](https://github.com/Halium/projectmanagement/labels/Halium-rootfs)
* [initramfs](https://github.com/Halium/projectmanagement/labels/Halium-Initrd)


## Proposals

[Proposals](https://github.com/Halium/projectmanagement/labels/Proposal) are also tracked in this repository.

Proposals seek to change the Halium stack in some way that will add features or fix multiple bugs. When filing a proposal please consider the following:

* Halium's product should be as distro-agnostic as possible.
* If you are proposing a change that has not yet been developed, specify who will be developing the solution.
* A change to Halium should be tested for its effect to the major distributions that support it.
  * To this end, include instructions so that others may test your proposal.
* Changes will likely affect multiple repositories. Provide links to all of your patches in your proposal.