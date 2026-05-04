# Home Assistant Add-on: Grafana v13 Fork

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

[![Community Forum][forum-shield]][forum]

Fork of the Grafana add-on v12 packaging, updated to run Grafana OSS v13.0.1.

![Grafana in the Home Assistant Frontend](images/screenshot.png)

## About

This fork keeps the Home Assistant add-on experience from the Grafana add-on v12
line while updating the bundled Grafana release to v13.0.1.

Grafana allows you to query, visualize, alert on and understand your metrics
no matter where they are stored. Create, explore, and share dashboards. Learn
about your Home Automation system using sexy and compelling graphs, and other
data visualizations.

Combine this add-on with the InfluxDB add-on to get powerful insights into your
home.

[:books: Read the full add-on documentation][docs]

## Support

Got questions?

You have several options to get them answered:

- This repository's [GitHub Issues][issue] for fork-specific support and feature
  requests.
- The [Home Assistant Discord chat server][discord-ha] for general Home
  Assistant discussions and questions.
- The Home Assistant [Community Forum][forum].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also [open an issue here][issue] GitHub.

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](.github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

The original add-on was created by [Franck Nijhof][frenck].

This fork is maintained by Sam Black. For a full list of all authors and
contributors, check [the contributor's page][contributors].

## Fork details

This repository is a fork of the upstream Home Assistant Community Grafana
add-on. It keeps the original add-on structure, updates repository metadata and
documentation for this fork, and removes the bundled image renderer plugin
because Grafana 13 supports image rendering through a separate remote renderer
service instead.

## License

MIT License

Copyright (c) 2018-2025 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/hellosamblack/addon-grafana.svg
[commits]: https://github.com/hellosamblack/addon-grafana/commits/main
[contributors]: https://github.com/hellosamblack/addon-grafana/graphs/contributors
[discord-ha]: https://discord.gg/c5DvZ4e
[docs]: https://github.com/hellosamblack/addon-grafana/blob/main/grafana/DOCS.md
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/
[frenck]: https://github.com/frenck
[github-actions-shield]: https://github.com/hellosamblack/addon-grafana/workflows/CI/badge.svg
[github-actions]: https://github.com/hellosamblack/addon-grafana/actions
[issue]: https://github.com/hellosamblack/addon-grafana/issues
[license-shield]: https://img.shields.io/github/license/hellosamblack/addon-grafana.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[releases-shield]: https://img.shields.io/github/release/hellosamblack/addon-grafana.svg
[releases]: https://github.com/hellosamblack/addon-grafana/releases
