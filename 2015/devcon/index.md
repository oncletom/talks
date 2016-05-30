---
title: Rethinking applications design with Docker
language: en-GB
layout: slides/bbcrd.hbs
event:
  name: EBU DevCon
  location: Geneva
  duration: 25
  date: 2015-10-07
  url: https://tech.ebu.ch/events/devcon15
video:
slides:
  - file: title.md
  - file: ../../about-me.md
  - file: intro-photographs.md
  - file: 01-use-case-php.md
  - file: 02-provisioning.md
  - file: 03-lxc.md
  - file: 04-docker.md
  - file: 05-single-component.md
  - file: 06-standard-streams.md
  - file: 07-orchestrated-components.md
  - file: 08-continuous-integration.md
  - file: 09-other-purposes.md
  - file: 10-best-practices.md
  - file: conclusion.md
  - file: thank-you.md
---

Docker has shaken the software world by making LXC a commodity. Now
that the universal runtime container runC is born, what is its impact on
us, developers?

We will investigate what Docker really is, how to think in term of layers
and containers, and what are the key best practice in term of design and
security. [Demonstrator can be found on GitHub](https://github.com/oncletom/devcon-2015-docker-demonstrator).