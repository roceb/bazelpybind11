
# Example of Bazel with pybind11

Here is a quick example take from the Pybind11 website and converted to work with Bazel.
This ~~was only tested with linux running on aarch64, but I assume it works in all environments.~~ was tested on both Mac M1 and Linux running on aarch64. ~~To save time I used my local install of python for this, but a custom python toolchain can be used.~~ I have used a hermetic python toolchain meaning that it no longer needs a local version of python.

This also works if you do not have bazel installed. I created a script to download and bazelisk (a bazel wrapper and version control manager) and store it locally for use.

To run the test, use the following command:

```bash
.tools/bazel test //...

```
