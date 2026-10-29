# Rihan Star Battle

An original, offline-first 3D battle-royale-style survival prototype for Android.

## Offline gameplay
- Local Three.js engine bundled in the Android app; gameplay does not fetch JavaScript from a CDN.
- Solo campaign against AI-controlled enemies.
- Three difficulty-scaled campaign levels.
- Loot pickups, ammunition, healing kits, a shrinking safe zone, parachute entry, vehicles, touch controls and a tactical minimap.
- No account, multiplayer server, or internet connection is required to play the prototype.

## Build Android APK
1. Open the **Actions** tab in this repository.
2. Select **Build Android APK**.
3. Select **Run workflow** (or use the latest successful run).
4. Download the **Rihan-Star-APK** artifact and extract the APK from the downloaded ZIP.
5. Install the APK on an Android test device. Android may ask you to allow installation from that source.

Latest build workflow: https://github.com/ssuraj/rihan-star-game/actions/workflows/build-apk.yml

## Important project status
This is a lightweight prototype, not a finished AAA/production battle royale. Character models, animations, map variety, audio, mission depth, performance testing and release hardening still need substantial work. The current APK is not expected to be 500 MB–1 GB; its size should reflect real bundled content, not padding.

## Third-party license
The bundled Three.js engine is distributed under the MIT License; see [THREE-LICENSE.txt](app/src/main/assets/THREE-LICENSE.txt).
