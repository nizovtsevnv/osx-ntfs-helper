Status: **WIP**

1. Open yout Terminal application
2. Install [Homebrew](https://brew.sh/): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Add FUSE homebrew repo: `brew tap gromgit/homebrew-fuse`
4. Install fresh version of [MacFUSE](https://github.com/osxfuse/osxfuse/wiki) adapter and [NTFS-3G](https://github.com/osxfuse/osxfuse/wiki/NTFS-3G) driver: `brew install macfuse ntfs-3g-mac`
5. Add helper scripts (`ntfs-mount`, `ntfs-umount`) to your preferable location (for example `~/.bin`) and check this location is in `PATH` environment variable
6. Use helper scripts to mount and unmount NTFS drives in writeable mode