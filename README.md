# kRDPclient releases

kRDPclient is the console client for the virtual machines on a [keelOS](https://keelos.dev) host
(Windows, x64): RDP to a VM's screen, with sound, USB device forwarding and the video a
[keelagent](https://github.com/keelos-dev/keelOS-releases#quickstart) in a GPU VM encodes.

**Most people do not need this page.** Every keelOS image carries a kRDPclient: open *Downloads* in
the host's web page and the zip you get already knows that host (address, certificate and an access
token of yours), so it connects without setup.

This repository holds the builds themselves, under [Releases](../../releases):

- `krdpclient-VERSION-windows-x64.zip`; the version is the release, the commit and the build time
  (UTC). Unzip anywhere and run `krdpclient.exe`; nothing is installed.
- A fix can be published here before the next keelOS image; the next image then carries it.
- Bugs and questions: [keelOS-releases Issues](https://github.com/keelos-dev/keelOS-releases/issues).

kRDPclient is not open source and is free to use, under the same terms as keelOS
(https://keelos.dev/about/). It includes IronRDP (MIT/Apache-2.0) and libvpx (BSD).
