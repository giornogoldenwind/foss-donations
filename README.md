# FOSS Donations

This is a personal collection of donation pages for FOSS projects and other
adjacent efforts, because I'm tired of keeping them on a text file that might
get obliterated the next time I attempt to perform an "exotic" operation to my
computer.

I think this list could help others (and I doubt making this list public on a
pseudonymous GitHub account will change my security posture against current
nation state adversaries).

I'll try to keep this updated, but I don't make any promises that this list will
always be free of dead links.

Some general guidelines:

* The list order is alphabetical.
* This is the order of credit/debit card donations:
    * Direct (sort of rare, especially tax deductible)
    * [Open Collective](https://opencollective.com/), which is tax deductible
    * [Liberapay](https://en.wikipedia.org/wiki/Liberapay), which is tax deductible
    * [GitHub Sponsors](https://en.wikipedia.org/wiki/GitHub#GitHub_Sponsors),
      which is not tax deductible but at least covers the transaction fees so
      that recipients keep the full donation amount
    * PayPal, but only if other methods are scarce
    * Patreon, which isn't great for FOSS development but still mentioned if not
      many methods exist
* Highlight Monero or Zcash, if available

### Warning
As Casey Neistat would say in his smartphone reviews, this is a **very biased**
list (i.e., absolutely not neutral), as my opinions have ended up leaking out
throughout the list.  As a fair warning, inserting my opinionated thoughts was a
nonlinear fashion, so the ordering may not make any sense to outside readers.

## Fundable
These projects accept direct donations in some shape, fashion, or form.

### [Bromite](https://www.bromite.org/)

This non-[Tor](https://en.wikipedia.org/wiki/Tor_(network)) browser has
[ad blocking](https://en.wikipedia.org/wiki/Ad_blocking), so this makes web
browsing on an Android device more bearable.  (I'm looking at you with contempt,
[Vanadium](https://github.com/GrapheneOS/Vanadium) - which can only be used on
GrapheneOS devices and lacks dark theme rendering of web pages and always-on
Incognito mode.  I don't give a hoot if installing Bromite via
[Droid-ify](https://github.com/Iamlooker/Droid-ify) [breaks](https://wonderfall.dev/fdroid-issues/)
the Android security model - as long as Michael Bazzell recommends some form of
F-Droid, I'll keep my F-Droid repository apps updated via Droid-ify.  Shut your
mouth and either improve F-Droid or make a better competitor to F-Droid.)

* [Info page](https://www.bromite.org/#donate)
    * Credit/debit card via [Patreon](https://www.patreon.com/csagan5)
    * Cryptocurrency

### [GrapheneOS](https://en.wikipedia.org/wiki/GrapheneOS)

The alternative Android OS that Snowden recommends, back in
[2019](https://nitter.lacontrevoie.fr/Snowden/status/1175430722733129729#m)
before [_Permanent Record_](https://en.wikipedia.org/wiki/Permanent_Record_(autobiography))
was published and in [November 2022](https://nitter.lacontrevoie.fr/Snowden/status/1588472045960327168#m).
GrapheneOS lets you experience which settings in out-of-the-box stock Android
come from are part of [AOSP](https://en.wikipedia.org/wiki/Android_(operating_system)#AOSP)
and which only exist with [Google Play Services](https://en.wikipedia.org/wiki/Google_Play_Services).
GrapheneOS does custom Android OS correctly, even porting the latest Android
versions to its stable release channels than even Google itself for
out-of-the-box Pixels.

* [Info page](https://grapheneos.org/donate)
    * Credit/debit card via [GitHub Sponsors](https://github.com/sponsors/thestinger)
      to lead developer Daniel Micay
    * Various cryptocurrency options
      * Includes Monero

### [KeePassDX](https://www.keepassdx.com/)

This is the Android version of [KeePass](https://en.wikipedia.org/wiki/KeePass).
KeePassDX is influenced to be modern, like KeePassXC.  This works great,
especially if you simply want a copy your KeePassXC database
[protected](https://keepassxc.org/docs/#faq-yubikey-2fa) with a YubiKey 4/5 NFC
device to still [work](https://github.com/Kunzisoft/KeePassDX/wiki/Hardware-Key#yubikey)
on your Android device, via either [USB OTG](https://en.wikipedia.org/wiki/USB_On-The-Go)
or [NFC](https://en.wikipedia.org/wiki/Near-field_communication).

* [Info page](https://www.keepassdx.com/#donation)
    * [Liberapay](https://liberapay.com/Kunzisoft/donate)
    * PayPal for credit/debit card

### [KeePassXC](https://en.wikipedia.org/wiki/KeePassXC)

IMHO, KeePassXC is the best local password manager.  It's included in Tails
(well, the version that Debian Stable is stuck with, which isn't the fault of
Tails) and looks much better than the Windows native [KeePass](https://en.wikipedia.org/wiki/KeePass).
Need I need to say more?  (If only SoloKeys could implement
[`hmac-secret`](https://github.com/Kunzisoft/KeePassDX/wiki/Hardware-Key#solokey)...)

* [Info page](https://keepassxc.org/donate/)
    * Credit/debit card
        * [Open Collective](https://opencollective.com/keepassxc)
        * [Liberapay](https://liberapay.com/keepassxc)
        * PayPal
        * GitHub Sponsors
            * But only individual pages for the three lead developers
        * Patreon
            * Two different accounts for client and browser add-on

### [Molly](https://molly.im/)

Molly is a security hardened fork of Signal that offers a local message database
encryption with a separate password (this is why I have to use KeePassXC to use
a random 128 character password to unlock Molly), a FOSS variant (which avoid
any proprietary libraries, unlike the Signal app for Android), removal of
MobileCoin, and automatic blocking of Signal users not in your contact book.
There once was a time when Signal truly cracked down on any third-party fork of
the Signal client on Android, but things at Signal seem to have changed since
2020.  (However, I won't dig any of that stuff up, because the neurotic minutia
combing in those primary sources is genuinely painful to pull up.)  That being
said, you are [trusting](https://blog.privacyguides.org/2022/07/07/signal-configuration-and-hardening/#caveats)
Molly, as it updates every two weeks (unless there are security updates), on top
of Signal with respect to the total number of development entities to trust.
For more info, see the 2022 Signal Configuration and Hardening Guide from
[Privacy Guides](https://blog.privacyguides.org/2022/07/07/signal-configuration-and-hardening)
(which will probably be moved in the next two weeks to effectively remove all
mentions of GitHub's "front end" with respect to contributors, even though you
can't get rid of all of the contribution history for the
[site](https://github.com/privacyguides/privacyguides.org/graphs/contributors)
and the [blog](https://github.com/privacyguides/blog.privacyguides.org/graphs/contributors)
- until the Privacy Guides team eventually does exactly that by moving everything
to a new repository to do exactly what I thought those people would never dare
to do).

* [Donation page](https://molly.im/#projects)
    * [Open Collective](https://opencollective.com/mollyim)
    * Cryptocurrency: [Monero](https://molly.im/project/monero/)

### [Qubes OS](https://en.wikipedia.org/wiki/Qubes_OS)

Edward Snowden mentioned using Qubes OS in
[September 2016](https://nitter.lacontrevoie.fr/Snowden/status/781493632293605376),
[December 2017](https://nitter.lacontrevoie.fr/Snowden/status/941020119609892864#m),
 and in [August 2019](https://nitter.lacontrevoie.fr/Snowden/status/1165607338973130752#m)
(right before _Permanent Record_ was published).  The last mention calls out the
usage of the Whonix gateway in Qubes OS.  The overall UX is rough, as the second
mention alludes to, but the security offered by Qubes OS is definitely real (as
the only potential competitor [Subgraph](https://en.wikipedia.org/wiki/Subgraph_(operating_system))
hasn't updated since September 2017).

* [Info page](https://www.qubes-os.org/donate/)
    * [Open Collective](https://opencollective.com/qubes-os)
    * Several cryptocurrency options

### [Signal](https://en.wikipedia.org/wiki/Signal_(software))

Signal has been mentioned by Snowden many, many times - but I'll cover a few.
The FBI already [knew](https://nitter.lacontrevoie.fr/Snowden/status/661313394906161152#m)
Snowden uses Signal in November 2015; Snowden had a "regular" 
[PSA](https://nitter.lacontrevoie.fr/Snowden/status/778592275144314884#m)
praising Tor and Signal in September 2016; Snowden suggests using Signal,
instead of e-mail, for truly private communications in
[2019](https://nitter.lacontrevoie.fr/Snowden/status/1175437588129308672#m)
before _Permanent Record_ came out; and Snowden says that he hasn't died from
using Signal in [January 2021](https://nitter.lacontrevoie.fr/Snowden/status/1347217810368442368#m).
Signal isn't perfect - but Tor and Qubes OS are the same.

* Direct [donation page](https://signal.org/donate/)
    * Credit/debit card
    * Many cryptocurrency options
        * Zcash, but no Monero? C'mon!
        * Ironically, not even [MobileCoin](https://en.wikipedia.org/wiki/MobileCoin)
          is accepted?  Pathetic!

### [SoloKeys](https://solokeys.com/)

SoloKeys is an open-source hardware security key for
[2FA](https://en.wikipedia.org/wiki/Multi-factor_authentication), which is for
the older U2F protocol or the newer FIDO2 protcol of [WebAuthn](https://en.wikipedia.org/wiki/WebAuthn).
This is a good alternative to YubiKey Security Key (but not the YubiKey 5 NFC
for securing a KeePassXC database).  There's nothing wrong with the security
keys from [Nitrokey](https://en.wikipedia.org/wiki/Nitrokey), but those residing
in the U.S. could simply source perfectly equivalent security keys from the Solo
1 series from North America rather than going across the Atlantic Ocean for a
Nitrokey device.  At the very least SoloKeys could help lower shipping costs to
those in the U.S. and North America.

* Credit/debit card via [GitHub Sponsors](https://github.com/sponsors/solokeys)
    * Though the most effective support is buying SoloKeys or contributing code

### [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia)
* [Donation page](https://donate.wikimedia.org/w/index.php?title=Special:LandingPage&country=US&uselang=en)
    * This happens to be the English language and US country page
    * Find the donate link on the [homepage](https://www.wikipedia.org/) to
      correctly generated donate page for your locale

## Not fundable
These projects can't be funded with traditionally direct donations.

### [Betrusted](https://betrusted.io/)
* Contributing code back to Betrusted on [GitHub](https://github.com/betrusted-io)
  and debugging both [Precursor](https://www.crowdsupply.com/sutajio-kosagi/precursor)
  and [Xous](https://xous.dev/) is most effective
* Note: December 2022
* Support hardware hacker [Andrew "bunnie" Huang](https://en.wikipedia.org/wiki/Andrew_Huang_(hacker))
  via [GitHub Sponsors](https://github.com/sponsors/bunnie)
* Support software hacker and fellow collaborator Sean Cross via
  [GitHub Sponsors](https://github.com/sponsors/xobs)

### [Droid-ify](https://github.com/Iamlooker/Droid-ify)

Droid-ify installs F-Droid repository apps without any permissions - unlike
F-Droid.  F-Droid isn't perfect by any means, but Droid-ify improves the UI and
UX of F-Droid.  Still, Droid-ify doesn't fix any of the fundamental issues of
F-Droid.  (If you want to keep an eye on a future app store that has the
unmatched power and seamless experience of GrapheneOS's [App store](https://github.com/GrapheneOS/Apps)
with the possibility of having the availability of F-Droid without its inherent
security shortcomings, then get to know the [Accrescent](https://accrescent.app/)
app store.)  That being said, I do not care what Privacy Guides has to say if
Michael Bazzell pays no mind to that group and Neo Store's UI feels as cluttered
(if not more cluttered) than the Google [Play Store](https://en.wikipedia.org/wiki/Google_Play)
itself.  (If Molly lets its users decide between using the auto-updater and the
F-Droid repo like actual adults, then I can manage my decision as as adult as
well.)

### [System76](https://en.wikipedia.org/wiki/System76)
* Just buy System76 hardware for the most direct support
#### [Pop!\_OS](https://en.wikipedia.org/wiki/Pop!_OS)
* Show symbolic support with $1/month
    * Click on the `SUPPORT POP` button to create a System76 account
