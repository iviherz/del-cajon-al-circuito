# Del cajón al circuito

_try it out for yourself (in spanish): https://iviherz.github.io/del-cajon-al-circuito/_

**Interactive decision tool for responsible e-waste choices: repair, give a device a second life, or use a verified e-waste channel.**

Developed by **Ivana Herz** as an individual project within **Challenge ODS 2026 – Goethe-Institut Buenos Aires**, linked to **SDG 12: Responsible Consumption and Production**.

> **Live site:** once GitHub Pages is enabled, this repository will publish the tool as a regular web page.

---

## What problem does it address?

During an exploratory survey conducted for the project with **50+ students**, a recurring pattern appeared: many unused phones, chargers, cables and other devices remain stored “just in case” instead of reaching a repair, reuse or recycling route.

The survey also identified practical barriers such as:

- repair cost or lack of trusted repair options;
- uncertainty about what to do with a device that still works;
- concern about photos, passwords and personal data;
- very low reported use of specialised recycling channels.

The survey is **project-specific and exploratory**. It is not presented as statistically representative of all students in Buenos Aires.

## The microsolution

**Del cajón al circuito** combines:

1. a short educational intervention on SDG 12 and electronic waste;
2. an interactive decision tool — **¿Reparo, dono o reciclo?** — that helps users organise their options;
3. a practical decision-making activity in which participants apply the tool to a real device they have at home.

The tool does **not** diagnose hardware, guarantee that repair is worthwhile, certify data erasure or replace manufacturer guidance. It is designed to reduce one concrete barrier: **not knowing what the next responsible step could be**.

## Decision paths

The tool can guide a user toward one of five outcomes:

- **Keep using it** when the device works and still has a concrete use.
- **Explore repair** when a fault may be recoverable.
- **Explore a second life** when the device works but is no longer needed.
- **Use a verified e-waste channel** when reuse is not viable.
- **Stop and consult** when there are signs of battery or device damage.

Where personal data may be involved, the tool redirects users to official manufacturer instructions rather than providing a universal “secure erase” recipe.

## Verification standard

Practical claims in the tool are based primarily on:

- official **Buenos Aires City Government** information for local e-waste routes;
- official **Apple, Google and Microsoft** support documentation for device preparation and reset procedures;
- **United Nations** sources for SDG 12;
- primary institutional sources for the Argentine and German initiatives used as inspiration.

See [`fuentes.md`](./fuentes.md) for the source register and scope of each reference.

**Last content verification:** 25 September 2026.

## Privacy

This site is intentionally static:

- no account is required;
- no analytics are included;
- no answers are sent to a server;
- no database stores users' decisions.

Impact measurement for the workshop is kept separate from the decision tool.

## Run locally

No build process is required.

1. Download the repository.
2. Open `index.html` in a modern browser.

## Publish with GitHub Pages

1. Upload `index.html`, `README.md` and `fuentes.md` to the repository root.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**.
4. Select **main** and **/ (root)**.
5. Save.

GitHub Pages will publish the tool as a normal website, typically at:

`https://<username>.github.io/del-cajon-al-circuito/`

## Project status

**September 2026:** functional prototype prepared for a school pilot in Buenos Aires.

After implementation, this repository can be updated with the final workshop methodology and aggregate results.

---

### Important note

This is an independent educational tool developed by Ivana Herz. It is **not an official product of, nor technically endorsed by**, Goethe-Institut, Universidad de Buenos Aires, Gobierno de la Ciudad de Buenos Aires, Apple, Google, Microsoft or Deutsche Umwelthilfe.
