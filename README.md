# sansung_s1_wifi_fix


Flash steps (publish these in your README)

Copy the ZIP to /sdcard (internal storage).

Boot to TWRP → Mount: tick System and Data.

Install → select WiFi_Quick_Fix_TWRP_FINAL.zip.

Reboot system.

Notes:

This patch disables PMF/IGTK (pmf=0, disable_pmksa_caching=1) and fixes Wi-Fi config perms/contexts.

It also best-effort repairs dhcpcd perms/contexts.

Backups of existing configs are created on flash with timestamps.
