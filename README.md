# image-builder

## Building the adsbexchange image based on buster:

```
git clone https://github.com/ADSBexchange/image-builder.git
cd image-builder
wget -O https://downloads.raspberrypi.org/raspios_oldstable_lite_armhf/images/raspios_oldstable_lite_armhf-2021-12-02/2021-12-02-raspios-buster-armhf-lite.zip
unzip 2021-12-02-raspios-buster-armhf-lite.zip
 ./create-image.sh 2021-12-02-raspios-buster-armhf-lite.img buster.img
```

## Building the adsbexchange image base on bullseye

Shoudl work similar as above, not yet tested