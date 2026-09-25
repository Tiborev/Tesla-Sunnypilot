# Tesla-Sunnypilot

> ⚠️ **PROJECT STATUS: NOT COMPLETED YET**

Custom Tesla Model 3 project built around sunnypilot/openpilot concepts, with a phone-based management interface and planned Tesla OEM camera integration.

## Current status

### Completed
- Phone → Manager API testing
- Manager → Agent communication
- Phone → Manager → Agent communication
- Settings/configuration API testing
- File staging/upload transport
- Local Manager/Agent test architecture

### In progress / not completed
- Final phone application
- Production integration with real sunnypilot
- Tesla OEM triple-camera / FPD-Link integration
- Final compute hardware selection
- Full vehicle validation and road testing

## Architecture direction

- **Base:** sunnypilot, with upstream openpilot used as reference where appropriate
- **Phone UI:** Custom-built application
- **Manager:** local API/control layer
- **Agent:** vehicle-side service layer
- **Cameras:** Tesla OEM triple forward camera assembly, planned FPD-Link III receiver path
- **Compute:** hardware selection remains open pending camera-interface validation

## Important

This repository documents an **unfinished development project**. It is not a completed autonomous-driving system and is not ready for deployment.

See `PROJECT_STATUS.md` for the working status and next steps.
