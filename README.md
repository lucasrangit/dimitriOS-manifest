# dimitriOS-manifest
A manifest to fetch the sources for the **`dimitriOS`** embedded Linux distribution.

To read more about the project, and how to build an image, please refer to the [meta-dimitriOS][].

## Manifest structure

| Manifest             | Purpose                                                                    |
| -------------------- | -------------------------------------------------------------------------- |
| `dimitriOS-base.xml` | Hardware-agnostic manifest for `dimitriOS` with the `meta-dimitriOS` layer |
| `dimitriOS-rpi.xml`  | Manifest for Raspberry Pi boards                                           |

[meta-dimitriOS]: https://github.com/platisd/meta-dimitriOS
