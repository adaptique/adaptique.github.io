---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header-bg.jpg
  actions:
    - label: "<i class='fas fa-download'></i> Explore our roadmap"
      url: "/roadmap/"
excerpt: >
  A modular blockchain infrastructure supporting WASM smart contracts and flexible access control.<br />
  <small>Current Version: 0.1.0-alpha</small>
---

## Key Features

- **Modular Chain Configuration**: Customize chain parameters and features
- **WASM Smart Contracts**: Write contracts in multiple languages
- **Flexible Access Control**: Pluggable authentication providers
- **Cross-Chain Communication**: Secure Base Pair Protocol
- **Enterprise Ready**: Support for permissioned and permissionless modes

## Getting Started


```bash
#Clone the repository
git clone https://github.com/adaptique/core.git
#Build from source
cd core
cargo build --release
```

## Latest Updates

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}

## Community

- [GitHub](https://github.com/adaptique)
- [Discord](https://discord.gg/adaptique)
- [Documentation](/docs/)
