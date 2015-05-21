# Astro Pi examples

Example programs using the Astro Pi / Sense HAT

## About

British ESA astronaut [https://twitter.com/astro_timpeake](Tim Peake) is going to the [International Space Station](https://twitter.com/Space_Station) for 6 months at the end of 2015 and taking two [Raspberry Pi](https://www.raspberrypi.org/) computers to run experiments coded by participants in the [Astro Pi](http://astro-pi.org/) coding competition for UK schools.

The Astro Pi (otherwise known as Sense HAT) is the hardware attachment board mounted to the Pis on the ISS, and will be available to the public as a product soon.

The Raspberry Pi Foundation have created a [Python API](https://pypi.python.org/pypi/astro-pi) to provide access to the board's LED matrix and sensors. See the documentation at [pythonhosted.org/astro-pi](http://pythonhosted.org/astro-pi/)

## Usage

With an Astro Pi / Sense HAT on a Raspberry Pi, and the firmware and Python library installed (see [Astro Pi installation](http://pythonhosted.org/astro-pi/)), download or clone this repository, enter the `python` directory and run the examples with Python 3 or Python 2.

e.g.

```bash
git clone git://github.com/bennuttall/astro-pi-examples
cd astro-pi-examples/python
python3 random_sparkles.py
```

## Examples

### Random Sparkles

Let your Astro Pi shine with pride

- [random_sparkles.py](python/random_sparkles.py)

### Conway's Game of Life

[Conway's Game of Life]() is a zero-player cellular automaton game

- [conway.py](python/conway.py)

The game is randomly generated each time. Some games will be over very quickly, others will last a few generations. Press `Ctrl + C` to quit and then run it again.

### Minecraft Colour

Walk around a Minecraft world and the Astro Pi will light up the colour of the block you're standing on

- [minecraft_colour.py](python/minecraft_colour.py)

Be sure to open a Minecraft world first

### Minecraft Map

Walk around a Minecraft world and the Astro Pi will show an 8x8 map of your player's surroundings

- [minecraft_map.py](python/minecraft_map.py)

Be sure to open a Minecraft world first. Note blocks are cached for speed so alterations are not accounted for.

## Licence

All examples provided are free to use for any purpose, with or without attribution.
