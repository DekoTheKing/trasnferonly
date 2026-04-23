New-NetFirewallRule -DisplayName "CAPE Agent" -Direction Inbound -LocalPort 8000 -Protocol TCP -Action Allow
