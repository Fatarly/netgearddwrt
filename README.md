# NETGEAR WNR2000v2 - DD-WRT és RADIUS

## DD-WRT letöltés: ftp://ftp.dd-wrt.com/others/eko/BrainSlayer-V24-preSP2/2010/12-24-10-r15962/broadcom_K26/dd-wrt.v24-15962_NEWD-2_K2.6_mini-WNR2000v2.chk

## A routert reseteljük ( 1 percen keretszül a reset gombot nyomva )
## A reset után, minden beállítás előtt frissítsük a routert
## A teljesítés után 5 percig hagyjuk dolgozni a routert

## A DD-WRT üdvözlő képernyőjén állítsuk be a felhasználónevet, jelszót

# Setup > Basic Setup

## WAN portot kapcsoljuk ki és akár hozzá lehet adni a switch portokhoz
## Router neve ( Nem lesz látható, célszerű értelmeset beállítani )
## Host Name ( A hálózatra csatlakoztó IP cím )
## Domain Name ( FQDN [ Fully Qualified Domain Name ] ( pl.: muhely.suli.lan ) )

## Local IP Address ( ugyan az mint a Host Name )
## Subnet Mask ( Hálózat alhálózati maszkja ( pl.: 192.168.0.x esetén 255.255.255.0 ) )
## Gateway ( Átjáró megadása )
## Local DNS ( DNS szerver megadása )

## DHCP Type ( DHCP Forwarder )
## DHCP Server ( DHCP szerver címe )

## NTP kliens ( Opcionális bekapcsolni )
### Time Zone ( UTC+01:00 )
### Summer Time(DST) ( last Sun Mar - last Sun Oct )
### Server IP/Name ( ntp.ubuntu.com )

# Wireless > Basic Settings

## Wireless Mode ( AP )
## Wireless Network Mode ( Mixed )
## Wireless Network Name(SSID) ( WiFI AP neve )
## Wireless Channel ( 6 - 2.437 GHz )
## Channel Width ( 20 MHz )
## Wireless SSID Broadcast ( Enable )
## Sensitivity Range(ACK Timing) ( 2000 )
## Network Configuration ( Bridged )

# Wireless > Wireless Security

## Security Mode ( WPA2 Enterprise )
## WPA Algorithms ( AES )
## Radius Auth Server Address ( RADIUS szerver IP címe )
## Radius Auth Server Port ( RADIUS szerver portja )
## Radius Auth Shared Secret ( RADIUS szerver titkos kódja )
## Key Renewal Interval ( 3600 )
