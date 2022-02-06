# CD4007 Dual Complementary Pair plus Inverter

When I was learning about CMOS 4000 logic integrated circuits I was not content just to learn about them from a book or lecture, I wanted to see how they worked practically and so I still have the collection of 4000 series IC's that I experimented with.

One IC that was of particular interest  was the CD4007, using it you could construct many different logic gates, and with more than one, many different clocked and arithmetic  devices.
It has 3 complementary MOSFET pairs (a P-channel and an N-Channel device)  with some of the drains and sources exposed as well as the gates, which are connected together for each pair.

Well, I bought 20 devices with the idea of putting them on a PCB and connecting them up to make common logic blocks and explore how they worked.
Initially I thought I would build some circuitry for a clock, a means of setting input pins high and low, some output LED's etc. but now I think using a microcontroller, like an Arduino as a 'Chip Tester' ( there are many Arduino projects that do this)  would be a better way to go.

I have used Logisim Evolution (also hosted on Github) to capture the schematic and simulate common logic gates, some of the files here show the CD4007 pin numbers, some do not as yet.

The array I have constructed consists of 10 CD4007 IC's ( 30 complementary pairs) , all the VCC and GND pins are connected to power rails on the 'breadboard like' PCB and pin header has been used to allow connections to the pins using 100mm Dupont Female to Female cables.

What can I build with this many MOSFETs? 