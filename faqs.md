
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

## What happens to my data?
Data stays on your phone unless you explicitly share it with the research team. Shared data is used for training navigation models and may be included in a publicly released research dataset, with operator identification removed and location data coarsened. You can choose not to share specific sessions or to delete sessions at any time.
## What about audio?
UNI records environmental audio for research on terrain characterization. We do not transcribe or analyze speech content. Audio data is not included in any public dataset release. If you record in a context where capturing audio is inappropriate (e.g., near private conversations), you can disable audio recording in app settings, or delete the session after recording.
## Will UNI record other people walking by?
Like any forward-facing camera, UNI's recordings may incidentally capture bystanders. Before any data is shared with researchers or released publicly, sessions are reviewed and faces, license plates, and other identifying details are blurred. If you are uncomfortable recording in a particular location, please stop the session.
## How long is a typical session?
Most sessions are 15–45 minutes. Sessions longer than 60 minutes may cause device thermal throttling. The app shows session length and storage usage during recording.
## Will UNI drain my battery?
Yes — extended use of camera, depth sensor, and GPS will drain the battery noticeably (typical: 25–35% per hour). We recommend using a battery pack for longer sessions.
## How do I keep my phone safe during walks?
Mount the phone securely on the walker or cart using a vibration-damped mount. Quad Lock motorcycle mounts or similar are recommended. Loose mounts cause data quality issues and risk damage to the phone.
## Is there an IRB protocol covering this?
We are working with Northeastern's IRB to establish an approved research protocol. For now, UNI is distributed only to researchers and collaborators operating under their own institutional approvals. We do not currently solicit data contributions from members of the public.
## Who is responsible for UNI?
UNI is developed and maintained by the RIVeR Lab at Northeastern University, under the supervision of Prof. Taşkın Padır.
## How is this data used in publications?
Data shared with the research team will be used for training and evaluating navigation policies. Aggregate results and sample trajectories may appear in academic publications. We will acknowledge community contributors in any dataset release.
## Can I delete my data?
Yes. All recorded sessions can be deleted from the app at any time. If you have shared data and later request its removal from our servers, contact us at [vaultsensor@gmail.com](mailto:vaultsensor@gmail.com) and we will remove your contributions from active datasets.
