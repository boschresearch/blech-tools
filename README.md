# Blech Tools

[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive) 

[![Project Status: Moved to http://github.com/blech-lang/blech-tools – The project has been moved to a new location, and the version at that location should be considered authoritative.](https://www.repostatus.org/badges/latest/moved.svg)](https://www.repostatus.org/#moved) to [development.blech-lang.org](http://development.blech-lang.org/blech-tools)

This repository comprises tools in the context of the Blech language and compiler.
Currently, the following tools are available:
* `ide/` - Integrated Development Environment plugin

## Cloning this repository

This repository contains the source of the Blech compiler as its submodule.

Therefore clone with
```
git clone --recurse-submodules https://github.com/boschresearch/blech-tools.git
```

In order to update the Blech compilers sources, go into the subfolder ```./blech```. 
Update the ```blech``` submodule.

```
cd blech
git pull
```

## License

Blech tools are open-sourced under the Apache-2.0 license. See the
[LICENSE](LICENSE) file for details.

For a list of other open source components included in Blech tools, see the
file [3rd-party-licenses.txt](3rd-party-licenses.txt).
