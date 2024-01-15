# spyderbat-demo<!-- markdownlint-disable-next-line -->
# <img src="https://avatars.githubusercontent.com/u/62435726" alt="Spyderbat logo" width="30"> Spyderbat Demo

## Welcome to the Spyderbat Runtime Security Demo

This repository contains the Spyderbat Runtime Security Demo; it includes
instructions, templates, examples and code to set up a Linux and/or Kubernetes
environment that demonstrates the capabilities and helps you understand the
Spyderbat runtime security platform in a near real-world environment.

Our goals are threefold:

- Provide a realistic example of a distributed system that demonstrates
  Spyderbat's security and observability capabilities (that's a lot or "-ities"!)
  We believe the best way to understand Spyderbat is to experience it, rather
  than simply reading about it or watching someone else demostrate it.
- Build a base for customers, authors, enthusiasts, and others to extend and
  demonstrate their Spyderbat integrations.
- Create a living example that can be used for testing API, SDK, and other
  components or enhancements.

If you'd like to help (**which we would love**), please join our
[Slack Community](https://spyderbatcommunity.slack.com)

*Acknowledgement: this repo was inspired by, and in some cases derived from, the
outstanding [OpenTelemetry Demo](https://github.com/open-telemetry/opentelemetry-demo)
github repository.  They did a great job, and imitation is the sincerest form of flattery,
but I wanted to acknowledge their fantastic work.*

<a id="prereq"></a>
## Prerequisites

You can be up and running with the demo in a few minutes.  The Spyderbat console itself runs in a
browser. We do all our testing with Chrome, so that's what we recommend.
The UI is designed for an HD resolution monitor or higher (1920x1280 minimum resolution).
Although you can run with lower resolution, some things won't work as well.

Spyderbat is a SaaS security platform -- we send telemetry from your monitored Linux machines
and Kubernetes clusters to the Spyderbat backend.  So in order to connect your machines with
your Spyderbat account in the backend, you'll also need a free Spyderbat account.  Simply
go to the [Spyderbat Login](https://app.spyderbat.com/login) and follow the instructions.
Once you have a verified account, continue below.

Lastly, you'll need a place to install the demo code. You can use a Linux VM, a small Kubernetes cluster,
or a combination of both.  To experience the full demo, we recommend both (which also reflects most
cloud native real world environments).

## Quick Start

Follow the the links below for your preferred deployment:

- [Linux](./Linux.md)
- [Kubernetes](./K8s.md)
- [Combined (recommended!)](./Combined.md)

