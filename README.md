# m145-git-pe22a

# 01_Packet Tracer - Navigate the IOS

- enable: Wechselt in den privilegierten EXEC-Modus.
- configure terminal: Wechselt in den globalen Konfigurationsmodus.
- show clock: Zeigt die aktuelle Systemzeit an.
- clock set: Ermöglicht das Einstellen der Systemzeit.

# 04_Packet Tracer - Identify MAC and IP Addresses

PC 127.16.31.5 `ping 172.16.31.2`
![alt text](image.png)

PC 127.16.31.5 `ping 172.16.31.2`
Switch 1 Outbound PDU Details
![alt text](image-1.png)

# Block 05 - 18.03.2025 - VLAN
- Falls keine VLAN ID im Packet definiert an alle VLAN ID's von Sender Port => Send to this Port
- Falls eine VLAN ID im Packet definiert an definierte VLAN ID => Send to this Port
- Falls Receiver Tagged ist und Sender Tagged => Add Tag
- Falls Receiver Tagged ist und Sender Untagged => No Tag
- Falls Receiver Untagged ist und Sender Tagged => Add Tag
- Falls Receiver Untagged ist und Sender Untagged => No Tag

## Übung zu Netzwerkdokumentation

-   **Netzwerkadresse Samedan:** 192.168.3.0/24

-   **IP-Adresse AccessPoint Bellinzona:** Teil von VLAN-2 & VLAN-3. Router-IP: 192.168.4.1.

-   **VLAN Arbeitsplatz-PCs:** VLAN-2 (Office)

-   **IP-Adresse Manageable-Switch Chur:** Netzwerk Chur: 192.168.2.0/24. Router-IP: 192.168.2.1.

-   **VPN-Gateway Bellinzona (IPs LAN/Tunnel):** LAN: 192.168.4.1, Tunnel (VPN-B): 172.200.4.2/24

-   **Standardgateway Samedan (Arbeitsplatz-PCs):** 192.168.3.1

-   **VPN-Konfiguration Aussendienstmitarbeiter:** Verbindung zu 82.4.12.158 (Chur ADSL), für VPN-C Tunnel (172.200.5.1/24).

-   **Installateur VoIP CAD Wasserbau:** abisang

-   **Installationsdatum AccessPoint Bistro:** 23.07.14

-   **Rene Sauter (rsauter) Austritt - Betroffene Arbeiten/Verantwortlichkeiten:** Installationen: PC Empfang (E1/1), CAD WS Tiefbau (E2/1), Kopierer Bauleiter (E3/2), AP Bistro (E8/1). **Mögliche Nachfolger:** abisang, blaeuchli, rkundert.

-   **RJ45-Dosen Bauleiterbüro (Verfügbar/Frei):** Total 8 Dosen. **2 Dosen frei** (E3/1, E6/2).

-   **Zusätzliches VoIP-Telefon CAD Tiefbau (Patching):** Patchpanel: E2/2. Switch-Port: Freier Port in VLAN-1 (Telefon, Port 24-47 am Chur Switch).

-   **Ethernetverbindung Bistro (Projektpräsentation):** Freie Dose E8/2, E9/1 oder E9/2 nutzen. Patchpanel-Port mit Switch-Port (VLAN-2 Office) verbinden.

-   **Temporärer Arbeitsplatz CAD Wasserbau (Lösung):** Mini-Switch an bestehendem PC-Anschluss (z.B. E10/2) oder temporär nicht genutzten Anschluss verwenden.

-   **Anzahl Switches Standort Chur:** 2 (ZYXEL XGS1910-24, stacked)

-   **Frau Sommer (CAD-WS) keine Internetverbindung -- Überprüfung:**

    1.  Kabelverbindung (PC/Dose).

    2.  IP-Konfiguration PC (IP, Gateway, DNS).

    3.  Patchpanel/Switch-Port Verbindung (VLAN-2).

    4.  Switch/Router/Firewall Chur Funktion.

    5.  ADSL-Router/Internetverbindung Chur.

    6.  DNS-Auflösung.

    7.  Andere Geräte im VLAN-2 betroffen?

-   **SSID Churer-AccessPoint:** Konnte ich nicht finden
