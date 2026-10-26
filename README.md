# BRIGHT TECH — electrical & it installation

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `brighttechservices.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/brighttechservices.mjs`).
> To change the content, edit that file and run `node build.mjs brighttechservices` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@brighttechservices.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Bright Tech Services, an electrical and IT installation company based in Tervuren, Flemish Brabant. We carry out general electrotechnical installation, install network and data cabling, and supply, install and commission IT and communications equipment for homes, offices and small businesses. One rule governs all of it and we would rather state it than let a client find out later: in Belgium a new or substantially modified electrical installation must be inspected by an approved inspection body and declared compliant with the General Regulation on Electrical Installations before it is put into service. We arrange that inspection and hand over the report, and we will not commission an installation that has not passed it. We do not carry out gas work and we do not touch asbestos. Site: brighttechservices.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
