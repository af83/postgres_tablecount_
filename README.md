# Installation

Copy `postgres_tablecount_` into the plugin directory of the pg node, launch autoconfiguration and restart munin node :

```bash
git clone https//github.com/af83/postgres_tablecount_.git
cd postgres_tablecount_.git
sudo cp postgres_tablecount_ /usr/local/share/munin/plugins/

sudo munin-node-configure --libdir /usr/local/share/munin/plugins --shell | sudo bash

sudo systemctl restart munin-node
```
