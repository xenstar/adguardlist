# Xenstar AdGuard Home List

Personal AdGuard Home custom rules and the upstream filter collection used on my China-to-global ecommerce workstation and home network.

This repository has two purposes:

1. `adguardhome` contains my custom AdGuard Home rules.
2. This README documents the complete upstream filter setup currently configured in AdGuard Home.

## Subscribe

Copy this URL into **AdGuard Home -> Filters -> DNS blocklists -> Add a blocklist**:

```text
https://raw.githubusercontent.com/xenstar/adguardlist/main/adguardhome
```

## Custom rules

- Adobe, Microsoft, Spotify, Xiaomi, TikTok, Xiaohongshu, Taobao, DingTalk, Dida365, and other application-specific rules
- Tracking, telemetry, advertising, push-notification, and malware endpoints
- Deliberate allow rules for important login, media, ecommerce, productivity, and development services
- Client-specific rules where a service must remain available on a particular device

The published file is the custom-rule list for AdGuard Home. The repository does not publish credentials, client names, DNS settings, or the full private configuration.

## Important notes

Some broad domains are intentionally blocked and selectively allowed where required. In particular, Adobe, Microsoft, social platforms, and several China-based services may need local adjustments for your own devices and workflow.

Review the rules before using this list in a shared or production environment. Start with a normal filter update, then check AdGuard Home's query log if an application stops working.

## Upstream lists

These are the complete lists configured in my AdGuard Home instance. Add them under **Filters -> DNS blocklists** if you want to reproduce the setup.

| Status | List | URL |
| --- | --- | --- |
| Enabled | AdGuard DNS filter | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt` |
| Enabled | AdAway Default Blocklist | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_2.txt` |
| Enabled | HaGeZi's Pro++ Blocklist | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_51.txt` |
| Disabled | Perflyst and Dandelion Sprout's Smart-TV Blocklist | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_7.txt` |
| Enabled | CHN: anti-AD | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_21.txt` |
| Enabled | CHN: AdRules DNS List | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_29.txt` |
| Enabled | Dandelion Sprout's Anti Push Notifications | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_39.txt` |
| Enabled | HaGeZi's Windows/Office Tracker Blocklist | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_63.txt` |
| Enabled | Phishing URL Blocklist (PhishTank and OpenPhish) | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_30.txt` |
| Enabled | Dandelion Sprout's Anti-Malware List | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_12.txt` |
| Enabled | HaGeZi's DynDNS Blocklist | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_54.txt` |
| Enabled | HaGeZi's Encrypted DNS/VPN/TOR/Proxy Bypass | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_52.txt` |
| Enabled | HaGeZi's Threat Intelligence Feeds | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_44.txt` |
| Enabled | Phishing Army | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_18.txt` |
| Enabled | The Big List of Hacked Malware Web Sites | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_9.txt` |
| Enabled | OISD Blocklist Big | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_27.txt` |
| Enabled | HaGeZi Pop Ads | `https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/popupads.txt` |
| Enabled | HaGeZi DOH IP | `https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-ips.txt` |
| Enabled | OISD NSFW | `https://nsfw.oisd.nl/` |

### Allowlist

| Status | List | URL |
| --- | --- | --- |
| Enabled | HaGeZi Allowlist | `https://adguardteam.github.io/HostlistsRegistry/assets/filter_45.txt` |

## Status

| Field | Value |
| --- | --- |
| Last synced | 2026-09-02 |
| Source | AdGuard Home on `xenstar-home` |
| Custom rules | Published in `adguardhome` |
| Upstream lists | 18 enabled, 1 disabled |
| Allowlist | 1 enabled |
| Format | AdGuard Home DNS rules |

## License

This is a personal configuration published for reference. Use it at your own discretion.
