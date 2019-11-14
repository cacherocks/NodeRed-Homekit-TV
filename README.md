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
- node-red-contrib-homekit-bridged (для полноценной работы пульта и громкости необходима dev версия 1.0)
- node-red-node-wol

![NodeRed Homekit TV](https://github.com/cacherocks/NodeRed-Homekit-TV/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202019-11-14%20%D0%B2%2017.30.25.png)
