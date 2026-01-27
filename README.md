# zolozkit
zolozkit for HarmonyOS
# Background
This repository provide an example to help customer to integrate ZOLOZ SDK with ease.
# Getting started
## Prequisites
Before integrating the ZOLOZ HarmonyOS SDK, ensure that your DevEco Studio version is 5.0.5or later.

# SDK Integration
## Step 1: Download and install SDK
1. Open the zolozkit repository:https://ohpm.openharmony.cn/ohpm/zolozkit
2. Select the desired ZOLOZKit version (it is recommended to use the latest version)
3. Install the package using the OHPM CLI

```json
ohpm install @zoloz/zolozkit@<version\>  

## Step 2: Importing SDK into Main Project
```arkts
//import zoloz
import {ZolozFacade,ZolozRequest,ZolozResponse} from "@zoloz/zolozkit"

//use
const request = new ZolozRequest(clientCfg, { rsaPubKey });
const response= await ZolozFacade.getInstance().startWithRequest(getContext(this),request);


