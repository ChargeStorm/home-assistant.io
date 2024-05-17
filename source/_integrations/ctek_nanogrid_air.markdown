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

The CTEK Nanogrid Air integration facilitates seamless connectivity between your Nanogrid Air wireless gateway energy meter and Home Assistant. This integration empowers you to optimize energy distribution within your home, ensuring efficient charging for your electric vehicles (EVs) while prioritizing power allocation for essential appliances.

{% include integrations/config_flow.md %}

## Troubleshooting

<div class='note'>
If you do not have mDNS, when adding integration, you need to add the IP address manually, otherwise it will be added automatically.
</div>

### Encountering issues? Here's what you can do

- Verify the Nanogrid Air's connection to the electricity meter and ensure it's switched on.
- Consult the Nanogrid Air manual for further troubleshooting guidance if needed.
- Attempt to resolve issues by disconnecting and reconnecting the Nanogrid Air.

### Firmware updates

After updating your Nanogrid Air's firmware, you may need to reconfigure the integration. Follow these steps if problems persist:

- When configured using the integration:
  Remove the integration through Settings > Integrations > CTEK Nanogrid Air > Delete (trash can icon)

- Restart Home Assistant, then repeat the steps like during initial setup.
