<p align="center">
  <img src="https://notificator-project.com/notificator-icon.png" alt="Notificator Project" width="92" height="92">
</p>

<h1 align="center">Notificator Project</h1>

<p align="center">
  Turn meaningful events into alerts you can act on.
</p>

<p align="center">
  <a href="https://notificator-project.com/get-started/"><strong>Get started</strong></a> ·
  <a href="https://notificator-project.com/">Website</a> ·
  <a href="https://docs.notificator-project.com/">Documentation</a> ·
  <a href="https://notificator-project.com/changelog/">Changelog</a> ·
  <a href="https://notificator-project.com/support/">Support</a>
</p>

Notificator is a free and open-source notification ecosystem for WordPress, Strapi, mobile apps, and compatible physical devices.

Discover useful WordPress events or define Strapi content rules, then choose where each alert belongs: in a local activity view, on your phone, by optional email, or on an MQTT-connected device.

## One event, several useful destinations

```text
WordPress or Strapi event
      ↓
Notificator notification rule
      ↓
Local activity · Mobile push · Optional email · MQTT device
```

WordPress dashboard alerts and the Strapi activity log work locally without an account or API key. Remote delivery is optional and can connect the mobile app, email alerts, and user-owned MQTT infrastructure.

## Projects

| Project                                                                     | What it provides                                                                                                                                                             |
| --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [WordPress Plugin](https://github.com/notificator-project/WordPress-Plugin) | Event discovery, ready-made templates, notification rules, dashboard alerts, mobile delivery, MQTT, activity history, and portable configuration exports.                    |
| [Strapi Extension](https://github.com/notificator-project/Strapi-Extension) | The `0.1.1` Strapi 5 preview for content lifecycle rules, local activity, signed remote delivery, mobile alerts, email, and user-owned MQTT without repeated lifecycle code. |
| [IoT Firmware](https://github.com/notificator-project/IoT-Firmware)         | Open-source ESP32 firmware, browser installation, signed OTA updates, and independent release channels for supported hardware.                                               |
| [Hosted API](https://github.com/notificator-project/public-api)             | The server-side notification ingestion and delivery service operated at `api.notificator-project.com`.                                                                       |
| [Node.js SDK](https://github.com/notificator-project/Node-SDK)              | The `@notificator-project/api` server client for sending typed alerts through the hosted API.                                                                                |
| [Documentation](https://github.com/notificator-project/Docs)                | Setup guides for the plugin, app, HiveMQ, Notificator Base, Notificator Touch, firmware installation, and integrations.                                                      |
| [Website](https://github.com/notificator-project/Website)                   | The public project website, Journal, support and privacy pages, changelog, and browser-based firmware installer.                                                             |

## Physical devices

Notificator is designed to work beyond the browser.

### Notificator Base

A compact maker-friendly reference device built around an ESP32-C3 SuperMini, SSD1306 OLED display, and capacitive control. Base firmware is the stable hardware channel.

### Notificator Touch

A touchscreen firmware preview for the Waveshare ESP32-S3 Touch LCD 3.49, with alert history, clock and weather views, audio, on-device Wi-Fi setup, orientation support, and dedicated settings.

### Notificator Matter

An upcoming device path intended to let selected Notificator alerts trigger compatible smart-home and office devices. It remains under development and is not yet available as a firmware release.

<table>
  <tr>
    <td width="50%">
      <img src="https://raw.githubusercontent.com/notificator-project/IoT-Firmware/main/hardware/showcase/notificator-base-alert.png" alt="Rendered Notificator Base device showing an alert">
    </td>
    <td width="50%">
      <img src="https://raw.githubusercontent.com/notificator-project/IoT-Firmware/main/hardware/showcase/notificator-touch-clock.png" alt="Rendered Notificator Touch device showing its clock and weather screen">
    </td>
  </tr>
</table>

More compatible firmware targets can be added without forcing different devices onto the same hardware assumptions or update channel.

## Built for choice and privacy

- Use WordPress dashboard alerts or Strapi activity without creating a Notificator account.
- Enable remote delivery only for notifications that need it.
- Connect compatible devices through your own HiveMQ Cloud cluster.
- Keep MQTT credentials out of the Notificator account database.
- Export saved WordPress notification configurations and reuse them across sites.
- Install supported firmware from the browser and continue with signed OTA updates.
- Review the project's external services and data handling in the [privacy policy](https://notificator-project.com/privacy/).

## Community

Notificator was first introduced publicly at [WordCamp Athens 2025](https://athens.wordcamp.org/2025/). Since then, tens of early-access devices have reached testers across multiple countries.

Feedback from early-access participants, the Greek WordPress community, WordPress contributors, makers, and open-source users continues to shape the project. Thank you to everyone who has tested a device, reported a problem, suggested an improvement, or helped someone else get started.

## Get involved

- Choose your path on the [Get Started page](https://notificator-project.com/get-started/).
- Read the [documentation](https://docs.notificator-project.com/).
- Follow meaningful releases in the [project changelog](https://notificator-project.com/changelog/).
- Open a focused issue in the repository that owns the affected component.
- Share integration ideas, hardware builds, accessibility feedback, and documentation improvements.
- Follow the project on [X](https://x.com/WP_Notificator) and [YouTube](https://www.youtube.com/@NotificatorProject).
- Support continued development through [GitHub Sponsors](https://github.com/sponsors/vagelisp) or [Buy Me a Coffee](https://buymeacoffee.com/vagelis).

## Independent and open source

Notificator is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by WordPress.org, the WordPress Foundation, Automattic, Strapi Solutions SAS, Waveshare, or HiveMQ.

References to WordPress and Strapi describe compatibility and participation in their open-source communities. References to Waveshare identify compatible hardware, while references to HiveMQ identify the currently supported user-owned MQTT service. Product names, trademarks, services, and terms remain the property of their respective owners.

Repository-specific licenses and third-party notices are documented in each project.
