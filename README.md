# Crosshax
## Cross-device productivity.

### What will it solve?
Switching between devices is complicated, especially when working locally on experiments without git.
Even with file sync, reproducing environments and reopening apps is inefficient.

### How will crosshax fix this?
Crosshax is a docker-like environment. It is like a Dockerfile.

Crosshax acts as a virtual environment, where all apps must be installed inside the virtual environment, from the app store for crosshax (crosshax-compatible apps) or manually (manually download executables for all platforms).

Crosshax also works as a package manager. It manages all sorts of different tools, homebrew, pip, npm all in one place to build your environment as soon as you open your laptop.

Every action you do (through the cli, of course) is reproduced on the next device to create your environment.

The environment is optimized live into dependencies, so that it can perform all actions in parallel for speed.

Supported apps have extensions/plugins to automatically generate the same workspaces in the same apps, and they are automatically organised into the same desktop environment (scaled for relative aspect ratio)