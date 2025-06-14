# ZMPT101B component for ESPHOME

## Example

```YAML
external_components:
  - source: github://eringerli/esphome-zmpt101b
    components: [zmpt101b]
    
zmpt101b:
  - id: voltage_l1
    adc_pin: 34
  - id: voltage_l2
    adc_pin: 36
  - id: voltage_l3
    adc_pin: 39
```
