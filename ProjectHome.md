Access point scanning requires a considerable amount of energy, especially on modern smart phones. This is because i) a/b/g/n devices scan both the 2.4- and 5GHz spectrum, comprising 32 channels in total and ii) modern CPUs are power hungry, so even background scanning suffers a considerable enery hit from CPU overhead.

This project contains a hack to wpa\_supplicant that enables scanning only a subset of the available channel spectrum.

There are two flavors: a modified wpa\_supplicant\_8 for most modern devices, and a modified ti\_wlan driver for HTC G1 (Dream, ADP) and G2 (Hero) phones.