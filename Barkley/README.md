# Barkley: Unsupported Activ Driver

## Situation
Due to changes in microsoft windows 1903 and beyond, driver signing for specified older gen1 & gen 2 activboards cannot be done. Promethean issued a unsigned, unsupported driver `v5.18.16` that does not claim to be a proper fix to the issue but could help. This needs to be tested.

additionally firmware provided in this directory is the latest and final build for boards of this generation. It should be the one flashed to these boards. `proactiv3_76b1.bin`

***

### Computer Models

| Model | Desc |
|-------|------|
| 5580 | Confirmed crashing within a few minutes of attaching board without driver/firmware combo |
| 5570 | 1 instances where computer did not crash without special driver/firmware |
| 5510 | no crashing reported |

***

### Link to driver
https://promethean.my.salesforce.com/sfc/p/3000000002Zt/a/6f000000DS2K/qugvcuqF.lcw6VvNU92QnwbUzt_CpxY6L.61O3Z6.wI

***

### Findings

| Date  | Room | Description | Result | Software Tested |
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| 11/24 | 114 | Installed unsigned driver | ... | ...
| 11/24 | 114 | Testing board | No crash 30+ minutes. | touch control for windows, whiteboard, ActivInspire and Easy Interactive |
| 11/24 | 114 | Testing board | No crash 1hr+. Wacom and Activboard connected. | touch control for windows, whiteboard, ActivInspire and Easy Interactive |
| 11/30 | 114 | Teacher using board | Made it through two days of teaching 11/29 & 11/30 no crash | ... |
| 12/2 | 114 | Teacher using board | Board working 4 consecutive days! | ... |
| 11/2 | 311 | Set up board for teacher, Unidirectional type A to Type A usb was backwards. Taught how to calibrate. | Board functional. | Active inspire, whiteboard |
| 11/30 | 116 | Brought USB A to B for teacher. COnnected board, unsigned ActivDriver installed. Taught teacher how to calibrate | Board functional, demoed with teacher! | ActivInspire |
