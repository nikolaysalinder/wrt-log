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
