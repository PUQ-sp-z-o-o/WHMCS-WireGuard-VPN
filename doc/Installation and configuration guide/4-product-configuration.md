# 4. Product Configuration

#####  [Order now](https://puqcloud.com/index.php?rp=/store/whmcs-module-wireguard-vpn) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-WireGuard-VPN/) | [FAQ](https://faq.puqcloud.com/)

### Add new product to WHMCS

```
System Settings->Products/Services->Create a New Product
```

In the **Module settings** section, select the **"PUQ WireGuard VPN"** module

![image](https://github.com/PUQ-sp-z-o-o/WHMCS-WireGuard-VPN/assets/81689153/06a99f12-c54a-4863-abbc-3b1bb503adc3)

- **License key:** A pre-purchased license key for the **"PUQ WireGuard VPN"** module. For the module to work correctly, the key must be active

### VPN Server

- Please select your server from the list. The list is loaded inconsistently from the server **[PUQVPNCP](https://doc.puq.info/books/puqvpncp/page/description)**, you may need to log in to the panel to make changes.

### Link settings

- **Link to instruction -** If you have prepared instructions for your customers on how to use the service, then a link to the instructions is provided here (If filled, it will be shown in the client area)
- **Link to VPN clients -** Link to download the VPN client. For example [https://www.wireguard.com/install/](https://www.wireguard.com/install/) (If filled, it will be shown in the client area)

### E-mail configuration
- **Custom Welcome Email** - Drop-down list of available e-mail templates for the action of creating a new client account. Please note that it is necessary to disable the standard welcome email in order to avoid double notification
- **Custom Change localization Email** - Drop-down list of available e-mail templates for the localization change action (package change) for the client account. Please note that you need to disable the standard package change email to avoid double notification.


### VPN users settings

- **Bandwidth Download** - Bandwidth Download of VPN accounts <span style="color: #ff00ff;">**(package change)**</span>
- **Bandwidth Upload -** BandwidthUpload of VPN accounts <span style="color: #ff00ff;">**(package change)**</span>
