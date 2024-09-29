# ArkTS Widget Calculator

### Overview

This sample shows how to develop a calculator model using the ArkTS widgets.

### Preview

| Adding a widget                                            | Preview the widget                                                   | Operating the widget                                            |
|--------------------------------------------------|---------------------------------------------------------|--------------------------------------------------|
| ![CalculatorAdd](screenshots/CalculatorAdd.en.png) | ![CalculatorPreview](screenshots/CalculatorPreview.en.png) | ![CalculatorUse](screenshots/CalculatorUse.en.png) |

### How to Use

1. Touch and hold an app icon to add it to the home screen.

2. Perform calculation on the widget.

### Project Directory

```
├──entry/src/main/ets                        // Code area
│  ├──calc
│  │  └──pages
│  │     └──CardCalc.ets                      // Calculator widget page
│  ├──entryability
│  │  └──EntryAbility.ets  
│  ├──entryability
│  │  └──EntryFormAbility.ets                 // File for periodically processing the widget declaration
│  ├──model
│  │  └──Logger.ts                            // Log file
│  └──pages
│     └──index.ets                            // Home page
└──entry/src/main/resources                   // App resource directory

```

### Required Permissions

N/A

### Constraints

1. The sample app is supported only on Huawei phones running the standard system.

2. The HarmonyOS version must be HarmonyOS NEXT Developer Beta1 or later.

3. The DevEco Studio version must be DevEco Studio NEXT Developer Beta1 or later.

4. The HarmonyOS SDK version must be HarmonyOS NEXT Developer Beta1 or later.
