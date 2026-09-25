# Project Status

## ⚠️ NOT COMPLETED YET

This is a work-in-progress research and development project. The items below reflect the current state and are intentionally not presented as a finished system.

## Completed

- Phone → Manager API tested
- Manager → Agent communication tested
- Phone → Manager → Agent communication tested
- Settings/configuration API tested
- File staging/upload transport tested
- Local navigation/API protocol defined and tested at the Manager interface level
- Lovable external navigation protocol documented
- Tesla Model 3 OEM triple-camera assembly identified for further hardware investigation

## Not completed

- Final Lovable phone application
- Production integration with the real sunnypilot codebase
- Final Tesla OEM camera interface implementation
- FPD-Link III receiver/deserializer hardware integration
- Final compute-platform selection
- Vehicle-side production deployment
- Full end-to-end vehicle validation
- Road testing and safety validation

## Current direction

The development direction is to use **sunnypilot as the primary software base**, with upstream comma.ai openpilot used as a reference where useful.

The phone is intended to provide the main configuration/management interface rather than reproducing the full Comma driving UI.

The Tesla OEM triple forward-facing camera assembly is being investigated as the preferred camera source. The planned signal path involves automotive FPD-Link III deserialization and a Linux-capable compute platform.

## Next major steps

1. Build the Lovable phone frontend against the already tested Manager API.
2. Inspect the incoming Tesla camera assembly and identify the exact signal/connectors/serializer configuration.
3. Select and test the FPD-Link III receiver path.
4. Select the production compute platform.
5. Integrate the required components into real sunnypilot.
6. Perform controlled hardware and vehicle validation.

## Status rule

Until the above work is completed and validated, this project must be treated as **experimental / development-only**.
