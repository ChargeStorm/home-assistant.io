---
title: CTEK NANOGRID™ AIR
description: Instructions on how to integrate NANOGRID™ AIR device with Home Assistant.
featured: true
#ha_release: 
ha_category: Sensor
ha_iot_class: Local Polling
ha_config_flow: true
ha_codeowners: "@ChargeStorm"
ha_domain: nanogrid_air
ha_integration_type: integration
---

# CTEK NANOGRID™ AIR

The CTEK NANOGRID™ AIR integration facilitates seamless connectivity between your NANOGRID™ AIR wireless gateway energy meter and Home Assistant. This integration empowers you to optimize energy distribution within your home, ensuring efficient charging for your electric vehicles (EVs) while prioritizing power allocation for essential appliances.

{% include integrations/config_flow.md %}

## Troubleshooting

<div class='note'>
If you do not have mDNS, when adding integration, you need to add the IP address manually, otherwise it will be added automatically.
</div>

### Encountering issues? Here's what you can do

- Verify the NANOGRID™ AIR's connection to the electricity meter and ensure it's switched on.
- Consult the NANOGRID™ AIR manual for further troubleshooting guidance if needed.
- Attempt to resolve issues by disconnecting and reconnecting the NANOGRID™ AIR.

### Firmware updates

After updating your NANOGRID™ AIR's firmware, you may need to reconfigure the integration. Follow these steps if problems persist:

- Remove the integration through Settings > Integrations > CTEK NANOGRID™ AIR > Delete (trash can icon)

- Restart Home Assistant, then repeat the steps from the initial setup.
