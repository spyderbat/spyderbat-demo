# spyderbat-demo<!-- markdownlint-disable-next-line -->
# <img src="https://avatars.githubusercontent.com/u/62435726" alt="Spyderbat logo" width="30"> Spyderbat Linux Demo

This page describes how to install the Spyderbat demo for Linux systems (VM or bare metal).

It assumes that you've already created and logged into a free Spyderbat account.  If not,
do that first (instructions can be found [here](./README.md#prereq)).


## You'll Need a Linux System

Spyderbat provides runtime security for all types of Linux systems. To
continue, you'll need a Linux system that you want to protect.  It can be
bare metal or a VM.  It's works on most modern Linux kernels.

It doesn't work in Windows subsystems for Linux (WSL), Mac OS, or
FreeBSD, because they don't support EBPF, which Spyderbat uses under
the hood.

The complete list of supported systems can be found
[here](https://docs.spyderbat.com/everything-about-nano-agent/about-the-spyderbat-nano-agent).

If you don't have a Linux system handy, you have a couple of options. You
can create a Linux VM in the free tier at AWS, or you can set one up for
for a few bucks at [Digital Ocean](https://cloud.digitalocean.com/login) or
[Linode](https://www.linode.com/), among others.
You don't need a particularly large system to run the demo. A good size is one CPU core and 2 GB of
RAM, although we've successfully installed it on systems as small as a Raspberry Pi.

- [Instructions for AWS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
We recommend using a t2.micro Ubuntu 22.04 LTS or Amazon Linux 2, but the choice is up to you.

- [Instructions for Linode](https://www.linode.com/docs/products/compute/compute-instances/guides/create/)
We recommend using a Linode 2 with Ubuntu 22.04 LTS, but the choice is up to you.

- [Instructions for Digital Ocean](https://docs.digitalocean.com/products/droplets/how-to/create/)
We recommend using the Ubuntu 22.04 LTS and 2 GB/1 CPU configuration, but the choice is up to you.

Alternatively, you can use Azure, Google Cloud Compute, or the desktop CPU that's been lying in your closet
for 7 years (you'll still need t use a supported OS!).

