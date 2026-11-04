# Paulenco — paulenco srl

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `paulenco.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/paulenco.mjs`).
> To change the content, edit that file and run `node build.mjs paulenco` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@paulenco.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Own account / $On time / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Paulenco, a holding company based in Knokke-Heist in West Flanders, formed in 2018. A holding company does very little visibly, which is exactly why the filing obligations deserve stating rather than assuming. There is a widespread belief that a company with no trading activity has nothing to do, and it is wrong in every particular. Annual accounts must still be approved by the general meeting within six months of the financial year end and filed with the National Bank within thirty days of approval, and in any event within seven months of year end. Late filing attracts surcharges that grow with the delay. More seriously, damage suffered by third parties is presumed to result from a failure to file, which reverses the burden of proof in any dispute. And a company that has not filed for three consecutive financial years can be judicially dissolved on the application of any interested party or the public prosecutor. On top of that the beneficial ownership entry has to be confirmed annually and the yearly company contribution still falls due. A dormant company is not an exempt company, it is simply a company nobody is watching. Site: paulenco.shop
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
