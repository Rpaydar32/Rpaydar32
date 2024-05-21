{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8c91:4063:21d0:7dd5:f218/128"
      ],
      "private_key": "MBc+tlX8hK46M/ONlJdoBH2/KUHRB2kelFyet3ewZ0Y=",
      "server": "188.114.97.232",
      "server_port": 8319,
      "peer_public_key": "MBc+tlX8hK46M/ONlJdoBH2/KUHRB2kelFyet3ewZ0Y=",
      "reserved": [164,48,6],
      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "Warp-Main",
      "detour": "Warp-IR",
      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:8c15:3f90:ad2d:8810:77f3/128"
      ],
      "private_key": "AKOZVjlsnhLTidKqOTP0JibR9rFil8A1sWi4HQZnLUU=",
      "server": "188.114.97.232",
      "server_port": 8319,
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": [159,59,9],
      "mtu": 1280,
      "fake_packets": "5-10"
    }
  ]
}
