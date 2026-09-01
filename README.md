# Xenstar AdGuard Home List

Personal AdGuard Home rules for a China-to-global ecommerce workstation and home network.

This list combines practical privacy blocking with carefully maintained exceptions for services that need to keep working. It is intended for **AdGuard Home**, not the AdGuard browser extension or mobile app.

## Subscribe

Copy this URL into **AdGuard Home -> Filters -> DNS blocklists -> Add a blocklist**:

```text
https://raw.githubusercontent.com/xenstar/adguardlist/main/adguardhome
```

## What is included

- Adobe, Microsoft, Spotify, Xiaomi, TikTok, Xiaohongshu, Taobao, DingTalk, Dida365, and other application-specific rules
- Tracking, telemetry, advertising, push-notification, and malware endpoints
- Deliberate allow rules for important login, media, ecommerce, productivity, and development services
- Client-specific rules where a service must remain available on a particular device

The published file contains the current global custom `user_rules` from my AdGuard Home instance. Client-scoped rules are omitted because they only apply to devices on my private network. The repository does not publish credentials, client names, DNS settings, or the full private configuration.

## Important notes

Some broad domains are intentionally blocked and selectively allowed where required. In particular, Adobe, Microsoft, social platforms, and several China-based services may need local adjustments for your own devices and workflow.

Review the rules before using this list in a shared or production environment. Start with a normal filter update, then check AdGuard Home's query log if an application stops working.

## Companion lists

The following upstream lists are currently enabled separately in AdGuard Home:

| List | Purpose |
| --- | --- |
| AdGuard DNS filter | General DNS protection |
| AdAway Default Blocklist | General advertising |
| HaGeZi's Pro++ Blocklist | Broad privacy and advertising coverage |
| CHN: anti-AD | China-focused advertising |
| CHN: AdRules DNS List | China-focused DNS rules |
| Dandelion Sprout's Anti Push Notifications | Push and notification endpoints |
| HaGeZi's Windows/Office Tracker Blocklist | Windows and Office telemetry |
| Phishing and malware lists | Threat protection |
| OISD Blocklist Big | Broad general-purpose coverage |
| HaGeZi Pop Ads | Pop-up advertising |
| HaGeZi DOH IP | Encrypted DNS bypass endpoints |
| OISD NSFW | Optional content category |

## Status

| Field | Value |
| --- | --- |
| Last synced | 2026-09-02 |
| Source | AdGuard Home on `xenstar-home` |
| Rules | 694 global custom rules |
| Format | AdGuard Home DNS rules |

## License

This is a personal configuration published for reference. Use it at your own discretion.
