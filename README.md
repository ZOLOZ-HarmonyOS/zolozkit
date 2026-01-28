# zolozkit

ZOLOZKit for HarmonyOS

## Background

This repository provides an example to help customers integrate the ZOLOZ SDK with ease.

## Getting Started

### Prerequisites

Before integrating the ZOLOZ HarmonyOS SDK, ensure that your DevEco Studio version is **5.0.5 or later**.

## SDK Integration

### Step 1: Download and Install SDK

1. Open the ZOLOZKit repository: [https://ohpm.openharmony.cn/ohpm/zolozkit](https://ohpm.openharmony.cn/ohpm/zolozkit)
2. Select the desired `zolozkit` version (it is recommended to use the latest version).
3. Install the package using the OHPM CLI:

```bash
ohpm install @zoloz/zolozkit@<version>
```
### Step 2: Import SDK
```arkts
//import zoloz
import {ZolozFacade,ZolozRequest,ZolozResponse} from "@zoloz/zolozkit"

//use
const request = new ZolozRequest(clientCfg, { rsaPubKey });
const response= await ZolozFacade.getInstance().startWithRequest(getContext(this),request);

```
