# ESP32_MODBUS_PCB_MASTER
# PAS sprinkler / irrigation controller

## Pin Wiring  


| PIN NAME | RS485_U2TX | RS485_U2RX | RS485_U2EN | RS485_U1TX | RS485_U1RX | RS485_U1EN | OPAMP_VA1 | OPAMP_IA0 |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | --------- | --------- |
| PIN NUM  | GPIO22     | GPIO23     | GPIO19     | GPIO18     | GPIO10     | GPIO5      | GPIO34    | GPIO35    |

<br/>

| PIN NAME | RELAY_OUT0 | RELAY_OUT1 | RELAY_OUT2 | RELAY_OUT3 | RELAY_OUT4 | RELAY_OUT5 | RELAY_OUT6 | RELAY_OUT7 |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| PIN NUM  | GPIO33     | GPIO25     | GPIO32     | GPIO13     | GPIO15     | GPIO26     | GPIO4      | GPIO9      |

<br/>

| PIN NAME | GPIO_EX0 | GPIO_EX1 | GPIO_EX2 | GPIO_EX3 | DS1307_SCL | DS1307_SDA |
| -------- | -------- | -------- | -------- | -------- | ---------- | ---------- |
| PIN NUM  | GPIO39   | GPIO38   | GPIO37   | GPIO36   | GPIO27     | GPIO14     |

    

## Hardware

### Schematics

[![SCHEMATIC REVIEW](assets/demo/schematic.png)](assets/demo/schematic.pdf)
### PCB Layout
#### Top side

[![PCB REVIEW](assets/demo/pcb-top.png)](assets/demo/pcb-top.svg)

#### Back side

[![PCB REVIEW](assets/demo/pcb-bottom.png)](assets/demo/pcb-bottom.svg)

### 3D

#### Top side

![3D REVIEW](assets/demo/3d-top.png)

#### Back side

![3D REVIEW](assets/demo/3d-bottom.png)

### Gerber

Version 3.0

- [Gerber V3
.0](./assets/gerber/PAS_v3.0.rar)

### Remark

This project was in development phase - we will remove this remark after release

# License
