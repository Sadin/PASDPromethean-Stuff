# Barkley: Unsupported Activ Driver

## Situation
Due to changes in microsoft windows 1903 and beyond, driver signing for specified older gen1 & gen 2 activboards cannot be done. Promethean issued a unsigned, unsupported driver `v5.18.16` that does not claim to be a proper fix to the issue but could help. This needs to be tested.

additionally firmware provided in this directory is the latest and final build for boards of this generation. It should be the one flashed to these boards. `proactiv3_76b1.bin`

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
