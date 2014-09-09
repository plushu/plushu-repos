# plushu-repos

This plugin provides Plushu commands for managing repositories, as well as
`PLUSHU_ROOT/repos` (exposed to other plugins as `PLUSHU_REPOS_DIR` via
profile.sh).

plushu-repos does *not* actually manage any repos itself: the management of
a repo is left to the plugin for that repo's system, such as
[plushu/plushu-git][].

[plushu/plushu-git]: https://github.com/plushu/plushu-git
