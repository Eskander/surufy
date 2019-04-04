# Surufy
Add Suru-style mask for your non-Suru iconed programs on Ubuntu with Yaru theme.

*NOTE: DEPRECATED:* Yaru theme no longer have squircle icons.

![screenshot][1]

#### Warning: This is an experimental, a pre-alpha, a non guaranteed to work script.

The idea came from some Android phone manufacturers that shape their default icons however they want then add a mask behind all user installed apps to keep the look consistant ― You get the idea (if not, [look here][2]).

## How to install
TODO

### Some known limitations
  * Not all programs store their icons in `hicolor/*/apps` so some programs won't get the mask.
  * No svg icons for now. (maybe this will change in the future)
  * ..

## How to remove
Since it's experimental and all
```
sudo rm -rf /etc/apt/apt.conf.d/92surufy /usr/lib/surufy ~/.local/share/icons/Yaru
```

###### DISCLAIMER: All icons and brands and whatever belong to their respective owners.

  [1]: https://github.com/eskander/surufy/raw/master/screenshot.png
  [2]: https://www.xda-developers.com/files/2018/09/Screenshot_20180925-000901_Samsung-Experience-Home-498x1024.jpg
