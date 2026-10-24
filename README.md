# Chirag

**I build small, honest software for problems that are already being handled badly.**

Most of it is for India — GST, payroll, KYC names, Hinglish — because that is where the
paperwork is heaviest and the tools are worst. Everything runs on your own machine.
No accounts, no uploads, no "connect your cloud project".

<br>

## Live, right now

<table>
<tr>
<td width="25%" valign="top">

**[concord](https://chirag120670598-dotcom.github.io/concord/)**
<br><sub>`GST`</sub>

Reconciles GSTR-2B against a purchase register. Finds the credit that can be disallowed
before the notice arrives. Offline, zero dependencies.

</td>
<td width="25%" valign="top">

**[docket](https://chirag120670598-dotcom.github.io/docket/)**
<br><sub>`compliance`</sub>

Every deadline that binds a company — dated, priced and sourced. Built after realising
nobody could name their own obligations.

</td>
<td width="25%" valign="top">

**[sprout](https://chirag120670598-dotcom.github.io/sprout/)**
<br><sub>`experiment`</sub>

A program that writes its own evaluation code, remembers its losses, and levels itself
up until it hits a ceiling it publishes.

</td>
<td width="25%" valign="top">

**[steward](https://chirag120670598-dotcom.github.io/steward/)**
<br><sub>`automation`</sub>

Runs every day without being asked. Checks what can be checked, and says plainly what
it cannot.

</td>
</tr>
</table>

<br>

## The rule I build by

> A tool should tell you what it does not know.

Every one of these has a limits section, and it is not decoration. `concord` says its
matching lands at 85–92%, not 100%. `sprout` publishes the generation where it stopped
improving. `steward` prints the list of decisions it is not allowed to make.

A number that flatters itself is worse than no number at all.

<br>

## Smaller things

| | |
|---|---|
| **[threshold](https://github.com/chirag120670598-dotcom/threshold)** | Indian labour-code payroll — statutory wages, PF, ESI, gratuity |
| **[hourglass](https://github.com/chirag120670598-dotcom/hourglass)** | EU CRA Article 14 — the 24-hour clock, tracked |
| **[naam](https://github.com/chirag120670598-dotcom/naam)** | Indian name matching for KYC. Rajesh is not Rakesh. |
| **[gst-patra](https://github.com/chirag120670598-dotcom/gst-patra)** | GST invoices, GSTR-1 JSON, e-way bills |
| **[dukaandaar](https://github.com/chirag120670598-dotcom/dukaandaar)** | WhatsApp orders in Hinglish, with GST and UPI links |
| **[bolcut](https://github.com/chirag120670598-dotcom/bolcut)** | Edit video by editing the transcript |
| **[awaaz](https://github.com/chirag120670598-dotcom/awaaz)** | Hinglish voice pipeline — numbers as Hindi words |
| **[kharcha](https://github.com/chirag120670598-dotcom/kharcha)** | Where your AI spend actually goes |
| **[desi-dev-skills](https://github.com/chirag120670598-dotcom/desi-dev-skills)** | Agent skills for Indian context — UPI, lakh, crore, IST |

<br>

## How these are made

No framework, no build step, no `node_modules`. Standard-library Python, a test suite
that runs in under two minutes, and a site that is one HTML file with its styles inline
so it works with the network switched off.

The tests are the part I care about. `concord` checks its bitboard-free matcher against
a naive implementation on 4,000 random inputs. `sprout` freezes its engine by hash so an
edit cannot be quiet. `steward` is tested on the case where it *cannot* run somebody's
tests, because "I could not check" and "it is broken" are different sentences and
confusing them is how tools become untrustworthy.

<br>

## Reach me

If one of these saved you an afternoon, the UPI below is entirely voluntary — there is
no paid version of anything here, and there never will be.

`chirag120670598-1@oksbi`

<br>

<sub>Ahmedabad, India. Everything here is Apache-2.0 or MIT — take it, fork it, sell
services around it.</sub>
