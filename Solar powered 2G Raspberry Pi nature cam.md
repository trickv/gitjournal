---
created: 2022-07-27T19:22:55-05:00
modified: 2022-07-28T16:41:36-05:00
type: Journal
---

# Solar powered 2G Raspberry Pi nature cam

A few years back I ran across [this article about a solar powered Raspberry Pi camera](https://www.hackster.io/reichley/solar-powered-squirrel-kam-pi-zero-w-updated-797db4). Without considering what I would use it for, I immediately bought the parts for a single solar cell & battery to try and make my own. Without too much hassle I succeeded, but I didn't have a use case. So the parts sat on my shelf while we brought our second child into the world.

# Spark of Inspiration

Madeline Island is beautiful. My in laws go there every year. In the ~50 odd weeks that they are not there, they obsess over the weather, read the Madeline Island gazette, and watch the [Beach Club web cam](https://www.madelineisland.com/madeline-island-webcam/) when the weather is interesting.

Last year while visiting I thought, how could I snake a PoE network cable 200' from the family cabin down to the cliff edge by the water to run our own camera? But there are challenges. 200' is a long way; a lot of digging. Then there's the simple reality that the cabin is only inhabitated for the warmer part of the year and the Internet gets shut down in winter. That would be less fun.

Then I had a spark of an idea: digging through my parts box I found a [Waveshare SIM800X GSM/GPRS hat](https://www.waveshare.com/wiki/SIM800C_GSM/GPRS_HAT) that I'd never found a use for. I looked around and realized that with enough hacking, this solution could run in any environment. Obviously subject to power & data limitations. But that's half the fun right?

# Solar powered Raspberry Pi with LiPo battery and GSM/GPRS connectivity

Here's what I ended up building with:
* Raspberry Pi Zero W
* Pimoroni LiPo Shim
* Waveshare SIM800X hat
* TP4056 charging module
* Relay for turning the Waveshare board on/off to save power

So then.
