# nakarin-test
just a test. please ignore

This is a R&D project to implement Bulldozer, an automatic way to merge PRs when all conditions are met.

The way Bulldozer works is quite simple. There are only 2 buckets of decision, ``Whitelist`` and ``Blacklist``.

There are many ways put a PR to one of each bucket. For example.
 - Labels: ``merge when ready`` and ``do not merge``

If both whitelist and blacklist are defined and matched, blacklist will take precedence.
