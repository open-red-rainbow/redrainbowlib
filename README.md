# Red Rainbow Compatibility Layer

This acts is an abstraction layer necessary for a modular implementation of 'Red Rainbow'.
While the [core](https://github.com/open-red-rainbow/RainbowCore) has to
    - manage and load modules
    - set up or read configuration
    - handle user actions through an interface
this layer exposes functionality for modules in a implementation-independent way.
This ensures any module will work independently of implementation details like the wrapper in use
or the networking library.

## Modules

A module is an arbitrary block of bot functionality, following the
[Specification](https://github.com/open-red-rainbow/module_base/blob/main/README.md#specification).
Currently, only modules implemented in python are supported, though future efforts **MAY** enable
implementing modules using other technologies and programming languages.

We recommend to base any module on the provided [template](https://github.com/open-red-rainbow/module_base).

## Documentation

Coming Soon...
<!--TODO use Sphinx for documentation-->

## Support

Contact the us in our [discord server](https://discord.gg/rB2BSxqNZs).
