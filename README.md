# NodeRed Homekit TV

## 1. Допустимые значения переменных

### TargetVisibilityState
- 1: Shown
- 0: Hidden

### CurrentVisibilityState
- 1: Shown
- 0: Hidden

### TargetMediaState
- 0: Play
- 1: Pause
- 2: Stop

### Mute
- true
- false

### VolumeSelector
- 0: Increment
- 1: Decrement

### Volume
- 0..100

### RemoteKey
- 4: up
- 5: down
- 6: left
- 7: right
- 8: enter
- 9: back
- 11: play/pause
- 15: tv settings/info

## 2. Flow

#### Используемые flow nodes:
- node-red-contrib-lgtv
- node-red-contrib-advanced-ping
- node-red-contrib-homekit-bridged
- node-red-node-wol
