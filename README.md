# wrt-log
My open wrt log from 22 of july

Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.739789] io scheduler noop registered
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.742153] io scheduler deadline registered (default)
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.747716] Serial: 8250/16550 driver, 16 ports, IRQ sharing enabled
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.757147] ar933x-uart: ttyATH0 at MMIO 0x18020000 (irq = 11, base_baud = 1562500) is a AR933X UART
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.764924] console [ttyATH0] enabled
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.771835] bootconsole [early0] disabled
Thu Nov 12 13:20:06 2020 kern.warn kernel: [    0.788013] m25p80 spi0.0: found gd25q32, expected m25p80
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.794321] m25p80 spi0.0: gd25q32 (4096 Kbytes)
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.797923] 5 tp-link partitions found on MTD device spi0.0
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.803036] Creating 5 MTD partitions on "spi0.0":
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.807861] 0x000000000000-0x000000020000 : "u-boot"
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.815528] 0x000000020000-0x00000016de50 : "kernel"
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.821921] 0x00000016de50-0x0000003f0000 : "rootfs"
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.827763] mtd: device 2 (rootfs) set to be root filesystem
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.832011] 1 squashfs-split partitions found on MTD device rootfs
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.838248] 0x0000003a0000-0x0000003f0000 : "rootfs_data"
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.846666] 0x0000003f0000-0x000000400000 : "art"
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    0.852780] 0x000000020000-0x0000003f0000 : "firmware"
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.860863] libphy: Fixed MDIO Bus: probed
Thu Nov 12 13:20:06 2020 kern.info kernel: [    0.883503] libphy: ag71xx_mdio: probed
Thu Nov 12 13:20:06 2020 kern.info kernel: [    1.516476] ag71xx-mdio.1: Found an AR7240/AR9330 built-in switch
Thu Nov 12 13:20:06 2020 kern.info kernel: [    1.558561] eth0: Atheros AG71xx at 0xba000000, irq 5, mode:GMII
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.186705] ag71xx ag71xx.0: connected to PHY at ag71xx-mdio.1:04 [uid=004dd041, driver=Generic PHY]
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.195475] eth1: Atheros AG71xx at 0xb9000000, irq 4, mode:MII
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.203526] NET: Registered protocol family 10
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.213031] NET: Registered protocol family 17
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.216188] bridge: filtering via arp/ip/ip6tables is no longer available by default. Update your scripts to load br_netfilter if you need this.
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.229118] 8021q: 802.1Q VLAN Support v1.8
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.235722] hctosys: unable to open rtc device (rtc0)
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.245714] VFS: Mounted root (squashfs filesystem) readonly on device 31:2.
Thu Nov 12 13:20:06 2020 kern.info kernel: [    2.252960] Freeing unused kernel memory: 216K
Thu Nov 12 13:20:06 2020 kern.warn kernel: [    2.255995] This architecture does not have kernel memory protection.
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    2.545053] random: fast init done
Thu Nov 12 13:20:06 2020 user.info kernel: [    3.165833] init: Console is alive
Thu Nov 12 13:20:06 2020 user.info kernel: [    3.168056] init: - watchdog -
Thu Nov 12 13:20:06 2020 user.info kernel: [    4.332090] kmodloader: loading kernel modules from /etc/modules-boot.d/*
Thu Nov 12 13:20:06 2020 user.info kernel: [    4.408997] kmodloader: done loading kernel modules from /etc/modules-boot.d/*
Thu Nov 12 13:20:06 2020 user.info kernel: [    4.417042] init: - preinit -
Thu Nov 12 13:20:06 2020 kern.info kernel: [    5.388607] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    5.423480] random: procd: uninitialized urandom read (4 bytes read)
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    8.793599] jffs2: notice: (401) jffs2_build_xattr_subsystem: complete building xattr subsystem, 0 of xdatum (0 unchecked, 0 orphan) and 0 of xref (0 dead, 0 orphan) found.
Thu Nov 12 13:20:06 2020 user.info kernel: [    8.809494] mount_root: switching to jffs2 overlay
Thu Nov 12 13:20:06 2020 user.warn kernel: [    8.849333] urandom-seed: Seeding with /etc/urandom.seed
Thu Nov 12 13:20:06 2020 user.info kernel: [    9.137108] procd: - early -
Thu Nov 12 13:20:06 2020 user.info kernel: [    9.138652] procd: - watchdog -
Thu Nov 12 13:20:06 2020 user.info kernel: [    9.817002] procd: - watchdog -
Thu Nov 12 13:20:06 2020 user.info kernel: [    9.819059] procd: - ubus -
Thu Nov 12 13:20:06 2020 kern.notice kernel: [    9.959546] random: ubusd: uninitialized urandom read (4 bytes read)
Thu Nov 12 13:20:06 2020 kern.notice kernel: [   10.034299] random: ubusd: uninitialized urandom read (4 bytes read)
Thu Nov 12 13:20:06 2020 kern.notice kernel: [   10.039910] random: ubusd: uninitialized urandom read (4 bytes read)
Thu Nov 12 13:20:06 2020 user.info kernel: [   10.046831] procd: - init -
Thu Nov 12 13:20:06 2020 user.info kernel: [   10.511429] kmodloader: loading kernel modules from /etc/modules.d/*
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.522540] ip6_tables: (C) 2000-2006 Netfilter Core Team
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.541309] Loading modules backported from Linux version wt-2017-11-01-0-gfe248fc2c180
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.547951] Backport generated by backports.git v4.14-rc2-1-31-g86cf0e5d
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.558785] ip_tables: (C) 2000-2006 Netfilter Core Team
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.574135] nf_conntrack version 0.5.0 (1024 buckets, 4096 max)
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.654576] xt_time: kernel timezone is -0000
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.733435] PPP generic driver version 2.4.2
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.739762] NET: Registered protocol family 24
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.798278] ath: EEPROM regdomain: 0x0
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.798292] ath: EEPROM indicates default country code should be used
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.798297] ath: doing EEPROM country->regdmn map search
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.798317] ath: country maps to regdmn code: 0x3a
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.798325] ath: Country alpha2 being used: US
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.798330] ath: Regpair used: 0x3a
Thu Nov 12 13:20:06 2020 kern.debug kernel: [   10.810070] ieee80211 phy0: Selected rate control algorithm 'minstrel_ht'
Thu Nov 12 13:20:06 2020 kern.info kernel: [   10.816281] ieee80211 phy0: Atheros AR9330 Rev:1 mem=0xb8100000, irq=2
Thu Nov 12 13:20:06 2020 user.info kernel: [   10.858966] kmodloader: done loading kernel modules from /etc/modules.d/*
Thu Nov 12 13:20:06 2020 kern.warn kernel: [   12.469127] urandom_read: 5 callbacks suppressed
Thu Nov 12 13:20:06 2020 kern.notice kernel: [   12.469139] random: jshn: uninitialized urandom read (4 bytes read)
Thu Nov 12 13:20:07 2020 user.notice dnsmasq: DNS rebinding protection is active, will discard upstream RFC1918 responses!
Thu Nov 12 13:20:07 2020 user.notice dnsmasq: Allowing 127.0.0.0/8 responses
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: started, version 2.80 cachesize 150
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: DNS service limited to local subnets
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: compile time options: IPv6 GNU-getopt no-DBus no-i18n no-IDN DHCP no-DHCPv6 no-Lua TFTP no-conntrack no-ipset no-auth no-DNSSEC no-ID loop-detect inotify dumpfile
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain test
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain onion
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain localhost
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain local
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain invalid
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain bind
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: using local addresses only for domain lan
Thu Nov 12 13:20:08 2020 daemon.warn dnsmasq[728]: no servers found in /tmp/resolv.conf.auto, will retry
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: read /etc/hosts - 4 addresses
Thu Nov 12 13:20:08 2020 daemon.info dnsmasq[728]: read /tmp/hosts/dhcp.cfg01411c - 0 addresses
Thu Nov 12 13:20:09 2020 authpriv.info dropbear[755]: Not backgrounding
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: tunnel
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: Network device
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: bridge
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: veth
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: macvlan
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: 8021ad
Thu Nov 12 13:20:11 2020 user.notice : Added device handler type: 8021q
Thu Nov 12 13:20:15 2020 user.notice ucitrack: Setting up /etc/config/network reload dependency on /etc/config/dhcp
Thu Nov 12 13:20:15 2020 user.notice ucitrack: Setting up /etc/config/network reload dependency on /etc/config/radvd
Thu Nov 12 13:20:15 2020 user.notice ucitrack: Setting up /etc/config/wireless reload dependency on /etc/config/network
Thu Nov 12 13:20:15 2020 user.notice ucitrack: Setting up /etc/config/firewall reload dependency on /etc/config/luci-splash
Thu Nov 12 13:20:15 2020 user.notice ucitrack: Setting up /etc/config/firewall reload dependency on /etc/config/qos
Thu Nov 12 13:20:15 2020 user.notice ucitrack: Setting up /etc/config/firewall reload dependency on /etc/config/miniupnpd
Thu Nov 12 13:20:16 2020 user.notice ucitrack: Setting up /etc/config/dhcp reload dependency on /etc/config/odhcpd
Thu Nov 12 13:20:16 2020 user.notice ucitrack: Setting up non-init /etc/config/fstab reload handler: /sbin/block mount
Thu Nov 12 13:20:16 2020 user.notice ucitrack: Setting up /etc/config/system reload trigger for non-procd /etc/init.d/led
Thu Nov 12 13:20:17 2020 user.notice ucitrack: Setting up /etc/config/system reload dependency on /etc/config/luci_statistics
Thu Nov 12 13:20:17 2020 user.notice ucitrack: Setting up /etc/config/system reload dependency on /etc/config/dhcp
Thu Nov 12 13:20:18 2020 kern.info kernel: [   25.978299] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
Thu Nov 12 13:20:18 2020 kern.info kernel: [   26.006073] br-lan: port 1(eth0.1) entered blocking state
Thu Nov 12 13:20:18 2020 kern.info kernel: [   26.010030] br-lan: port 1(eth0.1) entered disabled state
Thu Nov 12 13:20:18 2020 kern.info kernel: [   26.016052] device eth0.1 entered promiscuous mode
Thu Nov 12 13:20:18 2020 kern.info kernel: [   26.020180] device eth0 entered promiscuous mode
Thu Nov 12 13:20:18 2020 kern.info kernel: [   26.085082] IPv6: ADDRCONF(NETDEV_UP): br-lan: link is not ready
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'lan' is enabled
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'lan' is setting up now
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'lan' is now up
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'loopback' is enabled
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'loopback' is setting up now
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'loopback' is now up
Thu Nov 12 13:20:18 2020 kern.info kernel: [   26.172895] IPv6: ADDRCONF(NETDEV_UP): eth1: link is not ready
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'wan' is enabled
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'wan6' is enabled
Thu Nov 12 13:20:18 2020 daemon.notice procd: /etc/rc.d/S96led: setting up led WAN
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Network device 'lo' link is up
Thu Nov 12 13:20:18 2020 daemon.notice netifd: Interface 'loopback' has link connectivity
Thu Nov 12 13:20:19 2020 daemon.notice procd: /etc/rc.d/S96led: setting up led LAN1
Thu Nov 12 13:20:19 2020 daemon.notice procd: /etc/rc.d/S96led: setting up led LAN2
Thu Nov 12 13:20:19 2020 daemon.notice procd: /etc/rc.d/S96led: setting up led LAN3
Thu Nov 12 13:20:19 2020 daemon.notice procd: /etc/rc.d/S96led: setting up led LAN4
Thu Nov 12 13:20:19 2020 daemon.notice procd: /etc/rc.d/S96led: setting up led WLAN
Thu Nov 12 13:20:20 2020 user.notice firewall: Reloading firewall due to ifup of lan (br-lan)
Thu Nov 12 13:20:21 2020 kern.info kernel: [   28.326695] eth1: link up (100Mbps/Full duplex)
Thu Nov 12 13:20:21 2020 kern.info kernel: [   28.329837] IPv6: ADDRCONF(NETDEV_CHANGE): eth1: link becomes ready
Thu Nov 12 13:20:21 2020 daemon.notice netifd: Network device 'eth1' link is up
Thu Nov 12 13:20:21 2020 daemon.notice netifd: Interface 'wan' has link connectivity
Thu Nov 12 13:20:21 2020 daemon.notice netifd: Interface 'wan' is setting up now
Thu Nov 12 13:20:21 2020 daemon.notice netifd: Interface 'wan6' has link connectivity
Thu Nov 12 13:20:21 2020 daemon.notice netifd: Interface 'wan6' is setting up now
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036147] ath: EEPROM regdomain: 0x8283
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036161] ath: EEPROM indicates we should expect a country code
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036172] ath: doing EEPROM country->regdmn map search
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036181] ath: country maps to regdmn code: 0x3
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036188] ath: Country alpha2 being used: RU
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036194] ath: Regpair used: 0x3
Thu Nov 12 13:20:21 2020 kern.debug kernel: [   29.036203] ath: regdomain 0x8283 dynamically updated by user
Thu Nov 12 13:20:22 2020 daemon.notice netifd: wan (1222): udhcpc: started, v1.28.4
Thu Nov 12 13:20:22 2020 daemon.err odhcp6c[1228]: Failed to send RS (Address not available)
Thu Nov 12 13:20:22 2020 user.notice mac80211: Failed command: iw phy phy0 set antenna all all
Thu Nov 12 13:20:23 2020 daemon.notice netifd: wan (1222): udhcpc: sending discover
Thu Nov 12 13:20:23 2020 daemon.notice netifd: wan (1222): udhcpc: sending select for 10.146.35.11
Thu Nov 12 13:20:23 2020 daemon.notice netifd: wan (1222): udhcpc: lease of 10.146.35.11 obtained, lease time 2147483
Thu Nov 12 13:20:23 2020 daemon.info procd: - init complete -
Thu Nov 12 13:20:24 2020 daemon.notice netifd: Interface 'wan' is now up
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: reading /tmp/resolv.conf.auto
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain test
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain onion
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain localhost
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain local
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain invalid
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain bind
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using local addresses only for domain lan
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using nameserver 178.252.100.1#53
Thu Nov 12 13:20:24 2020 daemon.info dnsmasq[728]: using nameserver 178.252.100.5#53
Thu Nov 12 13:20:25 2020 user.notice firewall: Reloading firewall due to ifup of wan (eth1)
Thu Nov 12 13:20:25 2020 daemon.info dnsmasq[728]: read /etc/hosts - 4 addresses
Thu Nov 12 13:20:25 2020 daemon.info dnsmasq[728]: read /tmp/hosts/dhcp.cfg01411c - 0 addresses
Thu Nov 12 13:20:25 2020 daemon.err hostapd: Configuration file: /var/run/hostapd-phy0.conf
Thu Nov 12 13:20:25 2020 kern.info kernel: [   33.160899] IPv6: ADDRCONF(NETDEV_UP): wlan0: link is not ready
Thu Nov 12 13:20:26 2020 kern.info kernel: [   33.262555] br-lan: port 2(wlan0) entered blocking state
Thu Nov 12 13:20:26 2020 kern.info kernel: [   33.266519] br-lan: port 2(wlan0) entered disabled state
Thu Nov 12 13:20:26 2020 kern.info kernel: [   33.272294] device wlan0 entered promiscuous mode
Thu Nov 12 13:20:26 2020 daemon.notice hostapd: wlan0: interface state UNINITIALIZED->COUNTRY_UPDATE
Thu Nov 12 13:20:26 2020 daemon.err hostapd: Using interface wlan0 with hwaddr 60:e3:27:c1:ea:be and ssid "Wi-Fi"
Sun Jul 16 12:42:58 2023 kern.info kernel: [   35.026777] IPv6: ADDRCONF(NETDEV_CHANGE): wlan0: link becomes ready
Sun Jul 16 12:42:58 2023 kern.info kernel: [   35.031931] br-lan: port 2(wlan0) entered blocking state
Sun Jul 16 12:42:58 2023 kern.info kernel: [   35.037087] br-lan: port 2(wlan0) entered forwarding state
Sun Jul 16 12:42:58 2023 daemon.notice hostapd: wlan0: interface state COUNTRY_UPDATE->ENABLED
Sun Jul 16 12:42:58 2023 daemon.notice hostapd: wlan0: AP-ENABLED
Sun Jul 16 12:42:58 2023 daemon.notice netifd: bridge 'br-lan' link is up
Sun Jul 16 12:42:58 2023 daemon.notice netifd: Interface 'lan' has link connectivity
Sun Jul 16 12:42:58 2023 kern.info kernel: [   35.060606] IPv6: ADDRCONF(NETDEV_CHANGE): br-lan: link becomes ready
Sun Jul 16 12:42:58 2023 daemon.notice netifd: Network device 'wlan0' link is up
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[728]: exiting on receipt of SIGTERM
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: started, version 2.80 cachesize 150
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: DNS service limited to local subnets
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: compile time options: IPv6 GNU-getopt no-DBus no-i18n no-IDN DHCP no-DHCPv6 no-Lua TFTP no-conntrack no-ipset no-auth no-DNSSEC no-ID loop-detect inotify dumpfile
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq-dhcp[1537]: DHCP, IP range 192.168.1.100 -- 192.168.1.249, lease time 12h
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain test
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain onion
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain localhost
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain local
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain invalid
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain bind
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain lan
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: reading /tmp/resolv.conf.auto
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain test
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain onion
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain localhost
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain local
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain invalid
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain bind
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using local addresses only for domain lan
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using nameserver 178.252.100.1#53
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: using nameserver 178.252.100.5#53
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: read /etc/hosts - 4 addresses
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: read /tmp/hosts/dhcp.cfg01411c - 2 addresses
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq-dhcp[1537]: read /etc/ethers - 0 addresses
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: read /etc/hosts - 4 addresses
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq[1537]: read /tmp/hosts/dhcp.cfg01411c - 2 addresses
Sun Jul 16 12:43:04 2023 daemon.info dnsmasq-dhcp[1537]: read /etc/ethers - 0 addresses
Sun Jul 16 12:43:15 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 IEEE 802.11: authenticated
Sun Jul 16 12:43:15 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 IEEE 802.11: associated (aid 1)
Sun Jul 16 12:43:15 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED 3c:22:fb:e6:00:d3
Sun Jul 16 12:43:15 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 12:43:15 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sun Jul 16 12:43:15 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sun Jul 16 12:43:32 2023 kern.notice kernel: [   68.758334] random: crng init done
Sun Jul 16 12:47:04 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sun Jul 16 12:47:04 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sun Jul 16 13:26:23 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Sun Jul 16 13:26:23 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Sun Jul 16 13:26:23 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Sun Jul 16 13:26:23 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 13:26:53 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Sun Jul 16 13:26:53 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 13:26:53 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Sun Jul 16 13:26:53 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 13:26:54 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 13:26:54 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 13:30:57 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Sun Jul 16 13:30:57 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Sun Jul 16 13:30:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Sun Jul 16 18:48:47 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Sun Jul 16 18:48:47 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Sun Jul 16 18:48:47 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Sun Jul 16 18:48:47 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 18:49:24 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Sun Jul 16 18:49:24 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 18:49:26 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 18:49:26 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 18:51:08 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sun Jul 16 18:51:08 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sun Jul 16 19:08:33 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Sun Jul 16 19:08:33 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Sun Jul 16 19:11:56 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Sun Jul 16 19:11:56 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Sun Jul 16 19:11:56 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Sun Jul 16 19:11:56 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 19:11:56 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 19:11:56 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 19:24:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Sun Jul 16 19:24:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Sun Jul 16 19:24:32 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Sun Jul 16 19:24:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 19:24:32 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 19:24:32 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 20:00:57 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Sun Jul 16 20:00:57 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Sun Jul 16 20:00:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Sun Jul 16 20:06:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Sun Jul 16 20:06:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Sun Jul 16 20:06:02 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Sun Jul 16 20:06:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 20:06:04 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 20:06:04 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sun Jul 16 20:23:28 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Sun Jul 16 20:23:28 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Sun Jul 16 20:23:29 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Sun Jul 16 23:11:26 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 IEEE 802.11: authenticated
Sun Jul 16 23:11:26 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 IEEE 802.11: associated (aid 1)
Sun Jul 16 23:11:26 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED 3c:22:fb:e6:00:d3
Sun Jul 16 23:11:26 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: pairwise key handshake completed (RSN)
Sun Jul 16 23:11:26 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sun Jul 16 23:11:26 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Mon Jul 17 00:43:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 00:43:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 00:43:01 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 00:43:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 00:43:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Mon Jul 17 00:43:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 00:43:02 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 00:43:02 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 00:43:41 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Mon Jul 17 00:43:41 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Mon Jul 17 00:43:42 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Mon Jul 17 00:43:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 00:43:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 00:43:45 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 00:43:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 00:43:49 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 00:43:49 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 01:03:48 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Mon Jul 17 01:03:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Mon Jul 17 01:03:49 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Mon Jul 17 01:07:20 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 01:07:20 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 01:07:20 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 01:07:20 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 01:07:20 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 01:07:20 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 01:35:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 01:35:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 01:35:44 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 01:35:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 01:35:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 01:35:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 05:22:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Mon Jul 17 05:22:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Mon Jul 17 07:35:23 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 07:35:23 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 10:16:38 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disconnected due to excessive missing ACKs
Mon Jul 17 10:16:38 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Mon Jul 17 10:17:08 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Mon Jul 17 10:36:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 10:36:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 10:36:48 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 10:36:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 10:36:48 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 10:36:48 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 10:42:05 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Mon Jul 17 10:42:05 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Mon Jul 17 10:42:06 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Mon Jul 17 10:52:03 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Mon Jul 17 10:52:03 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Mon Jul 17 11:01:30 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 11:01:30 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 11:01:30 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 11:01:30 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 11:01:30 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 11:01:30 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 12:20:08 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Mon Jul 17 12:20:08 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Mon Jul 17 12:20:09 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Mon Jul 17 12:42:58 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: group key handshake completed (RSN)
Mon Jul 17 16:26:31 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Mon Jul 17 16:26:31 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Mon Jul 17 22:01:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Mon Jul 17 22:01:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Mon Jul 17 22:47:21 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Mon Jul 17 22:47:21 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Mon Jul 17 22:47:21 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Mon Jul 17 22:47:21 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Mon Jul 17 22:47:22 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Mon Jul 17 22:47:22 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 22:47:23 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Mon Jul 17 22:47:23 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 03:53:52 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Tue Jul 18 03:53:52 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Tue Jul 18 04:00:36 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 04:00:36 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Tue Jul 18 04:00:37 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 05:36:31 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 05:36:31 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 05:36:31 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 05:36:31 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 05:37:19 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Tue Jul 18 05:37:19 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 05:37:20 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 05:37:20 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 09:39:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Tue Jul 18 09:39:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Tue Jul 18 11:37:20 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 11:37:20 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 12:42:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: group key handshake completed (RSN)
Tue Jul 18 12:42:58 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: group key handshake completed (RSN)
Tue Jul 18 13:28:27 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 13:28:27 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Tue Jul 18 13:28:28 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 13:33:43 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 13:33:43 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 13:33:43 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 13:33:43 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 13:33:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 13:33:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 13:47:36 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 13:47:36 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Tue Jul 18 13:47:37 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 13:54:51 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 13:54:51 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 13:54:51 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 13:54:51 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 13:54:51 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 13:54:51 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 14:18:04 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 14:18:04 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Tue Jul 18 14:18:05 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 14:21:40 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 14:21:40 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 14:21:40 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 14:21:40 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 14:21:40 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 14:21:40 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 14:31:56 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 14:31:56 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Tue Jul 18 14:31:57 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 14:36:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 14:36:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 14:36:32 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 14:36:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 14:36:32 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 14:36:32 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 14:46:14 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disconnected due to excessive missing ACKs
Tue Jul 18 14:46:14 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 14:46:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 15:03:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 15:03:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 15:03:01 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 15:03:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 15:03:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:03:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:03:03 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:03:03 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:09:00 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 15:09:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Tue Jul 18 15:09:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 15:09:28 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 15:09:28 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 15:09:28 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 15:09:28 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 15:09:28 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:09:28 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:13:40 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 15:13:40 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Tue Jul 18 15:13:41 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 15:13:42 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 15:13:42 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 15:13:42 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 15:13:42 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 15:13:42 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:13:42 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 15:13:53 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Tue Jul 18 15:13:53 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Tue Jul 18 15:33:03 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Tue Jul 18 15:33:03 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Tue Jul 18 15:33:04 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Tue Jul 18 20:57:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Tue Jul 18 20:57:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Tue Jul 18 22:39:43 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Tue Jul 18 22:39:43 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Tue Jul 18 22:39:43 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Tue Jul 18 22:39:43 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Tue Jul 18 22:39:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Tue Jul 18 22:39:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 22:39:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Tue Jul 18 22:39:44 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 00:26:27 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 00:26:27 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Wed Jul 19 00:26:28 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Wed Jul 19 00:49:26 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 00:49:26 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 00:49:26 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 00:49:26 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 00:49:26 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 00:49:26 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 02:40:03 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Wed Jul 19 02:40:03 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Wed Jul 19 03:02:31 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 03:02:31 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Wed Jul 19 03:02:32 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Wed Jul 19 03:03:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 03:03:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 03:03:00 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 03:03:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 03:03:00 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 03:03:00 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 03:33:36 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 03:33:36 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Wed Jul 19 03:33:37 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Wed Jul 19 03:33:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 03:33:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 03:33:58 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 03:33:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 03:33:59 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 03:33:59 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 08:26:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Wed Jul 19 08:26:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Wed Jul 19 09:33:59 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 09:33:59 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 12:17:45 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 12:17:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Wed Jul 19 12:17:46 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Wed Jul 19 12:23:16 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 12:23:16 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 12:23:16 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 12:23:16 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 12:23:16 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 12:23:16 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 12:37:01 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 12:37:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Wed Jul 19 12:37:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Wed Jul 19 12:41:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 12:41:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 12:41:02 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 12:41:02 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 12:41:02 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 12:41:02 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 12:42:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: group key handshake completed (RSN)
Wed Jul 19 12:42:58 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: group key handshake completed (RSN)
Wed Jul 19 13:30:48 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 13:30:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Wed Jul 19 13:30:49 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Wed Jul 19 13:30:55 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 13:30:55 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 13:30:55 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 13:30:55 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 13:30:55 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 13:30:55 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 13:46:49 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Wed Jul 19 13:46:49 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Wed Jul 19 13:51:39 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Wed Jul 19 13:51:39 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Wed Jul 19 19:21:51 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Wed Jul 19 19:21:51 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Wed Jul 19 22:41:18 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Wed Jul 19 22:41:18 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Wed Jul 19 22:41:18 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Wed Jul 19 22:41:18 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Wed Jul 19 22:41:36 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Wed Jul 19 22:41:36 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 22:41:37 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Wed Jul 19 22:41:37 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 01:10:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Thu Jul 20 01:10:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Thu Jul 20 04:45:34 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 04:45:34 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 07:06:30 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Thu Jul 20 07:06:30 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Thu Jul 20 07:06:31 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Thu Jul 20 07:08:33 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Thu Jul 20 07:08:33 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Thu Jul 20 07:08:33 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Thu Jul 20 07:08:33 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Thu Jul 20 07:08:33 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 07:08:33 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 07:36:14 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Thu Jul 20 07:36:14 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Thu Jul 20 10:17:36 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Thu Jul 20 10:17:36 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Thu Jul 20 10:17:37 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Thu Jul 20 12:42:58 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: group key handshake completed (RSN)
Thu Jul 20 13:10:14 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Thu Jul 20 13:10:14 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Thu Jul 20 13:52:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Thu Jul 20 13:52:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Thu Jul 20 13:52:44 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Thu Jul 20 13:52:44 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Thu Jul 20 13:52:45 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 13:52:45 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 14:31:10 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Thu Jul 20 14:31:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Thu Jul 20 14:31:11 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Thu Jul 20 18:31:32 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Thu Jul 20 18:31:32 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Thu Jul 20 21:46:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Thu Jul 20 21:46:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Thu Jul 20 21:46:48 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Thu Jul 20 21:46:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Thu Jul 20 21:47:27 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Thu Jul 20 21:47:27 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 21:47:28 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 21:47:28 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Thu Jul 20 23:40:53 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Thu Jul 20 23:40:53 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Thu Jul 20 23:40:54 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 00:13:55 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Fri Jul 21 00:13:55 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Fri Jul 21 01:09:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 01:09:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 01:09:10 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 01:09:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 01:09:10 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Fri Jul 21 01:09:10 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 01:09:11 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 01:09:11 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 01:09:25 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 01:09:25 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Fri Jul 21 01:09:26 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 01:09:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 01:09:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 01:09:45 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 01:09:45 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 01:09:45 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 01:09:45 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 02:20:34 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 02:20:34 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Fri Jul 21 02:20:35 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 02:20:49 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 02:20:49 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 02:20:49 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 02:20:49 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 02:20:49 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 02:20:49 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 02:21:53 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 02:21:53 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Fri Jul 21 02:21:54 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 02:25:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 02:25:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 02:25:10 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 02:25:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 02:25:10 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 02:25:10 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 03:04:57 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 03:04:57 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 03:04:57 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 03:04:57 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 03:04:57 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 03:04:57 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 04:07:07 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 04:07:07 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Fri Jul 21 04:07:08 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 04:12:15 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 04:12:15 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 04:12:15 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 04:12:15 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 04:12:15 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 04:12:15 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 06:11:37 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Fri Jul 21 06:11:37 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Fri Jul 21 09:26:50 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 09:26:50 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Fri Jul 21 09:26:51 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 09:36:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 09:36:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 09:36:01 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 09:36:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 09:36:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 09:36:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 09:45:23 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 09:45:23 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 09:45:23 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 09:45:23 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 09:45:23 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 09:45:23 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 11:08:46 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 11:08:46 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 11:08:46 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 11:08:46 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 11:08:46 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 11:08:46 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 11:18:48 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 11:18:48 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated
Fri Jul 21 11:18:49 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 11:21:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 11:21:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 11:21:00 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 11:21:00 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 11:21:00 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 11:21:00 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 12:15:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Fri Jul 21 12:15:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 2)
Fri Jul 21 12:15:01 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Fri Jul 21 12:15:01 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Fri Jul 21 12:15:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 12:15:01 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Fri Jul 21 12:42:58 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: group key handshake completed (RSN)
Fri Jul 21 12:42:58 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: group key handshake completed (RSN)
Fri Jul 21 13:04:45 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Fri Jul 21 13:04:45 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Fri Jul 21 13:09:53 2023 daemon.notice hostapd: wlan0: AP-STA-DISCONNECTED f2:60:d2:4c:60:05
Fri Jul 21 13:09:53 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: disassociated due to inactivity
Fri Jul 21 13:09:54 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: deauthenticated due to inactivity (timer DEAUTH/REMOVE)
Fri Jul 21 20:30:02 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Fri Jul 21 20:30:02 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sat Jul 22 02:42:11 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sat Jul 22 02:42:11 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sat Jul 22 08:27:06 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sat Jul 22 08:27:06 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sat Jul 22 08:57:36 2023 daemon.info hostapd: wlan0: STA 1a:f8:d6:90:52:b9 IEEE 802.11: authenticated
Sat Jul 22 08:57:36 2023 daemon.info hostapd: wlan0: STA 1a:f8:d6:90:52:b9 IEEE 802.11: associated (aid 2)
Sat Jul 22 08:57:36 2023 daemon.notice hostapd: wlan0: AP-STA-POSSIBLE-PSK-MISMATCH 1a:f8:d6:90:52:b9
Sat Jul 22 08:57:37 2023 daemon.notice hostapd: wlan0: AP-STA-POSSIBLE-PSK-MISMATCH 1a:f8:d6:90:52:b9
Sat Jul 22 08:57:38 2023 daemon.notice hostapd: wlan0: AP-STA-POSSIBLE-PSK-MISMATCH 1a:f8:d6:90:52:b9
Sat Jul 22 08:57:39 2023 daemon.notice hostapd: wlan0: AP-STA-POSSIBLE-PSK-MISMATCH 1a:f8:d6:90:52:b9
Sat Jul 22 08:57:40 2023 daemon.info hostapd: wlan0: STA c0:d0:12:7e:bc:97 IEEE 802.11: authenticated
Sat Jul 22 08:57:40 2023 daemon.info hostapd: wlan0: STA c0:d0:12:7e:bc:97 IEEE 802.11: associated (aid 2)
Sat Jul 22 08:57:40 2023 daemon.notice hostapd: wlan0: AP-STA-POSSIBLE-PSK-MISMATCH c0:d0:12:7e:bc:97
Sat Jul 22 08:57:41 2023 daemon.notice hostapd: wlan0: AP-STA-POSSIBLE-PSK-MISMATCH c0:d0:12:7e:bc:97
Sat Jul 22 08:57:49 2023 daemon.info hostapd: wlan0: STA c0:d0:12:7e:bc:97 IEEE 802.11: deauthenticated due to local deauth request
Sat Jul 22 12:42:58 2023 daemon.info hostapd: wlan0: STA 3c:22:fb:e6:00:d3 WPA: group key handshake completed (RSN)
Sat Jul 22 12:50:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3
Sat Jul 22 12:50:43 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.236 3c:22:fb:e6:00:d3 MBP-Nikolay-1
Sat Jul 22 15:18:14 2023 daemon.info hostapd: wlan0: STA e6:fa:a2:57:cd:45 IEEE 802.11: authenticated
Sat Jul 22 15:18:14 2023 daemon.info hostapd: wlan0: STA e6:fa:a2:57:cd:45 IEEE 802.11: associated (aid 2)
Sat Jul 22 15:18:14 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED e6:fa:a2:57:cd:45
Sat Jul 22 15:18:14 2023 daemon.info hostapd: wlan0: STA e6:fa:a2:57:cd:45 WPA: pairwise key handshake completed (RSN)
Sat Jul 22 15:18:17 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) e6:fa:a2:57:cd:45
Sat Jul 22 15:18:17 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45
Sat Jul 22 15:18:17 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) e6:fa:a2:57:cd:45
Sat Jul 22 15:18:17 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45
Sat Jul 22 15:18:18 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45
Sat Jul 22 15:18:18 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45 iPhone
Sat Jul 22 15:19:37 2023 daemon.err uhttpd[904]: luci: accepted login on / for root from 192.168.1.236
Sat Jul 22 15:23:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: authenticated
Sat Jul 22 15:23:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 IEEE 802.11: associated (aid 3)
Sat Jul 22 15:23:10 2023 daemon.notice hostapd: wlan0: AP-STA-CONNECTED f2:60:d2:4c:60:05
Sat Jul 22 15:23:10 2023 daemon.info hostapd: wlan0: STA f2:60:d2:4c:60:05 WPA: pairwise key handshake completed (RSN)
Sat Jul 22 15:23:13 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Sat Jul 22 15:23:13 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sat Jul 22 15:23:13 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) f2:60:d2:4c:60:05
Sat Jul 22 15:23:13 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sat Jul 22 15:23:14 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sat Jul 22 15:23:14 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.161 f2:60:d2:4c:60:05
Sat Jul 22 15:40:06 2023 daemon.info dnsmasq-dhcp[1537]: DHCPDISCOVER(br-lan) e6:fa:a2:57:cd:45
Sat Jul 22 15:40:06 2023 daemon.info dnsmasq-dhcp[1537]: DHCPOFFER(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45
Sat Jul 22 15:40:07 2023 daemon.info dnsmasq-dhcp[1537]: DHCPREQUEST(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45
Sat Jul 22 15:40:07 2023 daemon.info dnsmasq-dhcp[1537]: DHCPACK(br-lan) 192.168.1.177 e6:fa:a2:57:cd:45 iPhone
Sat Jul 22 15:56:26 2023 auth.err passwd: password for root changed by root
Sat Jul 22 15:56:29 2023 authpriv.info dropbear[755]: Early exit: Terminated by signal
Sat Jul 22 15:56:29 2023 authpriv.info dropbear[9557]: Not backgrounding

# log from nmap

Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 10:43 MSK
Nmap scan report for google.com (64.233.165.100)
Host is up (0.0087s latency).
Other addresses for google.com (not scanned): 64.233.165.139 64.233.165.113 64.233.165.101 64.233.165.102 64.233.165.138
rDNS record for 64.233.165.100: lg-in-f100.1e100.net

TRACEROUTE (using proto 1/icmp)
HOP RTT     ADDRESS
1   1.65 ms 192.168.1.1
2   5.11 ms 10.146.35.253
3   ... 4
5   2.66 ms 74.125.244.132
6   9.49 ms 216.239.48.163
7   8.19 ms 216.239.46.139
8   ... 16
17  5.67 ms lg-in-f100.1e100.net (64.233.165.100)

Nmap scan report for microsoft.com (20.112.250.133)
Host is up (0.14s latency).
Other addresses for microsoft.com (not scanned): 20.231.239.246 20.76.201.171 20.70.246.20 20.236.44.162

TRACEROUTE (using port 80/tcp)
HOP RTT       ADDRESS
-   Hops 1-2 are the same as for 64.233.165.100
3   ...
4   2.84 ms   ae2-298.RT.BM.SPB.RU.retn.net (87.245.251.8)
5   14.73 ms  ae4-9.RT.TC1.STO.SE.retn.net (87.245.233.73)
6   40.35 ms  retn.ier02.sto.ntwk.msn.net (104.44.47.27)
7   39.34 ms  ae21-0.ear02.sto31.ntwk.msn.net (104.44.239.199)
8   149.65 ms be-23-0.ibr02.sto31.ntwk.msn.net (104.44.22.164)
9   150.13 ms be-6-0.ibr01.ham31.ntwk.msn.net (104.44.29.213)
10  149.73 ms be-3-0.ibr01.ham30.ntwk.msn.net (104.44.28.244)
11  204.56 ms be-12-0.ibr05.ams06.ntwk.msn.net (104.44.30.71)
12  146.82 ms be-3-0.ibr02.ams21.ntwk.msn.net (104.44.29.236)
13  148.24 ms be-1-0.ibr02.ams30.ntwk.msn.net (104.44.16.147)
14  145.12 ms be-15-0.ibr01.lon22.ntwk.msn.net (104.44.31.0)
15  161.50 ms be-7-0.ibr02.nyc30.ntwk.msn.net (104.44.18.154)
16  197.46 ms be-5-0.ibr01.ewr30.ntwk.msn.net (104.44.7.103)
17  145.28 ms be-10-0.ibr02.cle30.ntwk.msn.net (104.44.17.217)
18  145.95 ms be-9-0.ibr01.ch4.ntwk.msn.net (104.44.29.47)
19  176.35 ms be-8-0.ibr03.dsm05.ntwk.msn.net (104.44.28.220)
20  170.16 ms ae212-0.icr07.dsm05.ntwk.msn.net (104.44.32.75)
21  ... 30

Nmap done: 2 IP addresses (2 hosts up) scanned in 8.50 seconds

# All morning log from my terminal

Last login: Tue Jul 25 10:31:48 on ttys000
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % $ 
zsh: command not found: $
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % bash -c "$(curl -fsSL https://raw.githubusercontent.com/tjt263/macports-installer/master/macports-installer.sh)"
Warning: Unknown OS version.
MacPorts-2.3.4--.pkg
MacPorts-2.3.4.chk.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   126  100   126    0     0    525      0 --:--:-- --:--:-- --:--:--   536
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  3396  100  3396    0     0  18213      0 --:--:-- --:--:-- --:--:-- 18762
grep: .bash_profile: No such file or directory
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % sudo port install nmap
Password:
Sorry, try again.
Password:
sudo: port: command not found
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % sudo port install nmap
sudo: port: command not found
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % brew
Example usage:
  brew search TEXT|/REGEX/
  brew info [FORMULA|CASK...]
  brew install FORMULA|CASK...
  brew update
  brew upgrade [FORMULA|CASK...]
  brew uninstall FORMULA|CASK...
  brew list [FORMULA|CASK...]

Troubleshooting:
  brew config
  brew doctor
  brew install --verbose --debug FORMULA|CASK

Contributing:
  brew create URL [--no-fetch]
  brew edit [FORMULA|CASK...]

Further help:
  brew commands
  brew help [COMMAND]
  man brew
  https://docs.brew.sh
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % brew install nmap
Running `brew update --auto-update`...
==> Downloading https://ghcr.io/v2/homebrew/portable-ruby/portable-ruby/blobs/sha256:61029cec31c68a1fae1fa90fa876adf43d0becff777da793f9b5c5577f00567a
######################################################################### 100.0%
==> Pouring portable-ruby-2.6.10_1.el_capitan.bottle.tar.gz
==> Homebrew collects anonymous analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics have been recorded yet (nor will be during this `brew` run).

Installing from the API is now the default behaviour!
You can save space and time by running:
  brew untap homebrew/core
==> Downloading https://formulae.brew.sh/api/formula.jws.json
######################################################################### 100.0%
==> Downloading https://formulae.brew.sh/api/cask.jws.json
######################################################################### 100.0%
==> Auto-updated Homebrew!
Updated 2 taps (homebrew/services and mongodb/brew).

You have 13 outdated formulae installed.

==> Fetching dependencies for nmap: liblinear, ca-certificates, openssl@3, libssh2, lua and pcre
==> Fetching liblinear
==> Downloading https://ghcr.io/v2/homebrew/core/liblinear/manifests/2.47
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/liblinear/blobs/sha256:785f3d2a
######################################################################### 100.0%
==> Fetching ca-certificates
==> Downloading https://ghcr.io/v2/homebrew/core/ca-certificates/manifests/2023-
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/ca-certificates/blobs/sha256:f6
######################################################################### 100.0%
==> Fetching openssl@3
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/3/manifests/3.1.1_1
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/3/blobs/sha256:a123a680
######################################################################### 100.0%
==> Fetching libssh2
==> Downloading https://ghcr.io/v2/homebrew/core/libssh2/manifests/1.11.0_1
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libssh2/blobs/sha256:71b9199fd2
######################################################################### 100.0%
==> Fetching lua
==> Downloading https://ghcr.io/v2/homebrew/core/lua/manifests/5.4.6
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/lua/blobs/sha256:9b7170b3d84e70
######################################################################### 100.0%
==> Fetching pcre
==> Downloading https://ghcr.io/v2/homebrew/core/pcre/manifests/8.45
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pcre/blobs/sha256:df481fdd99c1d
######################################################################### 100.0%
==> Fetching nmap
==> Downloading https://ghcr.io/v2/homebrew/core/nmap/manifests/7.94_1-1
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/nmap/blobs/sha256:769500f197813
######################################################################### 100.0%
==> Installing dependencies for nmap: liblinear, ca-certificates, openssl@3, libssh2, lua and pcre
==> Installing nmap dependency: liblinear
==> Pouring liblinear--2.47.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/liblinear/2.47: 9 files, 335.3KB
==> Installing nmap dependency: ca-certificates
==> Pouring ca-certificates--2023-05-30.ventura.bottle.tar.gz
==> Regenerating CA certificate bundle from keychain, this may take a while...
🍺  /usr/local/Cellar/ca-certificates/2023-05-30: 3 files, 216.2KB
==> Installing nmap dependency: openssl@3
==> Pouring openssl@3--3.1.1_1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/openssl@3/3.1.1_1: 6,495 files, 29.9MB
==> Installing nmap dependency: libssh2
==> Pouring libssh2--1.11.0_1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/libssh2/1.11.0_1: 197 files, 1.1MB
==> Installing nmap dependency: lua
==> Pouring lua--5.4.6.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/lua/5.4.6: 29 files, 711.5KB
==> Installing nmap dependency: pcre
==> Pouring pcre--8.45.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/pcre/8.45: 204 files, 5.7MB
==> Installing nmap
==> Pouring nmap--7.94_1.ventura.bottle.1.tar.gz
==> Caveats
If using `ndiff` returns an error about not being able to import the ndiff module, try:
  chmod go-w /usr/local/Cellar
==> Summary
🍺  /usr/local/Cellar/nmap/7.94_1: 830 files, 26.9MB
==> Running `brew cleanup nmap`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Upgrading 4 dependents of upgraded formulae:
Disable this behaviour by setting HOMEBREW_NO_INSTALLED_DEPENDENTS_CHECK.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
openssl@1.1 1.1.1q -> 1.1.1u, pyenv 2.3.5 -> 2.3.23, python@3.10 3.10.8 -> 3.10.12_1, python@3.9 3.9.15 -> 3.9.17_1
==> Fetching openssl@1.1
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/1.1/manifests/1.1.1u
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/openssl/1.1/blobs/sha256:f0a7ff
######################################################################### 100.0%
==> Fetching pyenv
==> Downloading https://ghcr.io/v2/homebrew/core/pyenv/manifests/2.3.23
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pyenv/blobs/sha256:a10b2c5f70f5
######################################################################### 100.0%
==> Fetching dependencies for python@3.10: sqlite and xz
==> Fetching sqlite
==> Downloading https://ghcr.io/v2/homebrew/core/sqlite/manifests/3.42.0
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/sqlite/blobs/sha256:4bbf2bd9382
######################################################################### 100.0%
==> Fetching xz
==> Downloading https://ghcr.io/v2/homebrew/core/xz/manifests/5.4.3
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/xz/blobs/sha256:b9aebe3c04f5f17
######################################################################### 100.0%
==> Fetching python@3.10
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.10/manifests/3.10.12_1
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.10/blobs/sha256:5529cf
######################################################################### 100.0%
==> Fetching python@3.9
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.9/manifests/3.9.17_1
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.9/blobs/sha256:6b1f500
######################################################################### 100.0%
==> Upgrading openssl@1.1
  1.1.1q -> 1.1.1u 

==> Pouring openssl@1.1--1.1.1u.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/openssl@1.1/1.1.1u: 8,101 files, 18.5MB
==> Running `brew cleanup openssl@1.1`...
Removing: /usr/local/Cellar/openssl@1.1/1.1.1q... (8,097 files, 18.5MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/openssl@1.1--1.1.1q... (5.2MB)
==> Upgrading pyenv
  2.3.5 -> 2.3.23 

==> Pouring pyenv--2.3.23.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/pyenv/2.3.23: 1,096 files, 3.4MB
==> Running `brew cleanup pyenv`...
Removing: /usr/local/Cellar/pyenv/2.3.5... (943 files, 3MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/pyenv--2.3.5... (707.4KB)
==> Upgrading python@3.10
  3.10.8 -> 3.10.12_1 

==> Installing dependencies for python@3.10: sqlite and xz
==> Installing python@3.10 dependency: sqlite
==> Pouring sqlite--3.42.0.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/sqlite/3.42.0: 11 files, 4.5MB
==> Installing python@3.10 dependency: xz
==> Pouring xz--5.4.3.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/xz/5.4.3: 162 files, 2.5MB
==> Installing python@3.10
==> Pouring python@3.10--3.10.12_1.ventura.bottle.tar.gz
==> /usr/local/Cellar/python@3.10/3.10.12_1/bin/python3.10 -Im ensurepip
==> /usr/local/Cellar/python@3.10/3.10.12_1/bin/python3.10 -Im pip install -v --
==> Caveats
Python has been installed as
  /usr/local/bin/python3.10

Unversioned and major-versioned symlinks `python`, `python3`, `python-config`, `python3-config`, `pip`, `pip3`, etc. pointing to
`python3.10`, `python3.10-config`, `pip3.10` etc., respectively, have been installed into
  /usr/local/opt/python@3.10/libexec/bin

You can install Python packages with
  pip3.10 install <package>
They will install into the site-package directory
  /usr/local/lib/python3.10/site-packages

tkinter is no longer included with this formula, but it is available separately:
  brew install python-tk@3.10

If you do not need a specific version of Python, and always want Homebrew's `python3` in your PATH:
  brew install python3

See: https://docs.brew.sh/Homebrew-and-Python
==> Summary
🍺  /usr/local/Cellar/python@3.10/3.10.12_1: 3,097 files, 56.1MB
==> Running `brew cleanup python@3.10`...
Removing: /usr/local/Cellar/python@3.10/3.10.8... (3,114 files, 56.6MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/python@3.10--3.10.8... (14.6MB)
==> Upgrading python@3.9
  3.9.15 -> 3.9.17_1 

==> Pouring python@3.9--3.9.17_1.ventura.bottle.tar.gz
==> /usr/local/Cellar/python@3.9/3.9.17_1/bin/python3.9 -Im ensurepip
==> /usr/local/Cellar/python@3.9/3.9.17_1/bin/python3.9 -Im pip install -v --no-
🍺  /usr/local/Cellar/python@3.9/3.9.17_1: 3,066 files, 55.2MB
==> Running `brew cleanup python@3.9`...
Removing: /usr/local/Cellar/python@3.9/3.9.15... (3,069 files, 55.5MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/python@3.9--3.9.15... (14.4MB)
==> Checking for dependents of upgraded formulae...
==> No broken dependents found!
==> `brew cleanup` has not been run in the last 30 days, running now...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/autoconf--2.71... (944.3KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/c-ares--1.18.1_1... (158.4KB)
Removing: /usr/local/Cellar/ca-certificates/2022-10-11... (3 files, 225.5KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/ca-certificates--2022-10-11... (127.5KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/gdbm--1.23... (270.6KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/icu4c--71.1... (28.2MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/libnghttp2--1.50.0... (209.9KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/libuv--1.44.2... (1.3MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/m4--1.4.19... (263.9KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/mongodb-community--6.0.1.tgz... (57.5MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/mongodb-database-tools--100.6.0.zip... (57.9MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/pkg-config--0.29.2_3... (238.9KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/readline--8.2.1... (547KB)
Removing: /usr/local/Cellar/sqlite/3.39.4... (11 files, 4.4MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/sqlite--3.39.4... (2MB)
Removing: /usr/local/Cellar/xz/5.2.7... (95 files, 1.4MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/xz--5.2.7... (441.8KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/sqlite_bottle_manifest--3.39.4... (6.9KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/libnghttp2_bottle_manifest--1.50.0... (6.3KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/readline_bottle_manifest--8.2.1... (6.7KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/gdbm_bottle_manifest--1.23... (6.1KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/icu4c_bottle_manifest--71.1... (7.1KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/m4_bottle_manifest--1.4.19... (7.0KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/pyenv_bottle_manifest--2.3.5... (22.2KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/openssl@1.1_bottle_manifest--1.1.1q... (7.6KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/python@3.10_bottle_manifest--3.10.8-1... (19.2KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/node@16_bottle_manifest--16.18.0... (13KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/mongosh--1.6.0... (7.9MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/python@3.9_bottle_manifest--3.9.15... (18.5KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/portable-ruby-2.6.8_1.el_capitan.bottle.tar.gz... (8.8MB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/ca-certificates_bottle_manifest--2022-10-11... (1.8KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/c-ares_bottle_manifest--1.18.1_1... (6.3KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/libuv_bottle_manifest--1.44.2... (6.3KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/mongosh_bottle_manifest--1.6.0... (16.6KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/autoconf_bottle_manifest--2.71... (9.4KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/xz_bottle_manifest--5.2.7... (6.4KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/pkg-config_bottle_manifest--0.29.2_3... (7.4KB)
Removing: /Users/nikolaysalinder/Library/Caches/Homebrew/node@16--16.18.0... (13MB)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/pyenv... (64B)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/pkg-config... (64B)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/icu4c... (64B)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/autoconf... (64B)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/m4... (64B)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/openssl@1.1... (64B)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/python@3.10... (2 files, 2.5KB)
Removing: /Users/nikolaysalinder/Library/Logs/Homebrew/python@3.9... (4 files, 4.8KB)
Error: Permission denied @ apply2files - /usr/local/lib/docker/cli-plugins
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % mkdir -p /Applications/Docker.app/Contents/Resources/cli-plugins
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % brew cleanup
Warning: Skipping c-ares: most recent version 1.19.1 not installed
Warning: Skipping icu4c: most recent version 73.2 not installed
Warning: Skipping libnghttp2: most recent version 1.55.1 not installed
Warning: Skipping libuv: most recent version 1.46.0 not installed
Warning: Skipping mongodb/brew/mongodb-community: most recent version 6.0.6 not installed
Warning: Skipping mongodb/brew/mongodb-database-tools: most recent version 100.7.3 not installed
Pruned 0 symbolic links and 4 directories from /usr/local

Removing: /usr/local/Homebrew/Library/Homebrew/vendor/portable-ruby/2.6.8_1... (1,393 files, 24.4MB)
Removing: /usr/local/Homebrew/Library/Homebrew/vendor/portable-ruby/2.6.8... (1,393 files, 24.5MB)
Removing: /usr/local/Homebrew/Library/Homebrew/vendor/portable-ruby/2.6.10_1... (1,393 files, 24.2MB)
==> This operation has freed approximately 73.2MB of disk space.
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % nmap
Nmap 7.94 ( https://nmap.org )
Usage: nmap [Scan Type(s)] [Options] {target specification}
TARGET SPECIFICATION:
  Can pass hostnames, IP addresses, networks, etc.
  Ex: scanme.nmap.org, microsoft.com/24, 192.168.0.1; 10.0.0-255.1-254
  -iL <inputfilename>: Input from list of hosts/networks
  -iR <num hosts>: Choose random targets
  --exclude <host1[,host2][,host3],...>: Exclude hosts/networks
  --excludefile <exclude_file>: Exclude list from file
HOST DISCOVERY:
  -sL: List Scan - simply list targets to scan
  -sn: Ping Scan - disable port scan
  -Pn: Treat all hosts as online -- skip host discovery
  -PS/PA/PU/PY[portlist]: TCP SYN/ACK, UDP or SCTP discovery to given ports
  -PE/PP/PM: ICMP echo, timestamp, and netmask request discovery probes
  -PO[protocol list]: IP Protocol Ping
  -n/-R: Never do DNS resolution/Always resolve [default: sometimes]
  --dns-servers <serv1[,serv2],...>: Specify custom DNS servers
  --system-dns: Use OS's DNS resolver
  --traceroute: Trace hop path to each host
SCAN TECHNIQUES:
  -sS/sT/sA/sW/sM: TCP SYN/Connect()/ACK/Window/Maimon scans
  -sU: UDP Scan
  -sN/sF/sX: TCP Null, FIN, and Xmas scans
  --scanflags <flags>: Customize TCP scan flags
  -sI <zombie host[:probeport]>: Idle scan
  -sY/sZ: SCTP INIT/COOKIE-ECHO scans
  -sO: IP protocol scan
  -b <FTP relay host>: FTP bounce scan
PORT SPECIFICATION AND SCAN ORDER:
  -p <port ranges>: Only scan specified ports
    Ex: -p22; -p1-65535; -p U:53,111,137,T:21-25,80,139,8080,S:9
  --exclude-ports <port ranges>: Exclude the specified ports from scanning
  -F: Fast mode - Scan fewer ports than the default scan
  -r: Scan ports sequentially - don't randomize
  --top-ports <number>: Scan <number> most common ports
  --port-ratio <ratio>: Scan ports more common than <ratio>
SERVICE/VERSION DETECTION:
  -sV: Probe open ports to determine service/version info
  --version-intensity <level>: Set from 0 (light) to 9 (try all probes)
  --version-light: Limit to most likely probes (intensity 2)
  --version-all: Try every single probe (intensity 9)
  --version-trace: Show detailed version scan activity (for debugging)
SCRIPT SCAN:
  -sC: equivalent to --script=default
  --script=<Lua scripts>: <Lua scripts> is a comma separated list of
           directories, script-files or script-categories
  --script-args=<n1=v1,[n2=v2,...]>: provide arguments to scripts
  --script-args-file=filename: provide NSE script args in a file
  --script-trace: Show all data sent and received
  --script-updatedb: Update the script database.
  --script-help=<Lua scripts>: Show help about scripts.
           <Lua scripts> is a comma-separated list of script-files or
           script-categories.
OS DETECTION:
  -O: Enable OS detection
  --osscan-limit: Limit OS detection to promising targets
  --osscan-guess: Guess OS more aggressively
TIMING AND PERFORMANCE:
  Options which take <time> are in seconds, or append 'ms' (milliseconds),
  's' (seconds), 'm' (minutes), or 'h' (hours) to the value (e.g. 30m).
  -T<0-5>: Set timing template (higher is faster)
  --min-hostgroup/max-hostgroup <size>: Parallel host scan group sizes
  --min-parallelism/max-parallelism <numprobes>: Probe parallelization
  --min-rtt-timeout/max-rtt-timeout/initial-rtt-timeout <time>: Specifies
      probe round trip time.
  --max-retries <tries>: Caps number of port scan probe retransmissions.
  --host-timeout <time>: Give up on target after this long
  --scan-delay/--max-scan-delay <time>: Adjust delay between probes
  --min-rate <number>: Send packets no slower than <number> per second
  --max-rate <number>: Send packets no faster than <number> per second
FIREWALL/IDS EVASION AND SPOOFING:
  -f; --mtu <val>: fragment packets (optionally w/given MTU)
  -D <decoy1,decoy2[,ME],...>: Cloak a scan with decoys
  -S <IP_Address>: Spoof source address
  -e <iface>: Use specified interface
  -g/--source-port <portnum>: Use given port number
  --proxies <url1,[url2],...>: Relay connections through HTTP/SOCKS4 proxies
  --data <hex string>: Append a custom payload to sent packets
  --data-string <string>: Append a custom ASCII string to sent packets
  --data-length <num>: Append random data to sent packets
  --ip-options <options>: Send packets with specified ip options
  --ttl <val>: Set IP time-to-live field
  --spoof-mac <mac address/prefix/vendor name>: Spoof your MAC address
  --badsum: Send packets with a bogus TCP/UDP/SCTP checksum
OUTPUT:
  -oN/-oX/-oS/-oG <file>: Output scan in normal, XML, s|<rIpt kIddi3,
     and Grepable format, respectively, to the given filename.
  -oA <basename>: Output in the three major formats at once
  -v: Increase verbosity level (use -vv or more for greater effect)
  -d: Increase debugging level (use -dd or more for greater effect)
  --reason: Display the reason a port is in a particular state
  --open: Only show open (or possibly open) ports
  --packet-trace: Show all packets sent and received
  --iflist: Print host interfaces and routes (for debugging)
  --append-output: Append to rather than clobber specified output files
  --resume <filename>: Resume an aborted scan
  --noninteractive: Disable runtime interactions via keyboard
  --stylesheet <path/URL>: XSL stylesheet to transform XML output to HTML
  --webxml: Reference stylesheet from Nmap.Org for more portable XML
  --no-stylesheet: Prevent associating of XSL stylesheet w/XML output
MISC:
  -6: Enable IPv6 scanning
  -A: Enable OS detection, version detection, script scanning, and traceroute
  --datadir <dirname>: Specify custom Nmap data file location
  --send-eth/--send-ip: Send using raw ethernet frames or IP packets
  --privileged: Assume that the user is fully privileged
  --unprivileged: Assume the user lacks raw socket privileges
  -V: Print version number
  -h: Print this help summary page.
EXAMPLES:
  nmap -v -A scanme.nmap.org
  nmap -v -sn 192.168.0.0/16 10.0.0.0/8
  nmap -v -iR 10000 -Pn -p 80
SEE THE MAN PAGE (https://nmap.org/book/man.html) FOR MORE OPTIONS AND EXAMPLES
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % nmap -sn --traceroute google.com microsoft.com
Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 10:43 MSK
Traceroute has to be run as root
QUITTING!
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % root nmap -sn --traceroute google.com microsoft.com
zsh: command not found: root
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % sudo nmap -sn --traceroute google.com microsoft.com
Password:
Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 10:43 MSK
Nmap scan report for google.com (64.233.165.100)
Host is up (0.0087s latency).
Other addresses for google.com (not scanned): 64.233.165.139 64.233.165.113 64.233.165.101 64.233.165.102 64.233.165.138
rDNS record for 64.233.165.100: lg-in-f100.1e100.net

TRACEROUTE (using proto 1/icmp)
HOP RTT     ADDRESS
1   1.65 ms 192.168.1.1
2   5.11 ms 10.146.35.253
3   ... 4
5   2.66 ms 74.125.244.132
6   9.49 ms 216.239.48.163
7   8.19 ms 216.239.46.139
8   ... 16
17  5.67 ms lg-in-f100.1e100.net (64.233.165.100)

Nmap scan report for microsoft.com (20.112.250.133)
Host is up (0.14s latency).
Other addresses for microsoft.com (not scanned): 20.231.239.246 20.76.201.171 20.70.246.20 20.236.44.162

TRACEROUTE (using port 80/tcp)
HOP RTT       ADDRESS
-   Hops 1-2 are the same as for 64.233.165.100
3   ...
4   2.84 ms   ae2-298.RT.BM.SPB.RU.retn.net (87.245.251.8)
5   14.73 ms  ae4-9.RT.TC1.STO.SE.retn.net (87.245.233.73)
6   40.35 ms  retn.ier02.sto.ntwk.msn.net (104.44.47.27)
7   39.34 ms  ae21-0.ear02.sto31.ntwk.msn.net (104.44.239.199)
8   149.65 ms be-23-0.ibr02.sto31.ntwk.msn.net (104.44.22.164)
9   150.13 ms be-6-0.ibr01.ham31.ntwk.msn.net (104.44.29.213)
10  149.73 ms be-3-0.ibr01.ham30.ntwk.msn.net (104.44.28.244)
11  204.56 ms be-12-0.ibr05.ams06.ntwk.msn.net (104.44.30.71)
12  146.82 ms be-3-0.ibr02.ams21.ntwk.msn.net (104.44.29.236)
13  148.24 ms be-1-0.ibr02.ams30.ntwk.msn.net (104.44.16.147)
14  145.12 ms be-15-0.ibr01.lon22.ntwk.msn.net (104.44.31.0)
15  161.50 ms be-7-0.ibr02.nyc30.ntwk.msn.net (104.44.18.154)
16  197.46 ms be-5-0.ibr01.ewr30.ntwk.msn.net (104.44.7.103)
17  145.28 ms be-10-0.ibr02.cle30.ntwk.msn.net (104.44.17.217)
18  145.95 ms be-9-0.ibr01.ch4.ntwk.msn.net (104.44.29.47)
19  176.35 ms be-8-0.ibr03.dsm05.ntwk.msn.net (104.44.28.220)
20  170.16 ms ae212-0.icr07.dsm05.ntwk.msn.net (104.44.32.75)
21  ... 30

Nmap done: 2 IP addresses (2 hosts up) scanned in 8.50 seconds
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % nmap -sP 192.168.2.0/24
Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 10:50 MSK
Nmap done: 256 IP addresses (0 hosts up) scanned in 206.53 seconds
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % 
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % sudo nmap -sn --traceroute google.com microsoft.com
Password:
Sorry, try again.
Password:
Sorry, try again.
Password:
Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 11:41 MSK
Failed to resolve "google.com".
Failed to resolve "microsoft.com".
WARNING: No targets were specified, so 0 hosts scanned.
Nmap done: 0 IP addresses (0 hosts up) scanned in 0.00 seconds
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % stacktrace
zsh: command not found: stacktrace
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % stacktrace
zsh: command not found: stacktrace
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % nmap -sn --traceroute google.com microsoft.com

Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 11:50 MSK
Traceroute has to be run as root
QUITTING!
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % sudo nmap -sn --traceroute google.com microsoft.com

Password:
Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 11:50 MSK
Nmap scan report for google.com (173.194.222.139)
Host is up (0.0044s latency).
Other addresses for google.com (not scanned): 173.194.222.100 173.194.222.102 173.194.222.138 173.194.222.113 173.194.222.101
rDNS record for 173.194.222.139: lo-in-f139.1e100.net

TRACEROUTE (using proto 1/icmp)
HOP RTT     ADDRESS
1   5.43 ms 10.146.35.253
2   ... 3
4   1.67 ms 74.125.244.180
5   4.46 ms 216.239.48.163
6   6.56 ms 172.253.51.219
7   ... 15
16  4.40 ms lo-in-f139.1e100.net (173.194.222.139)

Nmap scan report for microsoft.com (20.112.250.133)
Host is up (0.15s latency).
Other addresses for microsoft.com (not scanned): 20.231.239.246 20.76.201.171 20.70.246.20 20.236.44.162

TRACEROUTE (using port 80/tcp)
HOP RTT       ADDRESS
-   Hop 1 is the same as for 173.194.222.139
2   ...
3   1.06 ms   ae2-298.RT.BM.SPB.RU.retn.net (87.245.251.8)
4   12.27 ms  ae4-9.RT.TC1.STO.SE.retn.net (87.245.233.73)
5   39.84 ms  retn.ier01.sto.ntwk.msn.net (104.44.47.25)
6   39.91 ms  ae21-0.ear01.sto31.ntwk.msn.net (104.44.239.193)
7   145.43 ms be-22-0.ibr01.sto31.ntwk.msn.net (104.44.22.162)
8   149.46 ms be-6-0.ibr01.ham31.ntwk.msn.net (104.44.29.213)
9   145.76 ms be-3-0.ibr01.ham30.ntwk.msn.net (104.44.28.244)
10  143.27 ms be-12-0.ibr05.ams06.ntwk.msn.net (104.44.30.71)
11  149.66 ms be-7-0.ibr02.nyc30.ntwk.msn.net (104.44.18.154)
12  273.04 ms be-1-0.ibr01.ams30.ntwk.msn.net (104.44.16.149)
13  237.79 ms be-15-0.ibr01.lon22.ntwk.msn.net (104.44.31.0)
14  149.90 ms be-11-0.ibr02.ch4.ntwk.msn.net (104.44.29.45)
15  146.99 ms be-7-0.ibr04.dsm05.ntwk.msn.net (104.44.28.222)
16  152.10 ms ae160-0.icr03.dsm05.ntwk.msn.net (104.44.22.206)
17  148.50 ms be-1-0.ibr02.cle30.ntwk.msn.net (104.44.7.90)
18  ... 29
30  151.73 ms 20.112.250.133

Nmap done: 2 IP addresses (2 hosts up) scanned in 8.83 seconds
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % sudo nmap -sn --traceroute google.com microsoft.com

Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 11:51 MSK
Nmap scan report for google.com (173.194.222.139)
Host is up (0.043s latency).
Other addresses for google.com (not scanned): 173.194.222.100 173.194.222.102 173.194.222.138 173.194.222.113 173.194.222.101
rDNS record for 173.194.222.139: lo-in-f139.1e100.net

TRACEROUTE (using port 80/tcp)
HOP RTT      ADDRESS
1   43.58 ms 10.146.35.253
2   ... 3
4   39.77 ms 74.125.244.180
5   44.34 ms 142.251.61.219
6   44.50 ms 142.251.61.221
7   46.12 ms 172.253.51.243
8   ... 16
17  43.44 ms lo-in-f139.1e100.net (173.194.222.139)

Nmap scan report for microsoft.com (20.112.250.133)
Host is up (0.19s latency).
Other addresses for microsoft.com (not scanned): 20.231.239.246 20.76.201.171 20.70.246.20 20.236.44.162

TRACEROUTE (using proto 1/icmp)
HOP RTT       ADDRESS
-   Hop 1 is the same as for 173.194.222.139
2   ...
3   39.83 ms  ae2-298.RT.BM.SPB.RU.retn.net (87.245.251.8)
4   53.46 ms  ae4-9.RT.TC1.STO.SE.retn.net (87.245.233.73)
5   77.72 ms  retn.ier02.sto.ntwk.msn.net (104.44.47.27)
6   78.92 ms  ae21-0.ear02.sto31.ntwk.msn.net (104.44.239.199)
7   183.03 ms be-24-0.ibr01.sto31.ntwk.msn.net (104.44.22.170)
8   190.30 ms be-6-0.ibr01.ham31.ntwk.msn.net (104.44.29.213)
9   185.30 ms be-3-0.ibr01.ham30.ntwk.msn.net (104.44.28.244)
10  229.70 ms be-12-0.ibr05.ams06.ntwk.msn.net (104.44.30.71)
11  182.24 ms be-11-0.ibr01.ams21.ntwk.msn.net (104.44.29.242)
12  184.88 ms be-1-0.ibr01.ams30.ntwk.msn.net (104.44.16.149)
13  182.14 ms be-15-0.ibr01.lon22.ntwk.msn.net (104.44.31.0)
14  184.67 ms be-10-0.ibr01.nyc30.ntwk.msn.net (104.44.18.152)
15  184.46 ms be-5-0.ibr01.ewr30.ntwk.msn.net (104.44.7.103)
16  184.29 ms be-8-0.ibr01.cle30.ntwk.msn.net (104.44.17.201)
17  186.70 ms be-1-0.ibr02.cle30.ntwk.msn.net (104.44.7.90)
18  185.32 ms be-11-0.ibr02.ch4.ntwk.msn.net (104.44.29.45)
19  181.76 ms be-7-0.ibr04.dsm05.ntwk.msn.net (104.44.28.222)
20  196.10 ms ae160-0.icr03.dsm05.ntwk.msn.net (104.44.22.206)
21  ... 25
26  185.68 ms 20.112.250.133

Nmap done: 2 IP addresses (2 hosts up) scanned in 7.47 seconds
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % nmap -sn --traceroute google.com microsoft.com     

# My terminal commands
 1  git checkout vitaliy
    2  git checkout -b "nikolay"
    3  npm i
    4  npm run dev
    5  git status
    6  git commit "Add 2 pages"
    7  git add .
    8  git commit -m "Add 2 pages"
    9  git checkout vitaliy
   10  npm run start:dev
   11  ды
   12  ls
   13  cd Desktop
   14  ls
   15  cd Educate
   16  ls
   17  cd udemy
   18  ls
   19  npm i -g @nestjs/cli
   20  nest new Vue3Nuxt.jsandNestJS:ARapidGuide-Advanced\n
   21  ls
   22  cd vue3-nuxt.jsand-nest-js:arapid-guide-advanced
   23  ls
   24  ls
   25  cd ..
   26  ls
   27  cd ..
   28  cd ..
   29  ls
   30  cd Projects
   31  git clone git@github.com:nikolaysalinder/currency.git
   32  cd currency
   33  ls
   34  node -v
   35  nvm
   36  nvm use 14
   37  vue --version
   38  vue create .
   39  yarn
   40  nvm use 15
   41  nvm
   42  nvm install 14
   43  nvm install 14
   44  yarn
   45  npm i yarn
   46  yarn 
   47  npm install --global yarn
   48  yarn 
   49  yarn 
   50  yarn
   51  yarn serve
   52  yarn add vue-multiselect
   53  yarn serve
   54  yarn remove vue-multiselect
   55  yarn add vue-multiselect@next
   56  yarn serve
   57  nvm
   58  node -v
   59  yarn serve
   60  npm i
   61  npm run serve
   62  git status
   63  git checkout -b "Nikolay"
   64  npm run serve
   65  git status
   66  npm run serve
   67  git status
   68  git add .
   69  git commit -m "End first task"
   70  npm run serve
   71  npm install @dansmaculotte/vue-crisp-chat --save
   72  npm run serve
   73  git status
   74  git add .
   75  git commit -m "Add assistang plug-in"
   76  git status
   77  git branc
   78  git branch
   79  git merge master
   80  git status
   81  git push
   82  git push --set-upstream origin Nikolay
   83  npm run serve
   84  npm run serve
   85  npm run serve
   86  vue create .
   87  vue create .
   88  npm run serve
   89  node --v
   90  node -v
   91  nvm
   92  nvm use 14
   93  npm run serve
   94  npm i
   95  npm run serve
   96  npm run serve
   97  node -v
   98  nvm use 14
   99  npm run serve
  100  git status
  101  git add .
  102  git commit -m "Added children module"
  103  git status
  104  git push
  105  git status
  106  git add .
  107  git commit -m "Change label for children adding"
  108  git push
  109  npm run serve
  110  git status
  111  git add .
  112  git commit -m "Fix parent name"
  113  git push
  114  nvm
  115  nvm use 14
  116  npm run serve
  117  npm i
  118  npm run serve
  119  npm run serve
  120  node -v
  121  nvm use 14
  122  npm run serve
  123  npm run serve
  124  git status
  125  git checkout src/components/ActivityCard.vue master
  126  git log
  127  git diff
  128  git status
  129  git checkout master src/components/ActivityCard.vue
  130  npm run serve
  131  ls
  132  cd Desktop
  133  ls
  134  cd Work
  135  git clone git@github.com:skkap/lookback-frontend.git
  136  ls
  137  cd ..
  138  ls
  139  cd Projects
  140  ls
  141  git clone git@github.com:nikolaysalinder/test-work.git
  142  git clone git@github.com:nikolaysalinder/test-work.git
  143  ls
  144  vue create
  145  vue create game
  146  npm run serve
  147  git status
  148  git add .
  149  git commit -m "Fix ussues"
  150  git push
  151  npm run dev
  152  npm run serve
  153  git status
  154  git add .
  155  git commit -m "delete unusefull code"
  156  git push
  157  npm run serve
  158  git status
  159  npm run serve
  160  npm run serve
  161  npm run serve
  162  npm run serve
  163  git status
  164  git add .
  165  git commit -m "Fix Activity card"
  166  npm run serve
  167  git status
  168  git add .
  169  git commit -m "Add shadow and set width"
  170  git push
  171  npm run serve
  172  git status
  173  git checkout master src/views/SingleActivity.vue
  174  npm run serve
  175  git status
  176  git add .
  177  git commit -m "fix tab shadow"
  178  git push
  179  git status
  180  npm run serve
  181  npm run start
  182  npm run start:dev
  183  git clone git@github.com:AlliKalykov/qrc.git
  184  python
  185  python3
  186  locate bin/postgres
  187  postgres
  188  Postgress
  189  su - postgres
  190  su - postgres
  191  su - postgres
  192  su - postgres
  193  postgress
  194  su - postgres
  195  sudo -u postgres psql
  196  sudo nano /etc/postgresql/14/main/pg_hba.conf
  197  ls
  198  cd etc
  199  cd /etc
  200  ls
  201  cd postgres
  202  cd postgresql
  203  cd
  204  postgres
  205  su - postgres
  206  su - postgres
  207  su - postgres
  208  /usr/lib/postgresql/14/bin/postgres -V
  209  \tcd /etc
  210  ls
  211  cd /var
  212  ls
  213  cd lib
  214  ls
  215  cd 
  216  postgress
  217  postgres
  218  psql
  219  cd /var/
  220  ls
  221  cd lib
  222  ls
  223  cd /Library
  224  ls
  225  cd PostgreSQL
  226  ls
  227  cd 14
  228  ls
  229  cd data
  230  sudo cd data
  231  sudo cd data
  232  cd data
  233  sudo cd data
  234  ls
  235  ps aux | grep postgres
  236  SHOW hba_file;
  237  ps -ef | grep postgres
  238  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  239  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  240  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  241  sudo service postgresql reload
  242  sudo service postgresql reload
  243  su service postgresql reload
  244  sudo service postgresql reload
  245  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  246  sudo service postgresql reload
  247  /usr/local/var/postgres restart
  248  brew services restart postgres
  249  pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log restart
  250  sudo -u postgres /Library/PostgreSQL/14/bin/pg_ctl -D /Library/PostgreSQL/14/data restart
  251  postgress
  252  postgres
  253  psql
  254  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  255  sudo -u postgres psql
  256  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  257  /Library/PostgreSQL/14/bin/pg_ctl restart -D /Library/PostgreSQL/14/data/
  258  sudo /Library/PostgreSQL/14/bin/pg_ctl restart -D /Library/PostgreSQL/14/data/
  259  su /Library/PostgreSQL/14/bin/pg_ctl restart -D /Library/PostgreSQL/14/data/
  260  su /Library/PostgreSQL/14/bin/pg_ctl restart -D /Library/PostgreSQL/14/data/
  261  su /Library/PostgreSQL/14/bin/pg_ctl restart -D /Library/PostgreSQL/14/data/
  262  sudo nano /Library/PostgreSQL/14/data/pg_hba.conf
  263  sudo -u postgres psql
  264  /Library/PostgreSQL/14/uninstall-postgresql.app
  265  sudo /Library/PostgreSQL/14/uninstall-postgresql.app
  266  sudo /Library/PostgreSQL/14/uninstall-postgresql,app/Contents/MAacOs/installbuilder.sh
  267  sudo /Library/PostgreSQL/14/uninstall-postgresql
  268  sudo /Library/PostgreSQL/14/uninstall-postgresql,app/Contents/MAacOs/installbuilder.sh
  269  sudo /Library/PostgreSQL/14/uninstall-postgresql.app/Contents/MacOS/installbuilder.sh
  270  sudo rm -rf /Library/PostgreSQL
  271  sudo rm /etc/postgres-reg.ini
  272  sudo rm /etc/sysctl.conf
  273  brew install posgres
  274  cd 
  275  brew install postgres
  276  brew update
  277  sudo nano /Library/PostgreSQL/14/data/config.py
  278  sudo /Library/PostgreSQL/9.1/uninstall-postgresql.app/Contents/MacOS/installbuilder.sh
  279  sudo /Library/PostgreSQL/14/uninstall-postgresql.app/Contents/MacOS/installbuilder.sh
  280  sudo rm -rf /Library/PostgreSQL
  281  sudo rm /etc/postgres-reg.ini
  282  sudo rm /etc/sysctl.conf
  283  sudo mkdir -p /etc/paths.d &&\necho /Applications/Postgres.app/Contents/Versions/latest/bin | sudo tee /etc/paths.d/postgresapp
  284  psql -U postgres
  285  vue create .
  286  pip install virtualenv
  287  virtualenv venv
  288  python3 -m venv venv
  289  source venv/bin/activate
  290  cd ..
  291  ls
  292  pip install virtualenv
  293  pip3 install virtualenv
  294  virtualenv venv
  295  virtualenv -p python3 venv
  296  python3 -m venv venv
  297  source venv/bin/activate
  298  pip install -r requirements.txt
  299  pip freeze
  300  python manage.py runserver
  301  locate bin/postgres
  302  locate bin/postgres
  303  python manage.py runserver
  304  python manage.py migrate
  305  python manage.py createsuperuser
  306  python manage.py runserver
  307  python manage.py runserver
  308  python manage.py runserver
  309  python3 manage.py runserver
  310  source venv/bin/activate
  311  python3 manage.py runserver
  312  python3 manage.py runserver
  313  source venv/bin/activate
  314  python3 manage.py runserver
  315  git pull
  316  git fetch
  317  git branch
  318  vue create .
  319  npm i yarn
  320  vue create .
  321  git status
  322  nvm
  323  nvm use 14
  324  nvm alias default 14
  325  vue create .
  326  git status
  327  git add .
  328  git commit -m "Init project"
  329  git pull
  330  git push
  331  git push
  332  git checkout -b dev
  333  yarn dev
  334  yarn
  335  yarn serve
  336  git clone git@github.com:AlliKalykov/qrc.git
  337  DEBUG=on\nSECRET_KEY=django-insecure-632z#yb6)@riza#xh*n3j3&(0g^rishbpg-!k@*5*04xw9i(4o\nDATABASE_URL=psql://qrc:qrc@127.0.0.1:5432/qrc
  338  git clone git@github.com:AlliKalykov/qrc_front.git
  339  git clone git@github.com:AlliKalykov/qrc_front.git
  340  cd qrc
  341  source venv/bin/activate
  342  virtualenv venv
  343  virtualenv -p python3 venv
  344  python3 -m venv venv
  345  python3 -m venv venv
  346  python3 -m venv venv
  347  python3 manage.py runserver
  348  python manage.py runserver
  349  source venv/bin/activate
  350  python manage.py runserver
  351  python3 manage.py runserver
  352  python manage.py runserver
  353  deactivate
  354  source venv/bin/activate
  355  python manage.py runserver
  356  python manage.py runserver
  357  python3 manage.py runserver
  358  python
  359  ls
  360  pip freezy
  361  pip freeze
  362  pip install -r requirenments.txt
  363  pip install -r requirements.txt
  364  python manage.py runserver
  365  exit
  366  ssh nick@151.115.55.2
  367  docker exec -it 104170fe4762e1c1f0838a950a93ca602b7d4d6fe759af1ca1ad9f0fbc9716c0 /bin/sh
  368  gulp
  369  npm i
  370  gulp
  371  yarn serve
  372  yarn serve
  373  rsync --archive --chown=nick:nick ~/.ssh /home/nick
  374  ls
  375  cd Desktop
  376  ls
  377  cd Projects
  378  ls
  379  git clone git@github.com:nikolaysalinder/zealous.foggystar.com.git
  380  ls
  381  ls
  382  mkdir wpwebsite
  383  cd zealous.foggystar.com
  384  touch docker-compose.yaml
  385  sudo nano docker-compose.yaml
  386  docker-compose up
  387  docker-compose up
  388  docker-compose up
  389  docker run -d -p 80:80 docker/getting-started
  390  docker-compose up
  391  docker-compose up
  392  docker ps
  393  docker kill $(docker ps -q)
  394  docker ps
  395  ls
  396  mkdir verstka
  397  cd verstka
  398  cd ..
  399  git clone git@github.com:nikolaysalinder/gulp4-starter.gi
  400  git clone git@github.com:nikolaysalinder/gulp4-starter.git
  401  cd gulp4-starter
  402  cd ..
  403  mv gulp4-starter verstka
  404  ls
  405  cd verstka
  406  ls
  407  ls
  408  cd ..
  409  cd ..
  410  ls
  411  cd wpwebsite
  412  ls
  413  sudo nano docker-compose.yaml
  414  ls
  415  docker-compose up
  416  docker ps
  417  cd ..
  418  ls
  419  cd zealous.foggystar.com
  420  docker-compose up
  421  docker rm $(docker ps -a -q)
  422  docker-compose up
  423  docker rmi $(docker images -q)
  424  docker rmi $(docker images -q)
  425  docker kill $(docker ps -q)
  426  docker-compose up
  427  pbcopy < ~/.ssh/id_rsa.pub
  428  ssh root@151.115.55.2
  429  ды
  430  ls
  431  cd ~/.ssh
  432  ls
  433  sudo nano id_ed25519.pub
  434  cd
  435  ssh root@151.115.55.2
  436  ssh root@151.115.55.2
  437  ssh root@151.115.55.2
  438  ssh root@151.115.55.2
  439  cd /opt/letsencrypt
  440  ssh root@151.115.55.2
  441  ssh root@151.115.55.2
  442  ssh root@151.115.55.2
  443  ssh root@151.115.55.2
  444  ssh root@151.115.55.2
  445  docker stop $(docker ps -a -q)
  446  docker rm $(docker ps -a -q)
  447  mkdir test-work3
  448  cd test-work3
  449  ls
  450  vue create .
  451  yarn serve
  452  yarn serve
  453  ssh root@151.115.55.2
  454  cd root@172.67.218.212
  455  ssh root@172.67.218.212
  456  cd app
  457  yarn dev
  458  yarn create nuxt-app <project-name
  459  yarn create nuxt-app .
  460  yarn dev
  461  yarn add aframe
  462  yarn dev
  463  yarn dev
  464  yarn serve
  465  yarn serve
  466  yarn dev
  467  yarn dev
  468  ls
  469  cd Desktop
  470  cd pr
  471  cd Projects
  472  ls
  473  git clone git@github.com:nikolaysalinder/visualspace.git
  474  git status
  475  git clone git@github.com:nikolaysalinder/card-game.git
  476  vue create antd-demo
  477  cd ..
  478  cd kReisereporter
  479  rm -rf antd-demo
  480  vue create antd-demo
  481  vue create .
  482  vue create antd-demo
  483   npm i --save ant-design-vue
  484  git status
  485  git add .
  486  git commit -m "Initial commit"
  487  git checkout -b develop
  488  git checkout -b layouts
  489  git status
  490  git push
  491  git push --set-upstream origin layouts
  492  npm i --save ant-design-vue
  493  nvm -v
  494  nvm
  495  nvm alias default 16
  496  nvm use 16
  497  npm run serve
  498  npm rebuild node-sass
  499  npm run serve
  500  nvm use 14
  501  nvm alias default 14
  502  nvm use 14
  503  npm run serve
  504  npm i @ant-design/icons-vue
  505  npm run serve
  506  npx nuxi init .
  507  ls
  508  cd ..
  509  ls
  510  cd proje
  511  cd Projects
  512  npx nuxi init nuxt-a-frame
  513  yarn install
  514  cd nuxt-a-frame
  515  yarn install
  516  pbcopy < ~/.ssh/id_rsa.pub
  517  ssh root@78.40.216.83
  518  ssh nick@78.40.216.83
  519  ssh nick@78.40.216.83
  520  ssh nick@78.40.216.83
  521  ssh nick@78.40.216.83
  522  ssh-copy-id nick@78.40.216.83
  523  ssh nick@78.40.216.83
  524  ssh nick@78.40.216.83
  525  ssh root@78.40.216.71
  526  ssh nick@78.40.216.71
  527  ls
  528  cd Downloads
  529  ls
  530  pwd
  531  ssh nick@78.40.216.71
  532  ssh nick@78.40.216.71
  533  ssh nick@78.40.216.71
  534  ssh nick@78.40.216.71
  535  ssh-copy-id nick@78.40.216.71
  536  ssh nick@78.40.216.71
  537  ssh nick@78.40.216.71
  538  ssh nick@78.40.216.71
  539  scp root@78.40.216.71:/home/VPN/configs/Mac-Nick.conf /Users/nikolaysalinder/Downloads
  540  ssh root@78.40.216.71:/Home/VPN/configs/Mac-Nick.conf /Users/nikolaysalinder/Downloads
  541  ssh root@78.40.216.71
  542  nick@78.40.216.71
  543  ssh nick@78.40.216.71
  544  ssh nick@78.40.216.71
  545  ssh root@85.193.93.154
  546  ssh root@85.193.93.154
  547  whois
  548  whois 85.193.93.154
  549  ls
  550  cd Downloads
  551  pwd
  552  ssh nick@85.193.93.154
  553  ssh-copy-id nick@85.193.93.154
  554  ssh-copy-id nick@85.193.93.154
  555  ssh nick@85.193.93.154
  556  ssh nick@85.193.93.154
  557  ssh nick@85.193.93.154
  558  mmap 85.193.93.154
  559  nmap 85.193.93.154
  560  sudo nmap 85.193.93.154
  561  ssh nick@85.193.93.154
  562  ssh nick@85.193.93.154
  563  ls
  564  cd Desktop/Projects
  565  git clone git@github.com:tparisi/WebGLBook.git
  566  cd WebGLBook
  567  python -m SimpleHTTPServer
  568  python --version
  569  brew install python
  570  python --version
  571  pip3
  572  pip3 install python
  573  python --version
  574  type python
  575  type ptyon2
  576  type python2
  577  type python3
  578  which python
  579  which python
  580  type -a python
  581  which python
  582  ls -l /usr/bin/python
  583  brew install pyenv
  584  brew upgrade
  585  pyenv install --list
  586  pyenv install 2.7.18
  587  python --version
  588  pyenv versions
  589  pyenv global 2.7.18
  590  pyenv versions
  591  python --version
  592  eval "$(pyenv init --path)"
  593  python
  594  python --version
  595  sudo nano ~/.zshrc
  596  source ~/.sprofile
  597  source ~/.zprofile
  598  python --version
  599  python -m SimpleHTTPServer
  600  python -m SimpleHTTPServer
  601  python -m SimpleHTTPServer
  602  python -m SimpleHTTPServer
  603  ssh nick@85.193.93.154
  604  ssh nick@85.193.93.154
  605  python -m SimpleHTTPServer
  606  python -m SimpleHTTPServer
  607  python -m SimpleHTTPServer
  608  git clone git@github.com:nikolaysalinder/gulp4-starter.git
  609  cd gulp4-starter
  610  npm i
  611  gulp
  612  gulp
  613  ls
  614  gulp
  615  cd Desktop/Projects
  616  ls
  617  git clone git@github.com:PacktPublishing/Real-Time-3D-Graphics-with-WebGL-2.git
  618  ls
  619   cd Real-Time-3D-Graphics-with-WebGL-2
  620  cd ..
  621  idea Real-Time-3D-Graphics-with-WebGL-2
  622  python
  623  python -V
  624  python3 -V
  625  python3 -m http.server
  626  python3 -m http.server
  627  python3 -m http.server
  628  python3 -m http.server
  629  ssh nick@85.193.93.154
  630  python3 -m http.server
  631  python3 -m http.server
  632  python3 -m http.server
  633  python3 -m http.server
  634  python3 -m http.server
  635  python3 -m http.server
  636  npm install
  637  npm run
  638  npm run dev
  639  npm run
  640  npm run dev
  641  npm run
  642  npm 
  643  npm help
  644  npm -h
  645  npm run
  646  ls
  647  cd Desktop/Projects
  648  git clone git@github.com:PacktPublishing/Learn-Three.js-Third-Edition.git
  649  npm start
  650  npm start
  651  npm starts
  652  npm start
  653  npm serve
  654  npm serve index.js
  655  npm run index.js
  656  python3 -m http.server
  657  python3 -m http.server
  658  python3 -m http.server
  659  git clone git@github.com:josdirksen/learning-threejs-third.git
  660  git clone git@github.com:josdirksen/learning-threejs-third.git
  661  python3 -m http.server
  662  python3 -m http.server
  663  nmap
  664  python3 -m http.server
  665  python3 -m http.server
  666  python3 -m http.server
  667  python3 -m http.server
  668  python3 -m http.server
  669  python3 -m http.server
  670  python3 -m http.server
  671  python3 -m http.server
  672  python3 -m http.server
  673  python3 -m http.server
  674  python3 -m http.server
  675  python3 -m http.server
  676  python3 -m http.server
  677  python3 -m http.server
  678  python3 -m http.server
  679  python3 -m http.server
  680  python3 -m http.server
  681  python3 -m http.server
  682  tracceroute hackware.ru
  683  traceroute hackware.ru
  684  suto traceroute hackware.ru
  685  sudo traceroute hackware.ru
  686  wget - p http://instagram.com
  687  ping instagram.com
  688  ping instagram.com
  689  python3 -m http.server
  690  git status
  691  git add .
  692  git clone git@github.com:jonasschmedtmann/complete-javascript-course.git
  693  ls
  694  cd HD/
  695  cd /
  696  ls
  697  ipconfig
  698  ipconfig
  699  system_profiler SPHardwareDataType
  700  ip a
  701  wg-easy
  702  node -v
  703  nvm -v
  704  nvm -h
  705  nvm install --lt
  706  nvm ls-remote
  707  nvm install v18.16.0
  708  nvm -v
  709  node -v
  710  pnpm dlx nuxit init sainder.ru-nuxt
  711  npm install -g pnpm
  712  pnpm dlx nuxi init salinder.ru-nuxt
  713  nvm h
  714  npm use --lts
  715  nvm use --lts
  716  pnpm -v
  717  npm install -g pnpm
  718  npm fund
  719  pnpm dlx nuxi init salinder.ru-nuxt
  720  ls
  721  cd Desktop
  722  ls
  723  cd Projects
  724  ls
  725  pnpm dlx nuxi init salinder.ru-nuxt
  726  cd salinder.ru-nuxt
  727  pnpm install
  728  pnpm run dev
  729  pnpm run dev
  730  nvm -v
  731  node -v
  732  nvm use --lts
  733  ls
  734  rm -rf salinder.ru-nuxt
  735  ls
  736  pnpm -v
  737  pnpm run dev
  738  nvm list
  739  nvm v18
  740  nvm alias default 18
  741  node -v
  742  nvm alias default 18.16.0
  743  node -v
  744  mkdir components public static pages
  745  mkdir components static pages
  746  node -v
  747  pnpm install
  748  pnpm run dev
  749  pnpm dev -o
  750  pnpm dev -o
  751  pnpm dev -o
  752  pnpm dev -o
  753  pnpm dev -o
  754  pnpm install eslint
  755  pnpm uninstall eslint
  756  pnpm install --dev eslint
  757  pnpm install - eslint
  758  pnpm install  eslint export default defineNuxtConfig({\n  components: [\n    {\n      path: '~/components',\n+     pathPrefix: false,\n    },\n  ],\n});
  759  pnpm i eslint -D
  760  pnpm i prettier eslint-config-prettier eslint-plugin-prettier
  761  pnpm uninstall prettier eslint-config-prettier eslint-plugin-prettier
  762  pnpm i prettier -D eslint-config-prettier -D eslint-plugin-prettier -D
  763  pnpm uinstall eslint prettier eslint-config-prettier eslint-plugin-prettier
  764  pnpm unistall eslint prettier eslint-config-prettier eslint-plugin-prettier
  765  pnpm uninstall eslint prettier eslint-config-prettier eslint-plugin-prettier
  766  pnpm install prettier eslint-config-prettier eslint-plugin-prettier @nuxt/eslint-config eslint
  767  pnpm uninstall prettier eslint-config-prettier eslint-plugin-prettier @nuxt/eslint-config eslint
  768  pnpm install prettier eslint-config-prettier eslint-plugin-prettier @nuxt/eslint-config eslint -D
  769  pnpm install prettier eslint-config-prettier eslint-plugin-prettier @nuxt/eslint-config eslint -D
  770  pnpm i eslint -D
  771  pnpm dev
  772  pnpm dev
  773  dev -o
  774  pnpm -o
  775  pnpm o
  776  pnpm dev o
  777  pnpm -o
  778  pnpm o
  779  pnpm run o
  780  pnpm run
  781  nuxt dev
  782  nuxt dev
  783  nuxt dev
  784  nuxt dev
  785  nuxt dev
  786  git@github.com:nikolaysalinder/nikolaysalinder.github.io.git
  787  ls
  788  cd Desktop/Projects
  789  git clone git@github.com:nikolaysalinder/nikolaysalinder.github.io.git
  790  ssh-keygen -R github.com
  791  ssh-keygen -R github.com
  792  git clone git@github.com:nikolaysalinder/nikolaysalinder.github.io.git
  793  pnpm i -d sass sass-loader
  794  pnpm add -g pnpm
  795  npm install -g pnpm
  796  pnpm add -g pnpm
  797  pnpm setup
  798  source /Users/nikolaysalinder/.zshrc
  799  pnpm add -g pnpm
  800  pnpm dev 
  801  node -v
  802  node path
  803  what node
  804  which node
  805  pnpm dev
  806  git status
  807  nuxt dev
  808  pnpm dev -o
  809  nuxt dev
  810  pnpm add -g eslint
  811  pnpm setup
  812  pnpm add -g eslint
  813  pnpm setup
  814  fuck you musk
  815  which pnpm
  816  subl ~/.zshrc
  817  which node
  818  pnpm -v
  819  pnpm dev -O
  820  which eslint
  821  which node
  822  which prettier
  823  which sass
  824  pnpm remove sass sass-loader
  825  pnpm add eslint -D
  826  pnpm dev -O
  827  pnpm dev -O
  828  pnpm dev -O
  829  pnpm dev -O
  830  pnpm remove @nuxt/eslint-config eslint eslint-config-prettier eslint-plugin-prettier prettier
  831  pnpm dev -O
  832  pnpm add -D eslint eslint-plugin-vue
  833  pnpm add -D eslint eslint-plugin-vue
  834  pnpm dev -O
  835  nuxt dev
  836  pnpm remove eslint-plugin-vue
  837  pnpm add -D @nuxt/eslint-config
  838  nuxt dev -O
  839  pnpm remove @nuxt/eslint-config
  840  pnpm add -D eslint @nuxtjs/eslint-module
  841  which eslint
  842  {\n  "extends": [\n    "@nuxtjs/eslint-config-typescript"\n  ]\n}
  843  nuxt dev
  844  pnpm @nuxt/eslint-config
  845  pnpm add -D  @nuxt/eslint-config
  846  nuxt dev
  847  nuxt dev
  848  nuxt dev
  849  clear
  850  nuxt dev
  851  nuxt dev
  852  nuxt dev
  853  nuxt js
  854  nuxt dev
  855  pnpm add -D prettier
  856  pnpm remove -D prettier
  857  pnpm add -D prettier
  858  pnpm add -D prettier
  859  nuxt dev
  860  nuxt dev
  861  nuxt dev
  862  nuxt dev
  863  eslint --fix
  864  nuxt dev
  865  eslint --fix
  866  nuxt dev
  867  pnpm lint:fix
  868  pnpm lint:fix
  869  pnpm lint:fix
  870  pnpm lint:fix
  871  prettier --check .
  872  prettier --check .
  873  prettier
  874  pnpm -g prettier
  875  pnpm add -g prettier
  876  which prettier
  877  which node
  878  pnpm add -D eslint-plugin-prettier
  879  nuxt run
  880  nuxt dev
  881  prettier --write
  882  prettier --write .
  883  which node
  884  nuxt dev -O
  885  pnpm remove eslint-plugin-prettier 
  886  nuxt dev
  887  nuxt dev
  888  nuxt dev
  889  nuxt dev -O
  890  nuxt dev -o
  891  pnpm add -D scss
  892  nuxt dev -o
  893  pnpm remove scss
  894  pnpm add -D sass
  895  nuxt dev
  896  node -v
  897  node -v
  898  nuxt dev
  899  nuxt -v
  900  nuxt -v
  901  nuxt dev
  902  nuxt dev
  903  pnpm i
  904  nuxt dev
  905  pnpm remove sass
  906  nuxt dev
  907  nuxt dev -o
  908  pnpm add sass -D
  909  nuxt dev
  910  nuxt dev
  911  nuxt dev
  912  nuxt dev
  913  nuxt dev
  914  nuxt dev
  915  nuxt dev
  916  pnpm add eslint-config-prettier -D
  917  nuxt dev
  918  nuxt dev
  919  cd Desktop/Projects/salinder.ru-nuxt
  920  ls
  921  pwd
  922  ls
  923  cd Desktop
  924  ls
  925  cd Projects
  926  ls
  927  cd salinder.ru
  928  ls
  929  cd client
  930  ls
  931  ls
  932  ls
  933  cd Desktop
  934  ls
  935  cd Projects
  936  ls
  937  ls
  938  cd salinder.ru
  939  ls
  940  cd salinder.ru-nuxt
  941  ls
  942  cd
  943  ls
  944  cd Desktop
  945  ls
  946  cd Projects
  947  ls
  948  cd ..
  949  ls
  950  ls
  951  cd Work
  952  ls
  953  cd salinder.ru
  954  ls
  955  cd ..
  956  ls
  957  cd ..
  958  ls
  959  cd Projects
  960  ls
  961  cd 
  962  ls
  963  cd Desktop
  964  ls
  965  ~/.bash_history
  966  sudo ~ /.bash_history
  967  ls
  968  ls Projects
  969  sudo ~ /.bash_history
  970  sudo ~/.bash_history
  971  cat ~/.zsh_history
  972  cd Projects
  973  ls
  974  traceroute
  975  ды
  976  ls
  977  cd Doc
  978  cd Desktop
  979  ls
  980  cd Projects
  981  ls
  982  cd salinnder-nuxt
  983  cd salinder.ru-nuxt
  984  ls
  985  subl .
  986  pnpm run dev
  987  open ~/Library/icloud/accounts
  988  open ~/Library/Google
  989  dscl . list /Users | grep -v "^_"
  990  nmap
  991  pbcopy < ~/.ssh/id_rsa.pu
  992  pbcopy < ~/.ssh/id_rsa.pub
  993  ssh nikolaysalinder@192.168.1.1
  994  ssh root@192.168.1.1
  995  npm google.com
  996  stacktrace google.com
  997  ls
  998  cd Downloads
  999  bzip2 -cd nmap-7.94.tar.bz2 | tar xvf -
 1000  homebrew version
 1001  $ 
 1002  bash -c "$(curl -fsSL https://raw.githubusercontent.com/tjt263/macports-installer/master/macports-installer.sh)"
 1003  sudo port install nmap
 1004  sudo port install nmap
 1005  brew
 1006  brew install nmap
 1007  mkdir -p /Applications/Docker.app/Contents/Resources/cli-plugins
 1008  brew cleanup
 1009  nmap
 1010  nmap -sn --traceroute google.com microsoft.com
 1011  root nmap -sn --traceroute google.com microsoft.com
 1012  sudo nmap -sn --traceroute google.com microsoft.com
 1013  nmap -sP 192.168.2.0/24
 1014  sudo nmap -sn --traceroute google.com microsoft.com
 1015  stacktrace
 1016  stacktrace
 1017  nmap -sn --traceroute google.com microsoft.com\n
 1018  sudo nmap -sn --traceroute google.com microsoft.com\n
 1019  sudo nmap -sn --traceroute google.com microsoft.com\n
 1020  nmap -sn --traceroute google.com microsoft.com\n
 1021  subl
 1022  subl -v
 1023  ls
 1024  cd .
 1025  ls
 1026  cd ..
 1027  ls
 1028  cd ..
 1029  cd /
 1030  ls
 1031  cd Users
 1032  ls
 1033  ls cd Sha
 1034  cd Shared
 1035  ls
 1036  cd ..
 1037  ls
 1038  Cd nikolaysalinder
 1039  ls
 1040  pwd
 1041  ls
 1042  cd nikolaysalinder
 1043  ls
 1044  ls -a
 1045  cd .ssh
 1046  ls
 1047  ls
 1048  code id_rsa.pub
 1049  cd ..
 1050  history
 1051  help history
 1052  history help
 1053  history all
 1054  history 1051
nikolaysalinder@MacBook-Pro-Nikolay-1 ~ % 

# New terminal log

Starting Nmap 7.94 ( https://nmap.org ) at 2023-07-25 12:53 MSK
Nmap scan report for google.com (173.194.222.102)
Host is up (0.0048s latency).
Other addresses for google.com (not scanned): 173.194.222.101 173.194.222.100 173.194.222.138 173.194.222.113 173.194.222.139
rDNS record for 173.194.222.102: lo-in-f102.1e100.net

TRACEROUTE (using proto 1/icmp)
HOP RTT     ADDRESS
1   5.69 ms 10.146.35.253
2   ... 3
4   4.04 ms 74.125.244.132
5   5.48 ms 142.251.61.219
6   6.87 ms 172.253.51.241
7   ... 15
16  4.71 ms lo-in-f102.1e100.net (173.194.222.102)

Nmap scan report for microsoft.com (20.112.250.133)
Host is up (0.15s latency).
Other addresses for microsoft.com (not scanned): 20.231.239.246 20.76.201.171 20.70.246.20 20.236.44.162

TRACEROUTE (using port 443/tcp)
HOP RTT       ADDRESS
-   Hop 1 is the same as for 173.194.222.102
2   ...
3   1.42 ms   ae2-298.RT.BM.SPB.RU.retn.net (87.245.251.8)
4   12.65 ms  ae4-9.RT.TC1.STO.SE.retn.net (87.245.233.73)
5   42.38 ms  retn.ier02.sto.ntwk.msn.net (104.44.47.27)
6   42.32 ms  ae21-0.ear02.sto31.ntwk.msn.net (104.44.239.199)
7   143.65 ms be-24-0.ibr01.sto31.ntwk.msn.net (104.44.22.170)
8   146.24 ms be-6-0.ibr02.ham31.ntwk.msn.net (104.44.17.207)
9   143.75 ms be-3-0.ibr02.ham30.ntwk.msn.net (104.44.29.2)
10  146.33 ms be-12-0.ibr06.ams06.ntwk.msn.net (104.44.30.73)
11  144.30 ms be-11-0.ibr01.ams21.ntwk.msn.net (104.44.29.242)
12  143.84 ms be-1-0.ibr02.ams30.ntwk.msn.net (104.44.16.147)
13  146.88 ms be-15-0.ibr02.lon22.ntwk.msn.net (104.44.31.2)
14  145.91 ms be-7-0.ibr02.nyc30.ntwk.msn.net (104.44.18.154)
15  150.21 ms be-3-0.ibr02.ewr30.ntwk.msn.net (104.44.7.105)
16  146.18 ms be-8-0.ibr01.cle30.ntwk.msn.net (104.44.17.201)
17  146.32 ms be-11-0.ibr02.ch4.ntwk.msn.net (104.44.29.45)
18  144.37 ms be-7-0.ibr04.dsm05.ntwk.msn.net (104.44.28.222)
19  143.96 ms ae162-0.icr04.dsm05.ntwk.msn.net (104.44.22.208)
20  ... 30




