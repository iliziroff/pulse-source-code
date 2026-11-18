# Pulse for macOS

Pulse is one of the free projects from Softrora. It gives you a live view of your Mac’s CPU, memory, GPU, storage, network, and running processes. [Visit Softrora](https://softrora.com)

**Version 1.1.0** · macOS 13 or later · Apple Silicon and Intel

## Install Pulse

1. Extract `Pulse-1.1.0-macOS.zip` and open `Pulse-1.1.0.dmg`.
2. Drag **Pulse** onto **Applications** in the disk image window.
3. Eject the disk image, then open **Pulse** from Applications.

This build uses an ad hoc signature. macOS may block copies downloaded from the internet because the build has not been notarized by Apple. [Apple’s macOS distribution guidance](https://developer.apple.com/macos/distribution/)

## Use Pulse

- **Overview** shows system load, resource usage, and the three busiest processes. Choose a chart range from **1 min** to **1 hr**. Hover over the chart for exact readings, or focus it and use the arrow keys.
- **CPU**, **Memory**, and **GPU** show a breakdown for each resource. GPU readings depend on what the hardware and driver report. Pulse shows the thermal state reported by macOS when temperature in degrees is unavailable.
- **Storage** shows free space and read and write activity. **Network** shows download and upload rates and session totals for the selected interface.
- **Processes** lets you search by name or PID and sort by CPU or memory. **Terminate** asks for confirmation before sending a termination signal to an eligible process.
- **Settings** lets you choose **Dark**, **Light**, or **System** appearance and configure alerts. Use **Invert colors** at the bottom of the sidebar to switch between black and white themes.

Click the pause button or press **Command–P** to pause or resume monitoring. Pulse samples about once a second and keeps up to one hour of chart history in memory. Monitoring runs locally and sends no telemetry.

## Support and requests

Need help with Pulse, want to suggest a feature, or have an idea for another project? Email [support@softrora.com](mailto:support@softrora.com).
