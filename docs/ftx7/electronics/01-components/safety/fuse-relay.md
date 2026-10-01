# Fuses and Relays


## Why do we need it?

A fuse is a deliberate weak point in a circuit. It contains a thin metal link that melts if too much current flows, breaking the circuit. This protects the wiring from overheating if there is a short circuit or a faulty component, so each fuse is chosen to blow below the current that the wire it protects can safely carry.

A relay is an electrically operated switch. A small current through the relay's coil (pins 85 and 86) creates a magnetic field that closes its contacts (pins 30 and 87). This allows a low current signal, from a switch, the ECU or the shutdown circuit, to turn on a high current load such as the fuel pump.

The rules require the shutdown circuit to control the ignition, injectors and fuel pump through at least two relays, one for the fuel pump and at least one for the injection and ignition.

A fuse and relay box keeps the fuses and relays together in one sealed enclosure so they are protected and easy to find and replace.

## FTX7

The FTX7 fuse ratings were chosen from recommended datasheets and measured current draws of components. As per the design report:

- Battery: 100 A, chosen from the measured current draw of the starter motor
- Main: 25 A, chosen from the original CBR600RR main fuse and measurements taken from the car
- ECU: 5 A, the recommended value from the ECU manual
- Fan: 10 A, from the original Hornet 600 1998-2002 wiring diagram
- Fuel pump: 10 A, from the current draw in the fuel pump datasheet
- Ignition: 15 A, from the official CBR600RR 2003-4 wiring diagram
- Injectors: 10 A, from the official CBR600RR 2003-4 wiring diagram

On the wiring schematic, the 100 A battery fuse is between the battery and the LVMS, and the 25 A main fuse comes after the LVMS. The other fuses protect the individual injector, fuel pump, fan, ECU and ignition supplies.

The wiring schematic shows five relays: FP Safety, Fan Relay, FP Relay, Injectors and Ignition. The Electronics Overview states that the end of the shutdown circuit feeds the fuel pump and ignition/injection relay coils, so when the shutdown circuit opens the fuel pump, ignition and injectors all lose power. The fuel pump and radiator fan are also controlled by the ECU through relays.

The design report states that the relays are standard 4-pin automotive relays capable of handling 40A each, which is far beyond the current draw of the car.
