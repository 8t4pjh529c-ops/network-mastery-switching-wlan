# 🚀 Network Mastery: Layer 2/3 Switching & Enterprise WLAN

Interaktive Single-Page-Lernwebseite & Präsentations-Spickzettel für Netzwerktechnik, Switching, VLANs, Spanning Tree und modernes Enterprise Wi-Fi.

## 🌟 Features & Module
- **Modul 1: Switching-Grundlagen & MAC-Table-Simulator**
  - Collision vs. Broadcast Domains, Unterschied zwischen Hub, Switch und Router.
  - Schrittweise Live-Simulation: Switch lernt Source-MAC ➔ Unknown Unicast Flooding ➔ Gezielter Unicast bei Antwort.
- **Modul 2: VLANs & Trunking (IEEE 802.1Q)**
  - Access-Port vs. 802.1Q Trunk-Port Umschaltung.
  - Interaktiver Ethernet-Frame-Inspector mit farblicher Hervorhebung des 4-Byte VLAN-Tags (VID, TPID 0x8100, Native VLAN).
- **Modul 3: Spanning Tree Protocol (STP / RSTP)**
  - Ursachen von Broadcast-Stürmen (keine TTL auf L2).
  - Dreiecks-Topologie mit Root-Bridge-Wahl (Priority + MAC), Root Ports, Designated Ports und Blocking/Discarding Port.
  - Interaktiver Failover-Klicktest (Kabelbruch simuliert).
- **Modul 4: WLAN-Standards, Frequenzen & Kanäle**
  - Ausführlicher Vergleich von 2,4 GHz, 5 GHz und 6 GHz (Wi-Fi 6E/7).
  - Übersicht von Wi-Fi 4 (MIMO) bis Wi-Fi 7 (MLO, OFDMA, MU-MIMO).
  - 2,4-GHz-Kanalplanung (1, 6, 11) und CSMA/CD vs. CSMA/CA mit RTS/CTS.
- **Modul 5: Enterprise WLAN-Architektur & 802.1X Security**
  - Autonomous vs. Lightweight APs mit WLC (Wireless LAN Controller), CAPWAP-Tunnel, Seamless Roaming und PoE (802.3af/at/bt).
  - Sicherheitsvergleich: WPA2-PSK vs. WPA3-SAE vs. 802.1X (RADIUS / Active Directory).
- **Modul 6: 10-Folien PowerPoint-Spickzettel & Interaktives Quiz**
  - Fertige 10-Folien-Präsentationsstruktur inkl. prägnanter Bulletpoints und ausformulierter Sprechernotizen für einen souveränen Vortrag.
  - 5 Multiple-Choice-Prüfungsfragen mit sofortiger Rückmeldung und Begründung.

## 🛠️ Technologie
- Reines HTML5, Tailwind CSS via CDN (Dark-Mode Theme: `#0b1120`, `#0f172a`, `#06b6d4`, `#10b981`), Lucide Icons & Vanilla JavaScript in einer einzigen Datei `index.html`.
- Keine externen Build-Tools erforderlich – direkt per Doppelklick im Browser ausführbar.
