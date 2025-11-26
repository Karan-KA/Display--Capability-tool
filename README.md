# Display--Capability-tool
A lightweight diagnostic tool that reads and analyzes EDID and DPCD data to reveal the full capabilities of a connected display. This tool is designed for display engineers, GPU driver developers, testers, and enthusiasts who need accurate, low-level information about HDMI/DP capabilities.

EDID Reader (HDMI + DisplayPort)

Extracts and decodes EDID directly from the Windows registry:

Manufacturer, model, serial number

Native resolution

Full list of supported resolutions & refresh rates

Detailed Timings (DTD)

Pixel Clock, HTotal, VTotal

HDR formats (HDR10, HLG, Dolby Vision flag)

Supported color formats (RGB, 4:4:4, 4:2:2, 4:2:0)

Bit depth support (8/10/12-bit)

HDMI VSDB parsing (HDMI 1.4 / 2.0 / 2.1 capabilities)

HDMI VRR, ALLM, QMS flags (if present)

🔹 DPCD Reader (DisplayPort Only)

Reads DisplayPort configuration data from the DPCD registers:

DisplayPort version (1.1 → 2.1)

Maximum link rate (RBR/HBR/HBR2/HBR3/UHBR)

Lane count (1/2/4)

DSC + FEC support

MST capability

AdaptiveSync (VRR) range

Link training status

Error counters (optional)
