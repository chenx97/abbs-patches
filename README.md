AOSC OS ABBS Tree Patch
=================

The AOSC OS ABBS Tree Patch repository contains build configurations and
scripts for all packages unavailable in the official AOSC OS
[repository](https://repo.aosc.io) in an unorganized fashion. The
"Tree" is split into two main classes:

- the top level contains components targetting [AOSC OS Mainline](https://github.com/AOSC-Dev/aosc-os-abbs/tree/stable/).
- `retro` contains components targetting [AOSC OS/Retro](https://github.com/AOSC-Dev/aosc-os-abbs/tree/retro/).

Simple Usage
------------

```bash
git am <path_to_a_patch>
cd <ciel_directory>
ciel build <package_name>
```


Further Readings
----------------

- [Intro to Package Maintenance](https://wiki.aosc.io/developer/packaging/basics)
- [AOSC OS Package Styling Manual](https://wiki.aosc.io/developer/packaging/package-styling-manual)

Useful Links
------------

- [AOSC OS Packages](https://packages.aosc.io/)
- [AOSC OS Packages, QA Information](https://packages.aosc.io/qa/)
    - [List of Package Issue Codes](https://wiki.aosc.io/developer/packaging/qa-issue-codes)
- [AOSC BuildBot Information](https://wiki.aosc.io/developer/infrastructure/buildbots)

Need Help?
----------

Please report any build-time and run-time issues using our
[issues](https://github.com/chenx97/abbs-patches/issues/new/choose) page.
