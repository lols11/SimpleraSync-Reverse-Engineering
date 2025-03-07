# SimpleraSync-Reverse-Engineering
![License](https://img.shields.io/static/v1?label=License&message=MIT&color=green)

> [!CAUTION]
> This repository is for educational purposes only.
> No modified medical device may be used for making medical decisions.

Reverse Engineering the Simplera Sync rtCGM Sensor


## About Simplera Sync
Simplera sync is a real-time continuous glucose monitoring (rtCGM) sensor that works with the 780G pump. Connecting the sensor to the pump enables the activation of the closed-loop system (SmartGuard), which automatically calculates and delivers basal insulin as well as any necessary corrections.

## Why?
I don't like it when companies force me to use only their product and/or ecosystem, especially when the product is overpriced for what it offers. The argument that the price reflects the cost of research, studies, and future development does not convince me at all—especially since other companies producing rtCGM systems have proven that it can be done better and cheaper.

## Main goals
- Understanding the Bluetooth protocol
- Enabling the connection of a different rtCGM
- Extending the sensor's lifespan

## Sensor inside
![RUIDe49194a1502a47bea1aec57cb6344361](https://github.com/user-attachments/assets/c9f00b3c-a7e8-4bee-8dc7-af27c8130543)
![aa](https://github.com/user-attachments/assets/aad8f484-7a38-4840-8fe3-5acac8d36891)
![IMG_20250307_191744](https://github.com/user-attachments/assets/cd339730-2250-440a-850d-3dbb6208a1d5)

### Battery

Connected in series
2x MAXELL SR927W
[V]: 1,55

![IMG_20250307_190045](https://github.com/user-attachments/assets/63610838-b8c4-40fa-86e1-fe776db28c98)

### IC's
![IMG_20250307_190259](https://github.com/user-attachments/assets/fb725164-ff82-49f7-83d9-666b0ee72508)
![IMG_20250307_191708](https://github.com/user-attachments/assets/951ad68e-d13c-4826-a19a-57467259d3a0)
![IMG_20250307_191656](https://github.com/user-attachments/assets/9ffe03bc-983d-4421-9233-02454c609773)

And an unknown bare die chip with no markings. (right side in the above photo)

Licensed under the MIT License. See LICENSE file for details.
