## Password Managers

| Provider | Description |
| --- | --- |
**[1Password](https://1password.com)** | Fully-featured cross-platform password manager with sync. Plans starts at $3/month. They do regularly publish results of their independent [security audits](https://support.1password.com/security-assessments), and they have a solid reputation for transparently disclosing and fixing vulnerabilities
**[Bitwarden](https://bitwarden.com)**  | Fully-featured, open source password manager with cloud-sync. Bitwarden is easy-to-use with a clean UI and client apps for desktop, web and mobile. They have a free-forever option.
**[Padloc](https://padloc.app)** | A modern, open source password manager for individuals and teams. Beautiful, intuitive and dead simple to use. Apps available for all platforms and you can self-host it as well. They also have a basic plan for free, or their premium for $3.49/month.
**[KeePass](https://lastpass.com)** | Another cross-platform and fully-featured password manager. They used to be good, but after several breachs they are no longer in the top vendors. They also have a basic plan for free, or their premium for $3/month.

Password Managers are a must-have to help you with the very basics rules:
- Don't reuse Passwords
- Use a very strong Password
- Avoid sharing passwords


## 2-Factor Authentication

| Provider | Description |
| --- | --- |
**[Authy](https://authy.com/)** It is a popular option among new users, due to its ease of use and device sync capabilities.
**[Aegis](https://getaegis.app)** (Android)  | Free, secure and open source authenticator app for Android. Has a backup/ restore feature and a customisable UI with dark mode
**[Authenticator Pro](https://github.com/jamie-mh/AuthenticatorPro)** (Android) | Free and open-source two factor authentication app for Android. It features encrypted backups, icons, categories and a high level of customisation. It also has a Wear OS companion app
**[Tofu](https://www.tofuauth.com)** (iOS) | An easy-to-use, open-source two-factor authentication app designed specifically for iOS
**[Authenticator](https://mattrubin.me/authenticator/)** (iOS) | Simple, native, open source 2-FA Client for iOS, which never connects to the internet - built by @mattrubin.me
**[Raivo OTP](https://github.com/raivo-otp/ios-application)** (iOS) | A native, lightweight and secure one-time-password (OTP) client built for iOS; Raivo OTP! - built by @tijme
**[WinAuth](https://winauth.github.io/winauth)** (Windows) | Portable, encrypted desktop authenticator app for Microsoft Windows. With useful features, like hotkeys and some additional security tools, WinAuth is a great companion authenticator for desktop power-users. It's open source and well-established (since mid-2010)
**[Authenticator](https://gitlab.gnome.org/World/Authenticator)** (Linux) | Rust-based OTP authenticator. Has native With GNOME Shell integration. Also available through [flathub](https://flathub.org/apps/details/com.belmoussaoui.Authenticator).
**[Authenticator](https://authenticator.cc/)** (BrowserExtension) | Authenticator Extension is an in-browser One-Time Password (OTP) client, supports both Time-Based One-Time Password (TOTP, specified in [RFC 6238](https://tools.ietf.org/html/rfc6238) and HMAC-Based One-Time Password (HOTP, specified in [RFC 4226](https://tools.ietf.org/html/rfc4226).

2FA should be used on every social media and online services that offers it. With 2FA you dramatically increase your security.

## Browsers

| Provider | Description |
| --- | --- |
**[Brave Browser](https://brave.com)** | Brave Browser, currently one of the most popular private browsers - it provides speed, security, and privacy by blocking trackers with a clean, yet fully-featured UI. It also pays you in [BAT tokens](https://basicattentiontoken.org/) for using it. Brave also has Tor built-in, when you open up a private tab/ window.
**[Firefox](https://www.mozilla.org/firefox)** | Significantly more private, and offers some nifty privacy features than Chrome, Internet Explorer and Safari. After installing, there are a couple of small tweaks you will need to make, in order to secure Firefox. For a though config, see [@arkenfox's user.js](https://github.com/arkenfox/user.js/). You can also follow one of these guides by: [Restore Privacy](https://restoreprivacy.com/firefox-privacy/) or [12Bytes](https://12bytes.org/7750)

#### Notable Mentions
Mobile Browsers: [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/) Hardened fork of FF-Fenix (Android), [Firefox Focus](https://support.mozilla.org/en-US/kb/focus) (Android/ iOS), [DuckDuckGo Browser](https://help.duckduckgo.com/duckduckgo-help-pages/mobile/ios/) (Android/ iOS).

Additional Desktop: [Nyxt](https://nyxt.atlas.engineer/), [WaterFox](https://www.waterfox.net), [Epic Privacy Browser](https://www.epicbrowser.com), [PaleMoon](https://www.palemoon.org), [Iridium](https://iridiumbrowser.de/), [Sea Monkey](https://www.seamonkey-project.org/), [Ungoogled-Chromium](https://github.com/Eloston/ungoogled-chromium), [Basilisk Browser](https://www.basilisk-browser.org/) and [IceCat](https://www.gnu.org/software/gnuzilla/)

12Bytes also maintains a list privacy & security [extensions](https://12bytes.org/articles/tech/firefox/firefox-extensions-my-picks/)

#### Word of Warning
New vulnerabilities are being discovered and patched all the time - use a browser that is being actively maintained, in order to receive these security-critical updates.

Even privacy-respecting browsers, often do not have the best privacy options enabled by default. After installing, check the privacy & security settings, and update the configuration to something that you are comfortable with. 12Bytes maintains a comprehensive guide on [Firefox Configuration for Privacy and Performance](https://12bytes.org/articles/tech/firefox/firefoxgecko-configuration-guide-for-privacy-and-performance-buffs/)

**See also** [Browser & Search Security Checklist](https://github.com/Lissy93/personal-security-checklist/blob/master/README.md#browser-and-search) and recommended [Browser Extensions](#browser-extensions) for privacy & security.

## VPN

| Provider | Description |
| --- | --- |
**[VeraCrypt](https://www.veracrypt.fr)** | VeraCrypt is open source cross-platform disk encryption software. You can use it to either encrypt a specific file or directory, or an entire disk or partition. VeraCrypt is incredibly feature-rich, with comprehensive encryption options, yet the GUI makes it easy to use. It has a CLI version, and a portable edition. VeraCrypt is the successor of (the now deprecated) TrueCrypt.
**[Cryptomator](https://cryptomator.org)** | Open source client-side encryption for cloud files - Cryptomator is geared towards using alongside cloud-backup solutions, and hence preserves individual file structure, so that they can be uploaded. It too is easy to use, but has fewer technical customizations for how the data is encrypted, compared with VeraCrypt. Cryptomator works on Windows, Linux and Mac - but also has excellent mobile apps.
**[age](https://github.com/FiloSottile/age)** | `age` is a simple, modern and secure CLI file encryption tool and Go library. It features small explicit keys, no config options, and UNIX-style composability

If you need to create a compressed archive, then [PeaZip](https://www.peazip.org/) is a great little cross-platform open source file archiver utility. It allows you to create, open, and extract RAR TAR ZIP archives. It also has a [password-protection feature](https://peazip.github.io/peazip-password.html), which encrypts compressed files using AES-256, which is also compatible with most other archive utilities

## Search Engines

Google frequently modifies and manipulates search, and is in pursuit of eliminating competition and promoting their own services above others. They also track, collect, use and sell detailed user search and meta data.

| Provider | Description |
| --- | --- |
**[DuckDuckGo](https://duckduckgo.com/)** | DuckDuckGo is a very user-friendly, fast and secure search engine. It's totally private, with no trackers, cookies or ads. It's also highly customisable, with dark-mode, many languages and features. They even have a [.onion](https://3g2upl4pq6kufc4m.onion) URL, for use with Tor and a [no Javascript version](https://duckduckgo.com/html/)
**[Qwant](https://www.qwant.com/)** | French service that aggregates Bings results, with its own results. Qwant doesn't plant any cookies, nor have any trackers or third-party advertising. It returns non-biased search results, with no promotions. Qwant has a unique, but nice UI.
**[Startpage](https://www.startpage.com/)** | Dutch search engine that searches on google and shows the results (slightly rearranged). It has several configurations that improve privacy during use (it is not open source)

#### Notable Mentions
[MetaGear](https://metager.org), [YaCy](https://yacy.net), [Brave Search](https://search.brave.com/). 

[Searx](https://searx.github.io/searx/) and [SearXNG](https://github.com/searxng/searxng) are two self-hostable search engines that use the results of multiple other engines (such as Google and Bing) at the same time. They're open source and self-hostable, although using a [public instance](https://searx.space) has the benefit of not singling out your queries to the engines used.

12Bytes also maintains a list of [privacy-respecting search engines](https://12bytes.org/articles/tech/alternative-search-engines-that-respect-your-privacy/)

**See also** [Browser & Search Security Checklist](https://github.com/Lissy93/personal-security-checklist/blob/master/README.md#browser-and-search)
