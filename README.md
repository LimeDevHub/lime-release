# lime-release

# Installation

## Windows

### Install Manually

1. Download the installation package ending in `.msi` or `.exe` from the [Latest Release](https://github.com/LimeDevHub/lime-release/releases/latest) page.
2. Double click the downloaded file to install it.
3. If prompted as unsafe, you can click on `More Info` -> `Run Anyway` to proceed with the installation.
4. Ready to use!

## MacOS 

### Install Manually

1. Go to the [Latest Release](https://github.com/LimeDevHub/lime-release/releases/latest) page and download the corresponding chip's `.dmg` installation package. Note: Use aarch64 version for Apple Silicon machines and run `xattr` command below.
2. Double click the downloaded file to install it.
3. Ready to use!

### Troubleshooting

<p align="center">
<img width="372" alt="image" src="https://github.com/LimeDevHub/lime-release/assets/28869910/b47710e2-a6bb-4efb-916a-a8feff12b212">
</p>

If you get error prompts such as broken files with Apple Silicon machines. Open Terminal.app and enter the following command (you may need to enter a password halfway through), then restart Lime:

```
sudo xattr -d com.apple.quarantine /Applications/lime.app
```

# Acknowledgement

- https://github.com/iawia002/lux
- https://github.com/eugeneware/ffmpeg-static
- https://github.com/openai-translator/openai-translator
