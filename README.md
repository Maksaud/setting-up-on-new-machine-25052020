# Setting up virtualbox, vagrant and other tools for my personal windows PC

## Virtualbox

VirtualBox is a general-purpose virtulisation tool for x86 and x86-64 hardware, targeted at server, desktop, and embedded use, that allows users and administrators to easily run multiple guest operating systems on a single host

Download virtualbox from:

`https://www.virtualbox.org/wiki/Downloads`

## Vagrant

Vagrant is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation.
- Vagrant lowers development environment setup time
- increases productivity parity
- makes the 'works on my machine' excuse a relic of the past.

Download Vagrant from

`https://www.vagrantup.com/`

### Windows troubleshooting

One problem I came accross was that hyper-v was disabled and after creating a virtual machine, that machine would not run.
If you come accross the same problem, you may need to:

- Enable virtualisation from your boot menu.
- Enable windows hypervisor platform and virtual machine platform. This can be done on:

```
control panel -> programs and features -> Turn windows features on or off
```

Then restart your computer.