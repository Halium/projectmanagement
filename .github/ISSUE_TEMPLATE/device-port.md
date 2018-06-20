---
name: Device port
about: Template for tracking progress of device ports
---

Tree: <!-- halium-5.1 or halium-7.1 -->

- [ ] Create manifest <!-- Link to the manifest, contained in a pull request to https://github.com/Halium/halium-devices -->
- [ ] Boot image and system image build successfully
- [ ] Device boots into rootfs, `usb: Manufacturer: GNU/Linux Device` appears in `dmesg` on host.
- [ ] LXC container starts and does not crash
- [ ] libhybris tests
  * [ ] test_gps
  * [ ] test_hwcomposer
  * [ ] test_lights
  * [ ] test_vibrator
  * [ ] test_wifi
  * [ ] test_sensors
  * [ ] test_audio
  * [ ] test_camera
  * [ ] test_input
  * [ ] test_nfc
  * [ ] test_recorder

<!-- 
Other information goes below this comment. Possible topics of comment may 
include special flashing or building instructions, such as manual effort to
change vendor files.
-->
