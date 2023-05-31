# 5. Localization change Сonfiguration

#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-wireguard-vpn) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-WireGuard-VPN/) | [FAQ](https://faq.puqcloud.com/)

To ensure the functionality of changing localization, you need to make some settings. We will give an example of such a configuration with two independent installations where "(UA) PUQ WireGuard VPN" and "(PL) PUQ WireGuard VPN" are two different packages that have two independent groups of servers and have different locations. In our example, we simulate two localizations and the ability to change client packages, which allow changing localization, it is also worth noting that in our configuration example, many servers are used in each of the two groups, where the server is selected according to the least loaded one, which is necessary for correct load distribution between servers.

<p class="callout warning">Attention! For the correct operation of this functionality, available servers are required. If the server is unavailable, changing the package when changing the locale will fail.</p>

##### 1. Add necessary services according to your requirements. ([How to add servers](https://doc.puq.info/books/wireguard-vpn-whmcs-module/page/3-add-server-puqvpncp-in-whmcs))

[![image-1685367366465.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685367366465.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685367366465.png)

##### 2. Add your servers to specific server groups. 

Add your servers for the first group:

[![image-1685368563207.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685368563207.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685368563207.png)

Add your servers for the second group:

[![image-1685368168505.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685368168505.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685368168505.png)

Server groups look like this:

[![image-1685382812370.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685382812370.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685382812370.png)

<p class="callout info">Note. Currently only the "Add to the least full server" scenario is implemented.</p>

##### 3. Select the appropriate server groups in the corresponding product.

Choose your servers group for the first product:

[![image-1685383882558.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685383882558.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685383882558.png)

Choose your servers group for the second product:

[![image-1685384078535.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685384078535.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685384078535.png)

##### 4. Select the appropriate package to update.

Choose your package update for the first product:

[![image-1685388455583.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685388455583.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685388455583.png)

Choose your package update for the second product:

[![image-1685388803760.png](https://doc.puq.info/uploads/images/gallery/2023-05/scaled-1680-/image-1685388803760.png)](https://doc.puq.info/uploads/images/gallery/2023-05/image-1685388803760.png)

<p class="callout info">Note. Please note that in order to avoid double notification, notification by means of WHMCS is disabled, because a custom notification will be used.</p>