# TouchInAir

### Note: This project is currently in progress, and is due by July 13th, 2025.

A finger-mounted, Raspberry Pi–powered system that turns **any surface** into a virtual touchscreen. Using an IMU for spatial tracking and a touch-sensing ribbon for contact feedback, `TouchInAir` lets you interact with projections, walls, or desktops — like they're giant iPads.

> Designed as a summer embedded systems research project  
> Blends IMU math, custom drivers, and 3D geometry  
> Live demo: July 13th, 2025. YouTube links will be shared shortly. LUMS live demo would be held in CAD lab, SSE, LUMS.

---

## Hardware Components

- Raspberry Pi 4 Model B
- MPU6050 (GY-521) IMU
- Touch-sensitive ribbon with binary output (custom-made)

---

## System Flow

1. Ribbon sensor detects physical touch.
2. Orientation data from MPU6050.
3. User touches 4 corners of a surface to define an interactive plane.
4. Finger direction ray intersected with the plane to get (x, y).
5. Map 3D point into 2D screen coordinates.
6. Software simulates real-time touch input.

---

## Project Timeline

| Phase | Dates | Description |
|-------|-------|-------------|
| Setup | Pre-Eid – June 10 | IMU + touch ribbon wiring + driver code |
| Filtering | June 10 – 20 | Sensor fusion, orientation estimation |
| Geometry | June 20 – 30 | Calibration, plane math, touch mapping |
| UX Layer | July 1 – 12 | UI software, testing, integration |
| Live Demo | **July 13** | Final presentation and live showcase |

---

## Contacts

Please contact 26100264@lums.edu.pk for queries and details.

