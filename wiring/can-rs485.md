# DB9 / DF13 and CAN / RS-485 Reference

This table documents the shared DF13 2-pin connector used for either **CAN** or **RS-485** communication.  
It is used by the [Open Motor Driver Initiative](https://github.com/open-dynamic-robot-initiative/open-motor-driver-initiative) and other projects at **LAAS-CNRS**.

| DF13 Pin | Wire Color | Mode: CAN      | Connects to (DB9 CAN) | Mode: RS-485     | Connects to (DB9 RS-485) |
|----------|------------|----------------|------------------------|------------------|---------------------------|
| 1        | Yellow     | CAN_H          | Pin 7                  | RS-485 A (D−)    | Pin 2                     |
| 2        | Green      | CAN_L          | Pin 2                  | RS-485 B (D+)    | Pin 3                     |

