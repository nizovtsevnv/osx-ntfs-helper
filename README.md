<h1 align="center">
  <br>
  <img src="https://github.com/nizovtsevnv/osx-ntfs-helper/raw/main/assets/osx.png" alt="MacOS" width="150"></a>
  <img src="https://github.com/nizovtsevnv/osx-ntfs-helper/raw/main/assets/ntfs.png" alt="MacOS" width="150"></a>
  <br>
  OSX NTFS Helper
  <br>
</h1>

<h4 align="center">Instruction and helper script for mounting all NTFS drives in writeable mode on MacOS.</h4>

<p align="center">
  <a href="https://saythanks.io/to/nizovtsevnv">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
  <a href="https://buymeacoffee.com/nizovtsevnv">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p>

## Installation

1. Open your Terminal application
2. Install [Homebrew](https://brew.sh/): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Add FUSE homebrew repo: `brew tap gromgit/homebrew-fuse`
4. Install fresh version of [MacFUSE](https://github.com/osxfuse/osxfuse/wiki) adapter and [NTFS-3G](https://github.com/osxfuse/osxfuse/wiki/NTFS-3G) driver: `brew install macfuse ntfs-3g-mac`
5. Add helper script ([mount-all-ntfs](https://github.com/nizovtsevnv/osx-ntfs-helper/releases/download/v1.0/mount-all-ntfs)) from this repository to your preferable location (for example `~/.bin`) and check this location is in `PATH` environment variable

## Usage example

```
$ mount-all-ntfs
Volume MyNtfsDrive on disk2s1 unmounted
Volume MyNtfsDrive on disk2s1 mounted in writeable mode
```

## License

Distributed under the MIT license. See [LICENSE](https://github.com/nizovtsevnv/osx-ntfs-helper/raw/main/LICENSE) for more information.

## Support

<a href="https://www.buymeacoffee.com/nizovtsevnv" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## Contributing

1. Fork it (<https://github.com/nizovtsevnv/osx-ntfs-helper/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
