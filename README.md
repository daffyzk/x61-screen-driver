# x61-screen-driver

So far this is just collecting information...  

The idea is to eventually build a display driver pcb to make the screen output to HDMI/DP/eDP.  

Options for these screens on aliexpress/ebay are bulky and don't seem to be compatible with these screens either.

## Information:


There is an eDP/DP to LVDS integrated circuit from nxp, for around 5 bucks on some sites, model number PTN3460I.
the datasheet is in this repo.

There are some documents that specify some infomation on the display itself and how it comunicates

So far that's all I got, and some wikipedia articles:

[LVDS Standard](https://en.wikipedia.org/wiki/Low-voltage_differential_signaling)


## I/O 
for input, I couldn't find the original x61/x60 board-to-board connector anywhere, so I opted for this 40pin panasonic one:
https://www.digikey.com/en/products/detail/panasonic-electric-works/AXT640124/1986594
this does mean that it will required a special flex cable, but I am working on that too.

the output connector will be 20455-040E-76, standard 40pin eDP board-to-cable connector, used for displays like the BOE NE135FBM-N41
https://www.digikey.com/en/products/detail/i-pex/20455-040E-76/22108829
