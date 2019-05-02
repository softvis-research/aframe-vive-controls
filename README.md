# aframe-vive-controls

A-Frame module for HTC Vive featuring several navigation modes.

# Usage

```
<a-entity id="cameraRig" position="300 200 300" vive-control-rig>
  <a-camera id="viewpoint"></a-camera>
</a-entity>
```

## Menu (left hand)

| Button | Action |
| ------------- |:-------|
| Trackpad | switch through modes |
| Trigger | activate mode |

## Navigation mode: Laser

| Button | Action |
| -------|:-------|
| Trigger | Teleport |
| Grip Button | move up |
| Trackpad | move down |

## Navigation mode: fly-head

| Button | Action |
|--------|--------|
| Grip Button | move forward |
| Trigger + Grip Button | move backward |

## Navigation mode: fly-hand

| Button | Action |
|--------|--------|
| Trigger | rotate left |
| Trackpad | rotate right |
| Grip Button | move forward |
| Trigger + Grip Button | move backward |
