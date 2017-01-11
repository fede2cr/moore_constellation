# Tier1 NTP Server synchronized to GPS

For correlating data between the nodes is very important to have good clock sync on all of the parts of a Moore Cluster.

This proyect is designed for those nodes that will be offline enough to have issues with remote NTP servers.

## Instructions

Run the ansible recipe on a freshly installed Raspbian image or Arch arm to fully install a Tier1 NTP Server synchronized to a USB GPS source.

It should work on any Raspberry Pi model an even on similar boards.

## See Also

- (Based on tutorial)[http://www.satsignal.eu/ntp/Raspberry-Pi-NTP.html]
