
## 
**Fork of Streamlink which includes the option to specify a decryption key. Tested on DASH Live Stream encryption.**  

**e.g streamlink --default-stream best --url -o "C:\Users\User\Downloads\test.mkv" --ffmpeg-dkey "03de....."**  

**--ffmpeg-dkey**
##
Streamlink is a CLI utility which pipes video streams from various services into a video player, such as VLC.

The main purpose of streamlink is to avoid resource-heavy and unoptimized websites, while still allowing the user to enjoy various streamed content.

Streamlink is a fork of the [Livestreamer][livestreamer] project.

Please note that by using this application you're bypassing ads run by
sites such as Twitch.tv. Please consider donating or paying for subscription
services when they are available for the content you consume and enjoy.


# [Installation][streamlink-installation]

Please refer to our documentation for different ways to install Streamlink:

- [Windows][streamlink-installation-windows]
- [macOS][streamlink-installation-macos]
- [Linux and BSD][streamlink-installation-linux-and-bsd]
- [PyPI package and source code][streamlink-installation-pypi-source]

# Features

Streamlink is built upon a plugin system which allows support for new services to be easily added.
Most of the big streaming services are supported, such as:

- [Twitch](https://www.twitch.tv)
- [YouTube](https://www.youtube.com)
- [Livestream](https://livestream.com)
- [Dailymotion](https://www.dailymotion.com)

... and many more. A full list of plugins currently included can be found on the [plugin page][streamlink-plugins].


# Quickstart

After installing, simply use:

```
streamlink STREAMURL best
```

The default behavior of Streamlink is to play back streams in the VLC player.

For more in-depth usage and install instructions, please refer to the [detailed documentation][streamlink-documentation].




