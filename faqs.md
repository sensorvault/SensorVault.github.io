# FAQs

## What is UNI?
UNI is a research data-collection app developed at the RIVeR Lab at Northeastern University. It records sensor data during walks for research on autonomous accessibility navigation — specifically, training navigation policies for autonomous wheelchairs and assistive mobility robots.
## Who is UNI for?
UNI is currently distributed via TestFlight to researchers and collaborators working on robot navigation, accessibility, and mobile robotics. Broader access for community contributors is in development.
## What does UNI need to work?
UNI requires an iPhone (with LiDAR if possible — iPhone 12 Pro or newer) mounted on a wheeled platform such as a walker, rollator, or cart. The phone is held at roughly walker-handlebar height (~90 cm) and points forward along the direction of travel.
## What data does UNI record?
During a recording session, UNI captures:
- Camera (RGB video, forward-facing)
- Depth (when available on devices with LiDAR)
- Motion (IMU: accelerometer, gyroscope)
- Location (GPS, outdoor only)
- Route plan (the walking route requested at session start, from an open mapping service)
- Audio (environmental sound; see below)

Data is stored locally on your device. You decide what to share with researchers.
