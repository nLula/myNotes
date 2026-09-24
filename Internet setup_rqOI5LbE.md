---
id: 7a6de4a4-d9b9-4f29-8f2d-b24d48723efe
---
# Internet setup



# Home VPN Setup: Hardware and Software List

Prices checked September 2026. Prices change, so verify before buying.
Setup goal: Flint 2 router with VPN client (Mullvad/Proton) + WireGuard server, two VPN-protected networks, Samsung S25 always tunneled through home.

---

## 1. Hardware

| Item | Purpose | Price | Required? |
|---|---|---|---|
| GL.iNet Flint 2 (GL-MT6000) router | VPN client + WireGuard server, two networks, AdGuard Home built in | about EUR 165 to 172 (GL.iNet EU store); deals seen around EUR 112 | Yes |
| ISP modem / fiber box | Your existing internet connection, Flint 2 plugs into it | EUR 0 (you already have it) | Yes |
| Ethernet cable Cat6, 1 to 2 m | Connects ISP box to Flint 2 WAN port (usually included in the router box) | EUR 0 to 10 (estimate) | Only if the included one is too short |
| Samsung Galaxy S25 | Always-on VPN client | EUR 0 (you already have it) | Yes |

**Hardware one-time total: about EUR 112 to 182**

---

## 2. VPN service (choose one)

| Service | Billing | Price | Notes |
|---|---|---|---|
| **Mullvad** (recommended for privacy) | Flat, per 30 days | EUR 5 / month (EUR 60 / year) | No email needed, anonymous account number, no auto-renewal, price never changes, 5 connections |
| Proton VPN Plus | Monthly | USD 9.99 / month | Includes NetShield ad blocker, 10 devices |
| Proton VPN Plus | 1 year | USD 4.99 / month (about USD 60 / year) | |
| Proton VPN Plus | 2 years | USD 2.99 / month (USD 71.76 total) | Big discounts around Black Friday |

---

## 3. Software on the router

| Software | Purpose | Price |
|---|---|---|
| GL.iNet firmware 4.x (preinstalled) | VPN client, WireGuard server, guest network / VLAN, kill switch, parental control | Free |
| WireGuard (built in) | Tunnel to Mullvad/Proton and tunnel from phone to home | Free |
| AdGuard Home (built in) | Blocks ads, trackers, malware domains for all devices | Free |
| Tailscale (built in) | Only needed if your ISP gives no public IP (CGNAT) | Free personal plan |

---

## 4. Software on the Samsung S25

| App | Purpose | Price |
|---|---|---|
| WireGuard (Google Play) | Tunnel phone to home, set as Always-on VPN with "Block connections without VPN" | Free |
| GL.iNet app (Google Play) | Manage the router, turn second network internet on/off | Free |
| Firefox for Android + uBlock Origin | Blocks in-page and video ads that DNS blocking cannot | Free |
| Tailscale app | Only if you use Tailscale instead of a public IP | Free |

---

## 5. Optional services

| Service | Purpose | Price |
|---|---|---|
| NextDNS Free | Cloud ad/tracker blocking, alternative to AdGuard Home | Free up to 300,000 queries / month |
| NextDNS Pro | Same, unlimited queries | USD 1.99 / month or USD 19.90 / year |
| Public IP from ISP | Lets your phone reach your home router | Depends on ISP: often free, sometimes a small monthly fee. Ask your ISP |

Note: with AdGuard Home on the router you do not need NextDNS.

---

## 6. Cost summary

| | Minimum | Typical |
|---|---|---|
| One-time (router) | EUR 112 | EUR 170 |
| Monthly VPN | about EUR 3 (Proton 2-year) | EUR 5 (Mullvad) |
| Monthly ad blocking | EUR 0 (AdGuard Home) | EUR 0 |
| Public IP | EUR 0 | Check with ISP |
| **First year total** | **about EUR 150** | **about EUR 230** |

---

## 7. Recommended package

- Router: GL.iNet Flint 2
- VPN: Mullvad, WireGuard protocol, server in Finland or Sweden
- Ad blocking: AdGuard Home on the router + uBlock Origin in Firefox
- Phone: WireGuard app, Always-on VPN + Block connections without VPN
- Remote control: GL.iNet app or router panel (192.168.8.1) through the home tunnel

---

## 8. Before you buy: checklist

- [ ] Ask ISP if you have a public IP address (or can get one, and at what price)
- [ ] Check your upload speed: it limits your phone's speed when tunneling through home
- [ ] Confirm ISP box can work with your own router behind it (bridge mode is best, but not required)
