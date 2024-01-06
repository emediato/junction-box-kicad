# junction_box_kicad
pcb with esp32


Hardware design knowledge .
1. While designing with ethernet 10/100/1000 speed we need to keep the following in mind as below.
2. Ethernet needs esd protection
3. RJ45 port will need EMI filters
4. Ethernet TX and RX pairs need to be impedance matched lines.
5. Shorter traces will provide better emi immunity.
6. We will need an Ethernet PHY interface chip
7. PHY data input lines need series resistors for reflection arrest.
8. Length Matched RX TX pair will improve the link quality and reliability.

