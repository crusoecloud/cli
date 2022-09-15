# Crusoe Cloud CLI

Repository for the [Crusoe Cloud CLI](https://crusoecloud.com), the world's first carbon-reducing, low-cost GPU cloud platform. Compiled binaries and release changelogs are located in the [releases](https://github.com/crusoecloud/cli/releases). To get started, check out our [documentation](https://docs.crusoecloud.com) and [sign up](https://console.crusoecloud.com/request). For support or feedback please [contact support](https://docs.crusoecloud.com/resources/support). 

## To install Crusoe Cloud cli with brew:

`brew install crusoecloud/cli/crusoe`

## To install Crusoe Cloud cli with apt:

```sh
echo "deb [trusted=yes] https://apt.fury.io/crusoe/ * *" > /etc/apt/sources.list.d/fury.list
sudo apt update
sudo apt install crusoe
```

### Verify CLI releases
If you would like to verify the authenticity of your download, our public gpg key is located at `signing/public.key`. A signature of `checksums.txt` is included as an asset with each of our releases in `checksums.txt.sig`.
