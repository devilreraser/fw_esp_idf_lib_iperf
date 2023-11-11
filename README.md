# iperf Component

This directory contains an implementation for iperf network performance tester

Note that it's incompatible with `iperf3`

This component is used as part of the following ESP-IDF examples:
- [esp_wifi](../../wifi/iperf).
- [ble_mesh_wifi_coexist](../../bluetooth/esp_ble_mesh/ble_mesh_wifi_coexist).
- [ethernet](../../ethernet/iperf)

To learn more about how to use this component, please check API Documentation from header file [iperf.h](./include/iperf.h).

Please note that this component is not considered to be a part of ESP-IDF stable API, and only for example use for now.

iperf -u -c 192.168.3.2 -p 5001 --bandwidth=50
iperf -c 109.120.232.91 -p 4567
iperf -c 109.168.3.105 -p 5001
iperf -c 109.168.3.105 -p 5201
iperf -c 192.168.3.2
iperf -c 192.168.3.2 -t 100
iperf -c 192.168.137.1 -p 5001
iperf -c 192.168.3.2 -p 5001
iperf -c 192.168.137.1 -p 34444 -u
iperf -c 192.168.137.1