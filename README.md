<<<<<<< HEAD
# librenms



## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin http://10.5.16.40/pn360/librenms.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](http://10.5.16.40/pn360/librenms/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Set auto-merge](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing (SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thanks to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README

Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Name
Choose a self-explaining name for your project.

## Description
Let people know what your project can do specifically. Provide context and add a link to any reference visitors might be unfamiliar with. A list of Features or a Background subsection can also be added here. If there are alternatives to your project, this is a good place to list differentiating factors.

## Badges
On some READMEs, you may see small images that convey metadata, such as whether or not all the tests are passing for the project. You can use Shields to add some to your README. Many services also have instructions for adding a badge.

## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
=======
[![Test Status](https://github.com/librenms/librenms/actions/workflows/test.yml/badge.svg?branch=master&event=push)](https://github.com/librenms/librenms/actions/workflows/test.yml?query=event%3Apush+branch%3Amaster)

Introduction
------------

LibreNMS is an auto-discovering PHP/MySQL/SNMP based network monitoring
which includes support for a wide range of network hardware and operating
systems including Cisco, Linux, FreeBSD, Juniper, Brocade, Foundry, HP and
many more.

We intend LibreNMS to be a viable project and community that:
- encourages contribution,
- focuses on the needs of its users, and
- offers a welcoming, friendly environment for everyone.

The [Debian Social Contract][10] will be the basis of our priority system,
and mutual respect is the basis of our behavior towards others.


Documentation
-------------

Documentation can be found in the [doc directory][5] or [docs.librenms.org][16], including instructions
for installing and contributing.


Participating
-------------

You can participate in the project by:
- Talking to us on [Discord][4] or [Twitter][3].
- Joining the [LibreNMS Community](https://community.librenms.org)
- Improving the [documentation][5].
- Cloning the [repository][2] and filing [pull requests][19] on GitHub.
- [Bug Reports](https://community.librenms.org) on our Community Forums
- See [CONTRIBUTING][15] for more details.


VM image
--------

You can try LibreNMS by downloading a VM image.  Currently, a Ubuntu-based
image is supplied and has been tested with [VirtualBox][8].

Download one of the [VirtualBox images][11] we have available, documentation is provided which details
login credentials and setup details.

License
-------

Copyright (C) 2006-2012 Adam Armstrong <adama@memetic.org>

Copyright (C) 2013-2024 by individual LibreNMS contributors

 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.

 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.

 You should have received a copy of the GNU General Public License
 along with this program.  If not, see <https://www.gnu.org/licenses/>.

[LICENSE.txt][14] contains a copy of the full GPLv3 licensing conditions.

The following additional license conditions apply to LibreNMS (a GPL
exception):

  As a special exception, you have permission to link or otherwise combine
  LibreNMS with the included copies of the following third-party software,
  and distribute modified versions, as long as you follow the requirements
  of the GNU GPL v3 in regard to all of the remaining software (comprising
  LibreNMS).

  Please see [Acknowledgements][17]

[2]: https://github.com/librenms/librenms "Main LibreNMS GitHub repo"
[3]: https://twitter.com/librenms "@LibreNMS on Twitter"
[4]: https://discord.gg/librenms "Discord LibreNMS Server"
[5]: https://github.com/librenms/librenms/tree/master/doc/
[8]: https://www.virtualbox.org/ "VirtualBox"
[10]: http://www.debian.org/social_contract "Debian project social contract"
[11]: https://www.librenms.org/#downloads
[14]: https://github.com/librenms/librenms/tree/master/LICENSE.txt
[15]: https://docs.librenms.org/General/Contributing/
[16]: https://docs.librenms.org/
[17]: https://docs.librenms.org/General/Acknowledgement/
[19]: https://github.com/librenms/librenms/pulls


## Backers

Support us with a monthly donation and help us continue our activities. [[Become a backer](https://opencollective.com/librenms#backer)]

<a href="https://opencollective.com/librenms/backer/0/website" target="_blank"><img src="https://opencollective.com/librenms/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/1/website" target="_blank"><img src="https://opencollective.com/librenms/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/2/website" target="_blank"><img src="https://opencollective.com/librenms/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/3/website" target="_blank"><img src="https://opencollective.com/librenms/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/4/website" target="_blank"><img src="https://opencollective.com/librenms/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/5/website" target="_blank"><img src="https://opencollective.com/librenms/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/6/website" target="_blank"><img src="https://opencollective.com/librenms/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/7/website" target="_blank"><img src="https://opencollective.com/librenms/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/8/website" target="_blank"><img src="https://opencollective.com/librenms/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/9/website" target="_blank"><img src="https://opencollective.com/librenms/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/10/website" target="_blank"><img src="https://opencollective.com/librenms/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/11/website" target="_blank"><img src="https://opencollective.com/librenms/backer/11/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/12/website" target="_blank"><img src="https://opencollective.com/librenms/backer/12/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/13/website" target="_blank"><img src="https://opencollective.com/librenms/backer/13/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/14/website" target="_blank"><img src="https://opencollective.com/librenms/backer/14/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/15/website" target="_blank"><img src="https://opencollective.com/librenms/backer/15/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/16/website" target="_blank"><img src="https://opencollective.com/librenms/backer/16/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/17/website" target="_blank"><img src="https://opencollective.com/librenms/backer/17/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/18/website" target="_blank"><img src="https://opencollective.com/librenms/backer/18/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/19/website" target="_blank"><img src="https://opencollective.com/librenms/backer/19/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/20/website" target="_blank"><img src="https://opencollective.com/librenms/backer/20/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/21/website" target="_blank"><img src="https://opencollective.com/librenms/backer/21/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/22/website" target="_blank"><img src="https://opencollective.com/librenms/backer/22/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/23/website" target="_blank"><img src="https://opencollective.com/librenms/backer/23/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/24/website" target="_blank"><img src="https://opencollective.com/librenms/backer/24/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/25/website" target="_blank"><img src="https://opencollective.com/librenms/backer/25/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/26/website" target="_blank"><img src="https://opencollective.com/librenms/backer/26/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/27/website" target="_blank"><img src="https://opencollective.com/librenms/backer/27/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/28/website" target="_blank"><img src="https://opencollective.com/librenms/backer/28/avatar.svg"></a>
<a href="https://opencollective.com/librenms/backer/29/website" target="_blank"><img src="https://opencollective.com/librenms/backer/29/avatar.svg"></a>


## Sponsors

Become a sponsor and get your logo on our README on GitHub with a link to your site. [[Become a sponsor](https://opencollective.com/librenms#sponsor)]

<a href="https://opencollective.com/librenms/sponsor/0/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/1/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/2/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/3/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/4/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/5/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/6/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/7/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/8/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/librenms/sponsor/9/website" target="_blank"><img src="https://opencollective.com/librenms/sponsor/9/avatar.svg"></a>


>>>>>>> master
