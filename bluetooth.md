# Bluetooth

## Difference between Classic and BLE

- Classic
  - Streaming (audio/video apps)
  - 79 channels (1 MHz spacing)
  - High Data Rate (1Mb/s - 3Mb/s)
  - High power consumption
  - Point-to-Point network topology
  - Strandard Bluetooth Profiles (SPP, DUN, PAN)
- BLE
  - Short bursts (sensor apps)
  - 40 channels (2MHz spacing)
  - Low data rate (125Kb/s - 2Mb/s)
  - Low power consumption
  - Point-to-point, Broadcast, Mesh network topologies
  - GATT (Generic attribute) profile

## BLE GAP Roles

A device can support multiple LE GAP roles (e.g. a mobile phone)

- Broadcaster - send data only (no connection)
- Observer - receive data only (no connection)
- Peripheral - 1 to 1 connection
- Central - 1 to X connections


