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


