## SLE Registration

AutoYaST can register a SLE system, use modules and extensions from the server
and install the provided online updates.


#### SCC Registration

Template for SLE15-SP3: [scc.xml]({{ "/" | absolute_url }}registration/scc.xml)

- Set `linux` password for the `root` user
- Register the system against [SCC](https://scc.suse.com)
- Add `Server Applications Module` (explicitly) and
  `Basesystem Module` (automatically as a dependency) software modules (repositories)
- Install available updates
- See more details in a [commented example](
https://github.com/yast/yast-registration/wiki/Autoyast-Support#manually-editing-an-autoyast-profile)

##### :warning: Notes

- This file is just a template, you need to download the file, edit it
  (to add your own registration code) and publish it on your server.
- For using with a different version than SLES15-SP3 you need to edit
  the addon version.
