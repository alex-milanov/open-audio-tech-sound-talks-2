# Отворени Аудио Технологии
[ползвайте стрелките за навигация ← → ↑ ↓]

## ... мисията (не)възможна

### ... или пък по-стабилно решение в дългосрочен план

## Постановка

### Моделът черната кутия

### През Рим за Атина

### Нашия пясъчник е много по-добър от вашия пясъчник

### Apple (и техните зарядни)

### Конспирацията на крушката

## MIDI
https://en.wikipedia.org/wiki/MIDI
- 1980 Roland -> DIN sync interface
- 1981 Roland -> DCB (Digital Control Bus)
- DCB protocol + DIN sync connector -> MIDI
- -> Yamaha, Korg, Kawai and Sequential Circuits
- 1982 MIDI's development announced, Robert Moog, Keyboard Magazine
- 1983 Demonstration at NAMM, Publication of specs (August)

## Аудио под Linux
http://linuxaudio.org

### Jack
http://jackaudio.org

### Low latency kernel
```sh
# за ubuntu
sudo apt-get update
sudo apt-get install linux-lowlatency linux-headers-lowlatency
```

### KXStudio
http://kxstudio.linuxaudio.org -> Repositories

### Jack & Pulseaudio
```sh
# ubuntu/debian
# инсталирайте jack module-а за pulseaudio
sudo apt-get install pulseaudio-module-jack

# отворето конфиг-а на pulseaudio
sudo nano /etc/pulse/default.pa

# и добавете тези 2 реда
load-module module-jack-sink
load-module module-jack-source

# рестартирайте pulseaudio
killall pulseaudio
```

## Open Apps

### Audacity
http://www.audacityteam.org

### ZynAddSubFX
http://zynaddsubfx.sourceforge.net

### LMMS
https://lmms.io

### VCV Rack
https://vcvrack.com

## Open Hardware

### Arduino & Raspberry PI
https://www.arduino.cc
https://www.raspberrypi.org

### Zynthian
http://zynthian.org/

## Моите залитания

### MusicTechBG
https://fb.com/groups/musictechbg
https://www.meetup.com/MusicTechBG

### The Jam Station
https://github.com/alex-milanov/jam-station
https://alex-milanov.github.io/jam-station

## Showtime
