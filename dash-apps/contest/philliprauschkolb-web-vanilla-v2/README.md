# Vanilla v2

**Category:** web

Vanilla v2 rebuilds the Vanilla dashboard around a real-time 3D scene written in plain WebGL 2, with no libraries and no build step. Your Tesla (a Model Y or Model 3; long-press anywhere to switch, tap the car to change its paint) drives a road that curves with the steering wheel. The car leans and steers its front wheels, and its wheels spin with your speed. The scene reacts to the car's data:

- **Blind spots:** cars slide into the next lane when a blind spot is flagged. They're a random Model Y, Model 3 or Cybertruck, and turn red when the warning is urgent.
- **Driver assist:** a green highlight with forward-flowing chevrons fills your lane while assist is on.
- **Traffic lights:** a lit signal, with its stop line, appears at the distance the car reports.
- **Park:** the camera swings to a front three-quarter studio view with a soft floor reflection.
- **Reverse:** the camera switches to a top-down view.
- **Dark mode:** turns the scene to night with headlight beams on the road.

Around the 3D scene sits Vanilla's instrument layer: speed, gear, power/regen bar, turn signals, cruise set speed, speed limit, battery and odometer. Open `index.html?demo=cycle` in a browser for a 30-second loop that runs through all of it.

## Credits

| Asset | Source | License |
|---|---|---|
| `model_y.glb` (Tesla Model Y) | Adapted for this dashboard from a third-party OBJ model: converted to glTF, interior and hidden geometry removed, materials and tail lights reworked. | |
| `model_3.glb` (Tesla Model 3) | Adapted for this dashboard from a third-party FBX model: converted to glTF, interior removed, glass made opaque, underbody panels added in code. | |
| `cybertruck.glb` (Tesla Cybertruck) | Adapted for this dashboard from a third-party glTF model: interior removed, glass and materials reworked. | |
| `fonts/inter-*.ttf` (Inter) | [Inter](https://rsms.me/inter/) by Rasmus Andersson, copied from `web-vanilla` | SIL Open Font License 1.1 |
| `left.png`, `right.png`, `seat-belt.png`, `car-door.svg`, `steering-wheel.svg`, `experimental.png` | The original Vanilla dashboard in this repo (`dash-apps/web-vanilla`) | This repo's MIT license |
| 3D scene, road, traffic light, studio floor, shaders | Written for this dashboard | This repo's MIT license |

"Tesla", "Model Y", "Model 3" and "Cybertruck" are trademarks of Tesla, Inc. This project is not affiliated with or endorsed by Tesla.
