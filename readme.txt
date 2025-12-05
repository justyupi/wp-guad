=== Simple Guard ===
Contributors: Kref Studio
Tags: security, login, turnstile, ban, protection
Requires at least: 6.0
Tested up to: 6.9
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Fail-ban + Cloudflare Turnstile integration for WordPress login/register/lostpassword + custom login page.

== Installation ==

1. Upload folder to wp-content/plugins
2. Activate plugin
3. Go to Simple Guard settings, set Site Key & Secret, configure thresholds.

== Notes ==

- Turnstile requires valid sitekey & secret from Cloudflare.
- Add your admin IP to whitelist to avoid lockout.