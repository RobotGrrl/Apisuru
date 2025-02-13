# Apisuru

**Apisuru** is a bee frame design featuring sensor panels and pockets for electronics that is designed for 3D printing. The frame dimensions are based on the widely used [Langstroth Hive](https://beeprofessor.com/langstroth-hive-dimensions/). Foundation can be installed inside the frame by sliding it between the rails in the upper and lower bars.

By integrating sensors, **Apisuru** could provide remote monitoring of real-time data on pressure, temperature, humidity, sound, and light levels. Tracking these parameters could help identify patterns related to hive health, such as pest invasions or environmental stressors.

Presently, existing frames do not have the space for electronics, such as pockets or channels for wires to pass through. Adding electronics to the outside of existing frames increases the chances of being frozen in place with [propolis](https://en.wikipedia.org/wiki/Propolis).

To keep the sensors and electronics clear of the brood area, the sensor panels are placed near the outer arc of the rainbow pattern. The sensor plates are barebones, intended to be modified with whatever your custom sensor plan will be. 

This first iteration of Apisuru might not have the weight holding capability as regular frames, since the piece is split into thirds for 3D printing on smaller build platforms.


## Sensor Panels

Each location with a sensor panel available has the naming convention of _FxBy, where x and y could be 0 or 1. 0 represents that the piece has the mounting points for a sensor panel. 1 represents that the piece is filled. 

Sensor panels are located on:
- Side upper (left and right)
- Side lower (left and right)
- Lower bar middle
- Upper bar middle


## Bill of Materials (BOM)

### Mechanical Components BOM

Each item on the BOM requires the following three mechanical components:

| Component                 | McMaster-Carr Part Number | Unit Cost (USD) |
| M3 Heat-set Insert        | 94180A331 | 0.2044 |
| M3 Washer                 | 98269A420 | 0.0247 |
| M3 Fastener 8 mm          | 91290A015 | 0.1876 |
| TOTAL                     |  | 0.4167 |

### Apisuru BOM

Basic setup, with no sensor plates. Each sensor plate requires qty 2 of the mechanical components set.

| Location                       | Quantity |
| Side Left                      | 2 |
| Lower                          | 8 |
| Side Right                     | 2 |
| Upper                          | 6 |
| TOTAL                          | 18 |
| Mechanical Cost                | 7.50 |
|                                |  |
| __For each sensor plate addition__ | __2__ |


## License

**Apisuru** is open source and available under the [CERN Open Hardware license](https://cern-ohl.web.cern.ch/), specifically CERN-OHL-P version 2.0. Let us know if you are interested in adapting Apisuru for an experiment in your hive this bee season!

Apisuru © Copyright Erin RobotZwrrl, Robot Missions Inc.

13-02-25 v1.0

[RobotMissions.org](https://robotmissions.org)
