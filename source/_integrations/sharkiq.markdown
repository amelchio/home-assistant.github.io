---
title: Shark IQ
description: Instructions on how to integrate your Shark IQ vacuum robot with Home Assistant.
ha_category:
  - Vacuum
ha_iot_class: Cloud Polling
ha_release: 0.115
ha_config_flow: true
ha_codeowners:
  - '@amarks'
ha_domain: sharkiq
---

The `sharkiq` integration allows you to control your [Shark IQ](https://www.sharkclean.com/vacuums/robot-vacuums/) vacuum.

<p class='img'>
<img src='/images/screenshots/more-info-dialog-sharkiq.png' />
</p>

This platform has been tested and is confirmed to be working with the Shark IQ R101AE robot vacuum with self-empty base but should also work with the R100.

## Configuration

To add your Shark IQ vacuum to your installation, go to **Configuration** >> **Integrations** in the UI, click the button with + sign and from the list of integrations select Shark IQ.

## Services

Currently supported services are:

- `start`
- `pause`
- `stop`
- `return_to_base`
- `locate`
