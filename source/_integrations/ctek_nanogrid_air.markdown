---
title: CTEK Nanogrid Air
description: Instructions on how to integrate Nanogrid Air device with Home Assistant.
#featured: true
#ha_release: 
ha_category: Sensor
ha_iot_class: Local Polling
ha_config_flow: true
ha_codeowners: "@ChargeStorm"
ha_domain: nanogrid_air
ha_integration_type: integration
---

# CTEK Nanogrid Air
The CTEK Nanogrid Air integration allows you to connect your Nanogrid Air wireless gateway energy meter to Home Assistant. The gateway safely and automatically balances the energy load in the your home at any time of the day, allowing you to charge your EVs while your appliances still get the power they need.

{% include integrations/config_flow.md %}

## Troubleshooting
<div class='note'>
If you do not have mDNS, when adding integration, you need to add the IP address manually, otherwise it will be added automatically.
</div>

### If you encounter problems
- Check that the Nanogrid Air is connected to the electricity meter and that it is turned on.
- Refer to the Nanogrid Air manual for troubleshooting steps if it is not turned on.
- Disconnect the Nanogrid Air and reconnect it.

### Firmware updates
After updating your Nanogrid Air firmware it might be necessary to repeat the configuration process. If you encounter problems:
- When configured using the integration: Remove the integration through Settings > Integrations > CTEK Nanogrid Air > Delete (trash can icon)

Restart Home Assistant. Then repeat the steps like during initial setup.
