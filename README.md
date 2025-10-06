<!-- SPDX-License-Identifier: Apache-2.0 -->
<!-- Copyright Contributors to the ACES Project. -->

# ACES Core Transforms

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![CLA
assistant](https://cla-assistant.io/readme/badge/ampas/aces-dev)](https://cla-assistant.io/ampas/aces-dev)

This repository houses core CTL library functions used by the ACES system. These
functions provide the foundational building blocks upon which higher-level ACES
transforms are constructed, including:

- Rendering algorithms used in ACES Output Transforms (e.g., tonescale, chroma
  compress, gamut compress)

- Utility functions for common operations (e.g., clamping, matrix math)

- Fundamental color science operations (e.g., transfer functions, matrix
  conversions, chromatic adaptation)

> [!IMPORTANT] 
> This repository was named **`aces-dev`** in versions of ACES prior to the 2.0
release, and preserves the commit history for those earlier ACES versions. <br>
Use the [tag history](https://github.com/ampas/aces-dev/tags) to access specific
ACES versions from before v2.0.

## Contributing

ACES depends on community participation. Developers, manufacturers, and end
users are encouraged to contribute code, bug fixes, documentation, and other
technical artifacts.

All contributors must have a signed Contributor License Agreement (CLA) on file
to ensure that the project can freely use your contributions. 

See [CONTRIBUTING.md](./CONTRIBUTING.md) for more details.

## Governance

This repository is a submodule of the ACES project, hosted by the ASWF. Details
about how the project operates can be found in the
[GOVERNANCE.md](https://github.com/ampas/aces/blob/main/GOVERNANCE.md) file in
the top-level ACES repository.

## Reporting Issues

To report a problem with Core Transforms, please open an
[issue](https://github.com/ampas/aces-core/issues).

If the issue is senstive in nature or a security related issue, please do not
report in the issue tracker. Instead refer to [SECURITY.md](SECURITY.md) for
more information about the project security policy.

## License

The ACES Project is licensed under the [Apache 2.0 license](./LICENSE).