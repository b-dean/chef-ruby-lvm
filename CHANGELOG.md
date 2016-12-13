# 0.2.2 (2016-12-12)

- Fork di-ruby-lvm as chef-ruby-lvm in order to unblock the Chef lvm cookbook support for the latest Linux distros
- Convert the readme to markdown and reword portions
- Resolve all chefstyle warnings
- Added a Gemfile/Rakefile for chefstyle linting

# 0.2.1 (2015-12-04)

- Fix failures calling the calling physical_volumes list method

# 0.2.0 (2015-12-01)

- Minor code refactoring
- Improve runtime with multiple VGs
- Use just a gemspec instead of hoe
- Require a newer di-ruby-lvm-attrib gem

....

# 0.1.1 (2008-07-21)

- 1 major enhancement

  - A complete rewrite! We won't bother attempting to wrap complex lvm operations, but instead provide LVM.raw() command. The wrapper now focuses purely on translating lvm lv/vg/pv data into the most useful ruby objects possible. The arguments passed to the underlying binaries have been broken out into a ruby-lvm-attributes package.

# 0.0.1 (2008-05-28)

- 1 major enhancement

  - Birthday!
  - Test release.
