# Interplanetary Spacecraft and Satellite Engineering

## Orbital Parameters:

- Semimajor Axis
- Eccentricity
- Inclination -> dihitung dari plane of reference (bisa equator bisa ekliptik)
- Longitude of Ascending Node -> Diukur dari titik Aries sepanjang garis plane of reference
- Argument of Periapsis -> diukur dari ascending node ke periapsis sepanjang plane orbit
- True Anomaly -> diukur dari periapsis ke objek sepanjang plane orbit

## Orbit manuver gravity assist

## Space Propulsion
- Chemical Internal Heat Engines
- Electric Propulsion
- Nuclear Propulsion

## Communication

How antenna can generate information from EM waves:
![antenna](antenna.png)

Important part of satellite link:
- Up-Converter
- Encoder - Decoder
- High Power Amplifier (trasmitting ground station)
- Low Noise Amplifier (receiving ground station)
- Satellite Repeater
![satellite link](sat_link.png)

Power graph of satellite link:
![power graph](power_graph.png)

## Attitude

Orientation of the spacecraft respect to an inertial reference of frame (central of earth maybe):
- x: roll (in the direction of $\vec{v}$)
- y: pitch
- z: yaw (radially outward of central body)

Measured counter-clockwise in each axis

**Attitude Determination**: measuring the orientation of the spacecraft

**Attitude Control**: returning the spacecraft to its desired attitude

Sistem kontrol attitude:
![kontrol attitude](attitude_control.png)

Attitude jitter: ada osilasi sedikit pada spacecraft, ada batas toleransinya juga

"In the absence of external torques, a body can spin stably only about the axis of maximum moment of inertia"

**Kasus**:

Punya USA itu ga stabil karena di space nanti akan ada rotasi pada axis yg momen inersianya maksimum, mereka kira cuma rotasi pada sekitar axis body yg panjang

Punya Russia stabil karena spherical aj, simpel

![momen inersia](momen_inersia.png)

## Sensor untuk Attitude Control and Determination

**Gyroscope**

**Sun Sensor and Star Tracker**

**Magnetometer**

## Actuator

**Momentum Wheel**

**Control Moment Gyros**

**Thrusters**

**Magnetic Torquers**
