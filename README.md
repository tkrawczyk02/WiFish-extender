# WiFish-extender
Creating a Wi-Fi range extender for Raymarine Wi-Fish so it can be used in a baitboat.

So this projects documents how I modified a standalone 230V socket-plug type Wi-Fi range extender to a battery powered one with greater range.

I used TP-LINK TL-WA860RE, because it was laying in my garage, can't say if there are better options on the market.

I began by stripping it of it's case and removing the 230V plug.

![Alt text](progress_%231.jpg?raw=true "Title")


As you can see there are two boards, the lower one is a PSU, it converts 230V AC to 3.3V DC to power up the upper board, which is responsible for all the hard work.
Board are connected by 4 four goldpin jumpers, two for each positive and negative terminal.

I used a ready-made DC-DC converter based on LM2596 because it is dirt cheap, and just soldered the wires to the appropriate pins.
![Alt text](progress_%234.jpg?raw=true "Title")
Next I began to remove the existing antennas, it turned out it just a simple PCB board, to be honest I'm quite impressed that I got a 130m range on open water, while encased in a boat hull from those antennas.

![Alt text](progress_%232.jpg?raw=true "Title")



I desoldered the cables, and soldered new 50cm SMA-RP pigtails.

![Alt text](progress_%233.jpg?raw=true "Title")

And it's done. I kept the original casing, because it was just the easiest way, and it doesn't take too much space.
![Alt text](after.jpg?raw=true "Title")


I am still waiting for new antennas, but I hope to reach a 250m range.

