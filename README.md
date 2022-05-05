# wireshark-zigbee-profile

Wireshark configuration profile for Zigbee traffic


## Installation

You can install this Zigbee profile by copying the `Zigbee` folder of this repository and pasting it inside the `profiles` folder of your Wireshark personal configuration directory.
In Linux distributions, this directory is typically located at `~/.config/wireshark`.
In this case, you can install it by executing the following commands:
```console
$ git clone https://github.com/akestoridis/wireshark-zigbee-profile.git
$ cp -r wireshark-zigbee-profile/Zigbee/ ~/.config/wireshark/profiles/Zigbee/
```
Regardless of your operating system, you can find the path of your Wireshark personal configuration directory by opening Wireshark, navigating to `Help`>`About Wireshark`>`Folders`, and inspecting the `Location` column of the `Personal configuration` row.
Once you have copied the `Zigbee` folder of this repository and pasted it inside the `profiles` folder of your Wireshark personal configuration directory, you can enable it by opening Wireshark, navigating to `Edit`>`Configuration Profiles...`, and selecting the `Zigbee` profile.


## Screenshots

The following screenshot showcases some of the profile's coloring rules, but several columns were hidden and the text was slightly enlarged to be more legible. A more detailed screenshot is available [here](https://github.com/akestoridis/wireshark-zigbee-profile/raw/7110457d020099e72139253628c3548e35e957fc/screenshot-wide.png).

<img src="https://github.com/akestoridis/wireshark-zigbee-profile/raw/7110457d020099e72139253628c3548e35e957fc/screenshot-narrow.png">

Both screenshots show the same packets from the `sth3-duos.pcap` file of the [CRAWDAD dataset cmu/zigbee-smarthome](https://doi.org/10.15783/c7-nvc6-4q28).


## Related Publications

* D.-G. Akestoridis and P. Tague, “HiveGuard: A network security monitoring architecture for Zigbee networks,” in *Proc. IEEE CNS’21*, 2021, pp. 209–217, doi: [10.1109/CNS53000.2021.9705043](https://doi.org/10.1109/CNS53000.2021.9705043).
* D.-G. Akestoridis, M. Harishankar, M. Weber, and P. Tague, “Zigator: Analyzing the security of Zigbee-enabled smart homes,” in *Proc. ACM WiSec’20*, 2020, pp. 77–88, doi: [10.1145/3395351.3399363](https://doi.org/10.1145/3395351.3399363).


## Acknowledgments

This project was supported in part by the Carnegie Mellon CyLab Security and Privacy Institute and in part by Carnegie Mellon University.


## License

Copyright (C) 2020 Dimitrios-Georgios Akestoridis

This project is licensed under the terms of the GNU General Public License version 2 or later (GPL-2.0-or-later).
