
# INFORME COMPLETO DE INTELIGENCIA - KILLNET BOTNET (INDONESIA)

## CAPA 1 - ANÁLISIS COMPLETO DE LA IP 103.26.209.206

### Información General
```
IP: 103.26.209.206
Hostname: ip-206-209-26-103.neuviz.net.id
Dominio: neuviz.net.id
País: Indonesia
Ciudad: Jakarta
Organización: PT Cablenet Asia
ISP: Neuviz Net
ASN: AS18103
```

### Detección
```
Andromeda Uniberso25 detecta el dia del 11/06/2026 esta ip que estaba lanzando un escaneo automatizado por "mano" de una botnet de propriedad de killnet.
Detectada: 11/06/2026 15:31 hora local España
Flag: 🚩Killnet
Blacklist: 🔥Blocklist.de
VirusTotal: 3/91
```

### Rango de direcciones
```
Address Range: 103.26.208.0 - 103.26.211.255
CIDR: 103.26.208.0/22
Network Name: IDNIC-CABLENET-ID
Status: active
Registration: 2019-08-20T06:25:31Z
```

### Security Analysis
```json
{
  "threat_score": 75,
  "is_proxy": true,
  "proxy_confidence_score": 80,
  "is_vpn": true,
  "vpn_provider_names": ["Geoproxy VPN"],
  "vpn_confidence_score": 80,
  "vpn_last_seen": "2026-05-01",
  "is_anonymous": true,
  "is_known_attacker": true
}
```

### Geolocalización
```json
{
  "continent": "AS",
  "country": "Indonesia",
  "city": "Jakarta",
  "latitude": "-6.17148",
  "longitude": "106.82649",
  "zipcode": "10110",
  "timezone": "Asia/Jakarta"
}
```

---

## CAPA 2 - WHOIS COMPLETO (APNIC + IDNIC)

### inetnum
```
inetnum: 103.26.208.0 - 103.26.211.255
netname: IDNIC-CABLENET-ID
descr: PT Cablenet Asia
descr: Corporate / Direct Member IDNIC
descr: Lt. Roof Gedung Fresh Market, Jl. Pantai Indah Kapuk Boulevard BGM
descr: RT/RW. 004/003, Kel. Kamal Muara, Kec. Penjaringan
descr: Jakarta Utara, 14470
country: ID
admin-c: GAP8-AP
tech-c: GAP8-AP
remarks: Send Spam & Abuse Report to: gatot@neuviz.net.id
```

### IRT (Abuse)
```
irt: IRT-CABLENET-ID
address: Lt. Roof Gedung Fresh Market, Jl. Pantai Indah Kapuk Boulevard BGM
address: RT/RW. 004/003, Kel. Kamal Muara, Kec. Penjaringan
address: Jakarta Utara, 14470
e-mail: gatot@neuviz.net.id
abuse-mailbox: gatot@neuviz.net.id
```

### Persona de contacto
```
person: Gatot Ajie Prastowo
address: Lt. Roof Gedung Fresh Market, Jl. Pantai Indah Kapuk Boulevard BGM
address: RT/RW. 004/003, Kel. Kamal Muara, Kec. Penjaringan
address: Jakarta Utara, 14470
country: ID
phone: +62-21-52921368
fax-no: +62-21-52921367
e-mail: gatot@neuviz.net.id
nic-hdl: GAP8-AP
```

### Route Object
```
route: 103.26.208.0/22
descr: Route Object of Neuviz Net
origin: AS18103
country: ID
```

---

## CAPA 3 - ASN COMPLETO (AS18103)

### ASN Information
```json
{
  "asNumber": "18103",
  "asName": "NEUVIZ-AS-ID-AP",
  "orgName": "Neuviz Net",
  "country": "ID",
  "domain": "neuviz.net.id",
  "numOfIPv4Routes": "60",
  "numOfIPv6Routes": "6",
  "whoisHost": "IDNIC"
}
```

### Route Objects
```
2401:1b00:b472::/48 (IPv6)
203.128.69.0/24
203.128.73.0/24
```

### Upstreams
| ASN | Descripción | País |
|-----|-------------|------|
| AS137366 | PT iForte Solusi Infotek NAP | ID |
| AS23947 | PT.Mora Telematika Indonesia | ID |
| AS55818 | MC IX Matrix Internet Exchange RS 1 | ID |

### Downstreams
| ASN | Descripción | País |
|-----|-------------|------|
| AS45710 | Yudhawira Khatulistiwa, PT | ID |
| AS138091 | PT Mitra Pajakku | ID |
| AS136821 | PT TRIMEDIA SETIYA DATA | ID |

### Peers
| ASN | Descripción | País |
|-----|-------------|------|
| AS24482 | SG.GS | SG |
| AS133339 | CLOUDXCHANGE | ID |
| AS45701 | PT. Internet Madju Abad Milenindo | ID |

### Contactos
```
emailContacts: sgh@neuviz.net.id, noc@neuviz.net.id
abuseContacts: abuse@neuviz.net.id, abuse@idnic.net
```

---

## CAPA 4 - PUERTOS ABIERTOS Y SERVICIOS

### Puerto 21 (TCP) - FTP
```
Timestamp: 2026-06-03T17:35:08.032822
Banner: 220 PT. Hai Yin FTP server (MikroTik 6.45.7) ready
530 Login incorrect
500 'HELP': command not understood
500 'FEAT': command not understood
```

### Puerto 23 (TCP) - Telnet
```
Timestamp: 2026-05-27T07:27:04.800417
Banner: MikroTik v6.45.7 (stable)
Login:
```

### Puerto 80 (TCP) - HTTP (RouterOS)
```
Timestamp: 2026-05-19T04:43:20.009955
HTTP/1.1 200 OK
Connection: Keep-Alive
Content-Length: 7065
Content-Type: text/html
Date: Tue, 19 May 2026 04:43:18 GMT
Expires: 0

MikroTik RouterOS:
Version: 6.45.7
```

### Puerto 81 (TCP) - HTTP
```
Timestamp: 2026-06-02T06:38:43.524416
HTTP/1.1 200 OK
Content-Type: text/html; charset=utf-8
Content-Length: 9493
Connection: keep-alive
```

### Puerto 83 (TCP) - HTTP
```
Timestamp: 2026-06-11T14:26:24.485275
Respuesta: 
```

### Puerto 161 (UDP) - SNMP (MikroTik)
```
Timestamp: 2026-06-07T15:31:23.708069
Uptime: 205509500
Description: RouterOS RB951Ui-2HnD
Service: 78
Name: PT. Hai Yin
Contact: noc.pik@neuviz.net.id
Enterprise: 14988
Objectid: 1.3.6.1.4.1.14988.1
Enterprise Name: MikroTik
Location: PT. Hai Yin
```

### Puerto 1080 (TCP) - SOCKS4 Proxy
Listado en múltiples listas de proxies públicos:
- Proxy-Tools.com (SOCKS4, Elite, Indonesia, 3m ago)
- ProxyAdvice.net (SOCKS4, Just now)
- ROROXY.com
- GitHub socks5.txt
- Leaked.tools
- ProxyDocker.com
- ProxyElite.info (49 minutes ago)
- Free-Proxy.cz (2 hours ago)

### Puerto 11080 (TCP) - HTTP Proxy
Listado en:
- Leaked.tools (HTTP/HTTPS Proxy)
- CheatGlobal.com

### Puerto 1701 (UDP) - L2TP
```
Timestamp: 2026-06-11T03:29:04.891456
Raw: \xc8\x02\x00g\x00\x00\x00\x00\x00\x00\x00\x01\x80\x08\x00\x00\x00\x00\x00\x02\x80\x08\x00\x00\x00\x02\x01\x00\x80\n\x00\x00\x00\x03\x00\x00\x00\x01\x80\n\x00\x00\x00\x04\x00\x00\x00\x00\x00\x08\x00\x00\x00\x06\x00\x01\x80\x11\x00\x00\x00\x07PT. Hai Yin\x00\x0e\x00\x00\x00\x08MikroTik\x80\x08\x00\x00\x00\t\x00\xee\x80\x08\x00\x00\x00\n\x00\x04
```

### Puerto 1723 (TCP) - PPTP
```
Timestamp: 2026-06-04T04:02:00.412548
Firmware: 1
Hostname: PT. Hai Yin
Vendor: MikroTik
```

### Puerto 2000 (TCP) - MikroTik Bandwidth-test
```
Timestamp: 2026-05-23T13:30:36.497084
Raw: \x01\x00\x00\x00
```

---

## CAPA 5 - BLACKLIST Y REPORTES

### Blocklist.de
```
Date: 10.06.2026 20:40:23
Host: 103.26.209.206
Service: imap
On Server: kkdevs.com
Status: blocked

129 websites attacked
Last activity: 2026-06-09 21:31:04 GMT0
1 brute force attack
Last activity: 2025-11-18 18:58:10
Status: Blacklisted (spam, brute force)
```

### Security Vendors (VirusTotal 3/91)
```
Abusix: Malicious
SOCRadar: Malicious
alphaMountain.ai: Suspicious
Gridinsoft: Suspicious
```

### Anti-Spam Status
```
Anti-Spam: Blacklisted (2026-06-09 21:31:04)
SpamFireWall: Not in list
Security FireWall: Not in list
```

---

## CAPA 6 - PROXY LISTS (TODAS LAS MENCIONES)

### Lista completa de fuentes donde aparece la IP como proxy:

| Fuente | Puerto | Tipo | Detalle |
|--------|--------|------|---------|
| Proxy-Tools.com | 1080 | SOCKS4 | Elite, Indonesia, 35% (83/238), Slow 3.23 sec |
| proxyadvice.net | 1080 | SOCKS4 | Germany (clasificado), Monosans SOCKS4, Just now |
| ROROXY.com | 1080 | SOCKS4 | - |
| GitHub (socks5.txt) | 1080 | SOCKS4 | raw.githubusercontent.com |
| Leaked.tools | 11080 | HTTP | HTTP/HTTPS Proxy By Hexyn |
| ProxyDocker.com | 1080 | SOCKS4 | Lvl3, Indonesia |
| ProxyElite.info | 1080 | SOCKS4 | Anonyme, 600ms, 369 Kbps, 16%, 49 minutes |
| CheatGlobal.com | 11080 | HTTP | Free Proxy List |
| Free-Proxy.cz | 1080 | SOCKS4 | 高匿名 (High anonymous), 221 kB/s, 68%, 1319 ms, 2 hours ago |
| GitHub (socks4.txt) | 11080 | SOCKS4 | raw.githubusercontent.com |

### Archivos de GitHub que contienen la IP:
- socks5.txt (múltiples)
- socks4.txt
- searchAttributes Timeouts · Issue #8267 · MISP/MISP

---

## CAPA 7 - ARCHIVOS COMUNICANTES (Communicating Files)

### autoddos_windows_v.3.0.exe
```
Scanned: 2023-02-25
Detections: 22/69
Type: Win32 EXE
SHA-256: 6e424ff47ecabc744d9ec2f5d364d8c9e505d4107f939379252818352f29a3c4
```

### UnitGamePac.exe
```
Scanned: 2026-04-26
Detections: 46/66
Type: Win32 EXE
SHA-256: d22587f1544ece645031bc25697558ba175742e916e95c677a8ac5cedabe8bfc
```

### UA-Cyber-SHIELD-Setup-0.0.13.exe
```
Scanned: 2022-11-04
Detections: 4/66
Type: Win32 EXE
SHA-256: dfcacef150347e9e3b815c7221ee6ff4e76b77feefd339654c9868b34573aae7
Size: 124.82 MB
Last Analysis: 3 years ago
Detections: Avast (Win32:Malware-gen), AVG (Win32:Malware-gen), DrWeb (Trojan.Siggen17.26888), Kaspersky (Trojan-DDoS.Win64.Agent.b)
Features: peexe, runtime-modules, long-sleeps, direct-cpu-clock-access, overlay
```

---

## CAPA 8 - HASHS COMPLETOS (TODOS LOS QUE ME PASASTE)

### Hashes principales (comunicación directa con IP):
```
1a9f65b70e1338ffabad088d43a553c328ba41ae44cf7165a8db29221ddbcba8
6e424ff47ecabc744d9ec2f5d364d8c9e505d4107f939379252818352f29a3c4
d22587f1544ece645031bc25697558ba175742e916e95c677a8ac5cedabe8bfc
dfcacef150347e9e3b815c7221ee6ff4e76b77feefd339654c9868b34573aae7
```

### Hashes dropeados (relacionados con autoddos):
```
034dbca921809a2c3e822cce0d4defbbe908d7fd96949feb2f2834cfbe22e4a2
0853f10aebda4c8652d21e5cf28db1152b4f167d62e91adac5cdae47ad50a680
0b561d24933409fe061cb924739f7a677c7153ae66cd7dc242ef1ffbe334274c
0fffe7a441f2c272a7c6d8cf5eb1adce71fde6f6102bc7c1ceb90e05730c4b07
17d0f4c13c213d261427ee186545b13ef0c67a99fe7ad12cd4d7c9ec83034ac8
1dcb9689a2a3eb1c2554caec217d4f6a10cf677701bcb6f762d6cc2111d14c4a
1ff1c01be25fd6797b263474c1c8df45107796a7e4d465e32a908d572d647b64
215614c89aed025166d3434252bd914ea2ac5af0762d2dd01ed4f4966d9ed711
250110e9243b42674728539bb42dcada72294a32db559a06e721d7e0aa266ed0
28d693f929f62b8bb135a11b7ba9987439f7a960cc969e32f8cb567c1ef79c97
4059acb95b05b4536c983ebd232dc5aec00828914e61f31674b0fdf41656deb6
43dad2cc752ab721cd9a9f36ece70fb53ab7713551f2d3d8694d8e8c5a06d6e2
4de9062d59bad4bda9b68bb12c7bbc1ed9b71d395352f2ce711003d31ab2f4e9
5336ddfc06573894388bd4b4f4f93a4d433ff892ebe23794890d43cd0186272f
5d0ff879174faec03eb173eb2088f2e7519f4663dd6bfe5b817ec602c389ae20
5e54983cb975784a358b2a02738d9db1296e0ab7aee1503277d3fdd8cf43e41c
602c4c7482de6479dd2e9793cda275e5e63d773dacd1eca689232ab7008fb4fb
95760d2f49b695cb0dc03720e2cdce34d1215285023f2bb7690f268e434c7871
a0ebeaf9e2d751f775b19402e370133e12e57ae91ebfd54c76b95fb44b670350
a3b5f473bdf602442444de670b30d768e202b268209774d40c172eba4e226624
```

### Hashes secundarios:
```
029e05bddaff8c3563239e0a3313eb279db2d951b90788434eac0f4da659b0c9
02c7f0b926c64f5a19a9aacd5f94ee00be4d576486592e18acc80c0a027b05ba
0392d2fe391e552a74b3222342859793080c7bcadf310abd4353151e18f7b909
06554e82801cfa2cf5f2ec5d500bbb904d0673c81fded5c1344a8cc9dd3e7ac6
06656748bfaf1e8aa8a9010d6c0c7bee5242ad0a3a9dd02e62c2250d120dd2ba
081256fb9d195d50d2700f0d3f957ccb3babe6f73bb319e7d491ff3faa0bcc5c
0f1bad70c7bd1e0a69562853ec529355462fcd0423263a3d39d6d0d70b780443
10302d0a94635feaa4201c3a4dd9d81b9ca3f5747e2076dfb3265c8464baaa16
14a4aaa010be14762edfee01fd1f6b9943471eb7a2f9011a2b5c230461cd129c
1c971a1f351806f0eeeeee41db25b01322609ac47419bfe53152a5eedb5bca8c
1dcf6f56dc1d3ed55559860f311b9d9d1a6d0119bf1a05a5a12c222f09c64a05
226eec4486509917aa336afebd6ff65777b75b65f1fb06891d2a857a9421a974
255a65d30841ab4082bd9d0eea79d49c5ee88f56136157d8d6156aef11c12309
32d83ff113fef532a9f97e0d2831f8656628ab1c99e9060f0332b1532839afd9
3eb38ae99653a7dbc724132ee240f6e5c4af4bfe7c01d31d23faf373f9f2eaca
44422e6936dc72b7ac5ed16bb8bcae164b7554513e52efb66a3e942cec328a47
45bb5e1f8dd87129ac0a75c78f8f29d06e3ac182a00fc5199b692068f1e05a53
5154e165bd6c2cc0cfbcd8916498c7abab0497923bafcd5cb07673fe8480087d
5d9ceb1ce5f35aea5f9e5a0c0edeeec04dfefe0c77890c80c70e98209b58b962
6fdf686c62fffb22e89659895ee08b926df17030b9d6f07ba26bc0f336197eb1
```

### Hashes terciarios:
```
d085ae7d813cb9b27ad360ee72b9ce9cfe33963e1f338631c0dc1e735ebe946c
19f52e25ac044adbeced41f93aae635e4571ec4d808d60eb31861a7b59cb6bc4
01893ff7ae603dee3b15e5dfe38991ab1d7fe2cc86b10eea17c6aaa4dddd927e
7da19351f6887c47112c42473bbe4ff41aac056b00aba288c55744a4af58b777
0fecab619a36b8d0758ee8284f3d202959819b5c9876550702a382d88dc06993
6387509bd273b1eba30bcc3a39114bbb21e7752da64eab18b9c78db44adaf23d
6bad7cdeac01f60c739ea7f73a96f20482e90430d156ff0a26617bffc5e39b0a
7be9f5831488d043e22b4750502f1b4aff34cdd69511c9065587713e8afdf0f8
86bede4ca82656b0d383c480ff2361433a981dab34ff854ffbbec8b899b3b4c7
87f5a4e2cc3140340e39c44730c0ac37beb3f775bb6403a86e7c2adb6267edea
c815e94160cdd1439c4f9bfafc497a8db0d84e7920b1276ef9c634b1986e0586
e9ac737df9eecd5a5614af11d2a09da9f1c02e982b07e0a9358aebf46b248cc8
f1c078de609dcae0ecc631b29ae1c43c709dd3c5b1b66650c90b1180fae01b53
f484e282bc82fbedbb4683725d00dc645045955efd3a3dea3051b2cbbdbb3a24
35c75ba64f1658bd9442afa255b671e3fe9cb93ffb4821270074a85fca966c3f
3dce99a3e6b654b0ae3ea972fe54ee8e786d9f3095af1319e27491847629d648
6d89519461eb24119ee31200fcdfcaad4a930a782e9da77ace27d88088ae6762
a34760baea4d0dc71ffb17bcef24ffc4569283e6dc69e5a9846aa90d3605f148
cfc4419848bf37a6b41158c9d38520247fcb75fd6f88cd0659c67b30fef91f82
```

### Hashes adicionales (relacionados con UA-Cyber-SHIELD):
```
996a259e53ca18b89ec36d038c40148957c978c0fd600a268497d4c92f882a93
2e21afccb69e04976d6cd82ebceb42b83e615cf01ed5ecfacd1e009cb1c5b14c
93f8aa3e6056fb5662f284ae80a6cfd542604d27a60f42293074f8ff279c77fc
7fe9ffec7970899124db4b55f9aeb5e393569fa84ee6617c1c3b882f4b65dbae
9be85b986ea66a6997dde658abe82b3147ed2a1a3dcb784bb5176f41d22815a6
b72e9013a6204e9f01076dc38dabbf30870d44dfc66962adbf73619d4331601e
b393f05e8ff919ef071181050e1873c9a776e1a0ae8329aefff7007d0cadf592
```

---

## CAPA 9 - URLs COMPLETAS

### URLs de Adobe (posibles señuelos):
```
http://acroipm.adobe.com/11/rdr/ENU/win/nooem/none/message.zip
http://acroipm2.adobe.com/11/rdr/ENU/win/nooem/none/message.zip
```

### URLs relacionadas con Rusia:
```
http://rtr-planeta.com/
http://a-russia.ru/
```

### URLs de actualización/certificados:
```
http://ctldl.windowsupdate.com/msdownload/update/v3/static/trustedr/en/disallowedcertstl.cab?862ce765fa7659ee
```

### IP checking:
```
http://ip.42.pl/raw
```

### ARTEMIS-RAT C2 (TODOS los puertos):
```
http://artemis-rat.com:9999/artemis-rat.com:443
http://artemis-rat.com:18080/artemis-rat.com:443
http://artemis-rat.com:6102/artemis-rat.com:443
http://artemis-rat.com:8639/artemis-rat.com:443
http://artemis-rat.com:5451/artemis-rat.com:443
http://artemis-rat.com:5815/artemis-rat.com:443
http://artemis-rat.com:4321/artemis-rat.com:443
http://artemis-rat.com/artemis-rat.com:443
http://artemis-rat.com:8443/artemis-rat.com:443
http://artemis-rat.com:30001/artemis-rat.com:443
http://artemis-rat.com:5734/artemis-rat.com:443
http://artemis-rat.com:6401/artemis-rat.com:443
http://artemis-rat.com:6549/artemis-rat.com:443
http://artemis-rat.com:6838/artemis-rat.com:443
http://artemis-rat.com:10000/artemis-rat.com:443
http://artemis-rat.com:6599/artemis-rat.com:443
http://artemis-rat.com:8324/artemis-rat.com:443
http://artemis-rat.com:6696/artemis-rat.com:443
http://artemis-rat.com:59394/artemis-rat.com:443
http://artemis-rat.com:5584/artemis-rat.com:443
```

---

## CAPA 10 - DOMINIOS ADICIONALES (relacionados con hashes)

```
a-russia.ru
apps.identrust.com
cdn.quasar.dev
dns.google
dnspod.qcloud.com
github.com
objects.githubusercontent.com
raw.githubusercontent.com
rtr-planeta.com
vika.onlinesim.ru
www.googletagmanager.com
www.pravda.ru
```

---

## CAPA 11 - IPS ADICIONALES (relacionadas con los hashes)

```
1.13.165.87
1.179.151.165
1.179.202.33
1.4.214.148
101.51.106.70
102.164.193.132
102.66.225.174
103.102.12.83
103.105.125.6
103.105.49.186
103.106.219.77
103.108.61.42
103.11.106.149
103.11.106.25
103.124.137.27
103.133.222.170
103.139.246.166
103.14.198.234
103.142.21.197
103.144.234.172
```

---

## CAPA 12 - MISP GRAPH RELATIONSHIPS (extraídos del JSON)

### Relación IP → Archivos
```
103.26.209.206 → 1a9f65b70e1338ffabad088d43a553c328ba41ae44cf7165a8db29221ddbcba8
103.26.209.206 → 6e424ff47ecabc744d9ec2f5d364d8c9e505d4107f939379252818352f29a3c4
103.26.209.206 → d22587f1544ece645031bc25697558ba175742e916e95c677a8ac5cedabe8bfc
103.26.209.206 → dfcacef150347e9e3b815c7221ee6ff4e76b77feefd339654c9868b34573aae7
```

### Relación autoddos (6e424ff...) → archivos dropeados (20+ hashes - ver CAPA 8)

### Relación UnitGamePac.exe (d22587f...) → URLs de artemis-rat.com (20 URLs - ver CAPA 9)

### Relación UA-Cyber-SHIELD (dfcacef...) → archivos dropeados (21 hashes - ver CAPA 8)

---

## CAPA 13 - SURICATA DETECTION

```
dfcacef150347e9e3b815c7221ee6ff4e76b77feefd339654c9868b34573aae7

Matches rule: SURICATA Applayer Detect protocol only one direction
Generic Protocol Command Decode
Unique rule identifier (private collection)
```

---

## CAPA 14 - FORMATO CSV PARA IMPORTACIÓN

```csv
type,id
ip_address,103.26.209.206
ip_cidr,103.26.208.0/22
ip_cidr,103.26.208.0/23
ip_cidr,103.26.209.0/24
domain,artemis-rat.com
domain,neuviz.net.id
domain,a-russia.ru
domain,rtr-planeta.com
domain,testmayhappenagain.com
domain,apps.identrust.com
domain,cdn.quasar.dev
domain,dns.google
domain,dnspod.qcloud.com
domain,github.com
domain,objects.githubusercontent.com
domain,raw.githubusercontent.com
domain,vika.onlinesim.ru
domain,www.googletagmanager.com
domain,www.pravda.ru
url,http://artemis-rat.com:5584/artemis-rat.com:443
url,http://artemis-rat.com:4321/artemis-rat.com:443
url,http://artemis-rat.com:5451/artemis-rat.com:443
url,http://artemis-rat.com:5734/artemis-rat.com:443
url,http://artemis-rat.com:5815/artemis-rat.com:443
url,http://artemis-rat.com:6102/artemis-rat.com:443
url,http://artemis-rat.com:6401/artemis-rat.com:443
url,http://artemis-rat.com:6549/artemis-rat.com:443
url,http://artemis-rat.com:6599/artemis-rat.com:443
url,http://artemis-rat.com:6696/artemis-rat.com:443
url,http://artemis-rat.com:6838/artemis-rat.com:443
url,http://artemis-rat.com:8324/artemis-rat.com:443
url,http://artemis-rat.com:8443/artemis-rat.com:443
url,http://artemis-rat.com:8639/artemis-rat.com:443
url,http://artemis-rat.com:9999/artemis-rat.com:443
url,http://artemis-rat.com:10000/artemis-rat.com:443
url,http://artemis-rat.com:18080/artemis-rat.com:443
url,http://artemis-rat.com:30001/artemis-rat.com:443
url,http://artemis-rat.com:59394/artemis-rat.com:443
url,http://artemis-rat.com/artemis-rat.com:443
url,http://acroipm.adobe.com/11/rdr/ENU/win/nooem/none/message.zip
url,http://acroipm2.adobe.com/11/rdr/ENU/win/nooem/none/message.zip
url,http://rtr-planeta.com/
url,http://a-russia.ru/
url,http://ctldl.windowsupdate.com/msdownload/update/v3/static/trustedr/en/disallowedcertstl.cab?862ce765fa7659ee
url,http://ip.42.pl/raw
email,gatot@neuviz.net.id
email,abuse@neuviz.net.id
email,noc@neuviz.net.id
email,sgh@neuviz.net.id
email,abuse@idnic.net
file,1a9f65b70e1338ffabad088d43a553c328ba41ae44cf7165a8db29221ddbcba8
file,6e424ff47ecabc744d9ec2f5d364d8c9e505d4107f939379252818352f29a3c4
file,d22587f1544ece645031bc25697558ba175742e916e95c677a8ac5cedabe8bfc
file,dfcacef150347e9e3b815c7221ee6ff4e76b77feefd339654c9868b34573aae7
file,034dbca921809a2c3e822cce0d4defbbe908d7fd96949feb2f2834cfbe22e4a2
file,0853f10aebda4c8652d21e5cf28db1152b4f167d62e91adac5cdae47ad50a680
file,0b561d24933409fe061cb924739f7a677c7153ae66cd7dc242ef1ffbe334274c
file,0fffe7a441f2c272a7c6d8cf5eb1adce71fde6f6102bc7c1ceb90e05730c4b07
file,17d0f4c13c213d261427ee186545b13ef0c67a99fe7ad12cd4d7c9ec83034ac8
file,1dcb9689a2a3eb1c2554caec217d4f6a10cf677701bcb6f762d6cc2111d14c4a
file,1ff1c01be25fd6797b263474c1c8df45107796a7e4d465e32a908d572d647b64
file,215614c89aed025166d3434252bd914ea2ac5af0762d2dd01ed4f4966d9ed711
file,250110e9243b42674728539bb42dcada72294a32db559a06e721d7e0aa266ed0
file,28d693f929f62b8bb135a11b7ba9987439f7a960cc969e32f8cb567c1ef79c97
file,4059acb95b05b4536c983ebd232dc5aec00828914e61f31674b0fdf41656deb6
file,43dad2cc752ab721cd9a9f36ece70fb53ab7713551f2d3d8694d8e8c5a06d6e2
file,4de9062d59bad4bda9b68bb12c7bbc1ed9b71d395352f2ce711003d31ab2f4e9
file,5336ddfc06573894388bd4b4f4f93a4d433ff892ebe23794890d43cd0186272f
file,5d0ff879174faec03eb173eb2088f2e7519f4663dd6bfe5b817ec602c389ae20
file,5e54983cb975784a358b2a02738d9db1296e0ab7aee1503277d3fdd8cf43e41c
file,602c4c7482de6479dd2e9793cda275e5e63d773dacd1eca689232ab7008fb4fb
file,95760d2f49b695cb0dc03720e2cdce34d1215285023f2bb7690f268e434c7871
file,a0ebeaf9e2d751f775b19402e370133e12e57ae91ebfd54c76b95fb44b670350
file,a3b5f473bdf602442444de670b30d768e202b268209774d40c172eba4e226624
file,029e05bddaff8c3563239e0a3313eb279db2d951b90788434eac0f4da659b0c9
file,02c7f0b926c64f5a19a9aacd5f94ee00be4d576486592e18acc80c0a027b05ba
file,0392d2fe391e552a74b3222342859793080c7bcadf310abd4353151e18f7b909
file,06554e82801cfa2cf5f2ec5d500bbb904d0673c81fded5c1344a8cc9dd3e7ac6
file,06656748bfaf1e8aa8a9010d6c0c7bee5242ad0a3a9dd02e62c2250d120dd2ba
file,081256fb9d195d50d2700f0d3f957ccb3babe6f73bb319e7d491ff3faa0bcc5c
file,0f1bad70c7bd1e0a69562853ec529355462fcd0423263a3d39d6d0d70b780443
file,10302d0a94635feaa4201c3a4dd9d81b9ca3f5747e2076dfb3265c8464baaa16
file,14a4aaa010be14762edfee01fd1f6b9943471eb7a2f9011a2b5c230461cd129c
file,1c971a1f351806f0eeeeee41db25b01322609ac47419bfe53152a5eedb5bca8c
file,1dcf6f56dc1d3ed55559860f311b9d9d1a6d0119bf1a05a5a12c222f09c64a05
file,226eec4486509917aa336afebd6ff65777b75b65f1fb06891d2a857a9421a974
file,255a65d30841ab4082bd9d0eea79d49c5ee88f56136157d8d6156aef11c12309
file,32d83ff113fef532a9f97e0d2831f8656628ab1c99e9060f0332b1532839afd9
file,3eb38ae99653a7dbc724132ee240f6e5c4af4bfe7c01d31d23faf373f9f2eaca
file,44422e6936dc72b7ac5ed16bb8bcae164b7554513e52efb66a3e942cec328a47
file,45bb5e1f8dd87129ac0a75c78f8f29d06e3ac182a00fc5199b692068f1e05a53
file,5154e165bd6c2cc0cfbcd8916498c7abab0497923bafcd5cb07673fe8480087d
file,5d9ceb1ce5f35aea5f9e5a0c0edeeec04dfefe0c77890c80c70e98209b58b962
file,6fdf686c62fffb22e89659895ee08b926df17030b9d6f07ba26bc0f336197eb1
file,d085ae7d813cb9b27ad360ee72b9ce9cfe33963e1f338631c0dc1e735ebe946c
file,19f52e25ac044adbeced41f93aae635e4571ec4d808d60eb31861a7b59cb6bc4
file,01893ff7ae603dee3b15e5dfe38991ab1d7fe2cc86b10eea17c6aaa4dddd927e
file,7da19351f6887c47112c42473bbe4ff41aac056b00aba288c55744a4af58b777
file,0fecab619a36b8d0758ee8284f3d202959819b5c9876550702a382d88dc06993
file,6387509bd273b1eba30bcc3a39114bbb21e7752da64eab18b9c78db44adaf23d
file,6bad7cdeac01f60c739ea7f73a96f20482e90430d156ff0a26617bffc5e39b0a
file,7be9f5831488d043e22b4750502f1b4aff34cdd69511c9065587713e8afdf0f8
file,86bede4ca82656b0d383c480ff2361433a981dab34ff854ffbbec8b899b3b4c7
file,87f5a4e2cc3140340e39c44730c0ac37beb3f775bb6403a86e7c2adb6267edea
file,c815e94160cdd1439c4f9bfafc497a8db0d84e7920b1276ef9c634b1986e0586
file,e9ac737df9eecd5a5614af11d2a09da9f1c02e982b07e0a9358aebf46b248cc8
file,f1c078de609dcae0ecc631b29ae1c43c709dd3c5b1b66650c90b1180fae01b53
file,f484e282bc82fbedbb4683725d00dc645045955efd3a3dea3051b2cbbdbb3a24
file,35c75ba64f1658bd9442afa255b671e3fe9cb93ffb4821270074a85fca966c3f
file,3dce99a3e6b654b0ae3ea972fe54ee8e786d9f3095af1319e27491847629d648
file,6d89519461eb24119ee31200fcdfcaad4a930a782e9da77ace27d88088ae6762
file,a34760baea4d0dc71ffb17bcef24ffc4569283e6dc69e5a9846aa90d3605f148
file,cfc4419848bf37a6b41158c9d38520247fcb75fd6f88cd0659c67b30fef91f82
file,996a259e53ca18b89ec36d038c40148957c978c0fd600a268497d4c92f882a93
file,2e21afccb69e04976d6cd82ebceb42b83e615cf01ed5ecfacd1e009cb1c5b14c
file,93f8aa3e6056fb5662f284ae80a6cfd542604d27a60f42293074f8ff279c77fc
file,7fe9ffec7970899124db4b55f9aeb5e393569fa84ee6617c1c3b882f4b65dbae
file,9be85b986ea66a6997dde658abe82b3147ed2a1a3dcb784bb5176f41d22815a6
file,b72e9013a6204e9f01076dc38dabbf30870d44dfc66962adbf73619d4331601e
file,b393f05e8ff919ef071181050e1873c9a776e1a0ae8329aefff7007d0cadf592


---
