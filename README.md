# Sake

> [!Warning]
> This is a heavily modified Version of the original hikari-sake version.
> In some cases it works completely different than the original version.
> 
> Current changes:
> - Using `hikari.internal.fast_protocol.FastProtocolChecking` to make sure that protocols work with Py >= 3.12
> - `MessageCache` does not update or delete messages automatically. These functions need to be called manually. 


A distributed asynchronous cache interface (plus several implementations) designed for use with Hikari.

# Installation

You can install Sake from PyPI using the following command.

```
python -m pip install hikari-sake -U
```

The `hikari-sake[tanjun]` feature flag can be used to ensure that the installed Tanjun version
is compatible with Sake's Tanjun adapters. You should still have a Tanjun version pinned in
your own requirements as this just provides an acceptable range for the requirement.

# Support

[Hikari's support guild](https://discord.gg/hikari) provides for support for Sake.

# Quick Usage.

For usage see the the [documentation](https://fasterspeeding.github.io/Sake/) and
[examples](https://github.com/FasterSpeeding/Sake/tree/master/examples) .
