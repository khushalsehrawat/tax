# tax
Designing a website that allows for tax calculation based on a users input.

This code is a simple tax calculator web application.

Describing what in the code:
1. The user enters their Gross Annual Income, Extra Income, and Deductions in the form fields. They also select their age range from a dropdown menu.
2. The code checks if the user has entered valid numbers in the input fields and if they have selected an age range. If there are any errors, it displays an error icon next to the corresponding field.
3. If the inputs are valid, the code calculates the overall income by adding the Gross Annual Income and Extra Income, and then subtracting the Deductions.
4. Based on the user's age range, the code applies a different tax rate to the taxable income (the amount over 8 lakhs). The tax rates are 30% for age under 40, 40% for age 40 to 60, and 10% for age 60 and above.
5. The calculated tax amount is then displayed in a modal window.

The code also includes some CSS styles and Bootstrap libraries to make the form and modal look better. Overall, it's a simple tax calculation tool that helps users understand how much tax they might need to pay based on their income and age.


## Website metadata

This repository is a plain HTML/CSS/JavaScript calculator demo using the rules implemented in `index.html`. The metadata describes those built-in rules without claiming that they match current tax law. The existing title, form, validation, calculations and result modal are preserved.

The page includes a description, TheBenzzCreations author/creator metadata, Open Graph metadata, Twitter card metadata and one WebApplication JSON-LD block identifying the developer. One visible developer credit appears in a footer with a normal same-tab hyperlink for the developer link.

Production identity is recorded in `seo-sites.json`; see Canonical URL validation below. The developer credit is not evidence of a project deployment URL.

Serve this directory with a static web server to preview the page. External libraries and fonts require an internet connection. No package manifest, configured lint suite or build command is present.

## Development & Maintenance

**Developed & Maintained by
[Khushal Sehrawat](https://github.com/khushalsehrawat)**
— Founder of
[TheBenzzCreations](https://www.thebenzzcreations.com/).

TheBenzzCreations is a digital development studio specializing in website development, custom software, mobile applications, e-commerce solutions and AI-powered business automation.

For development enquiries and collaborations, visit [TheBenzzCreations](https://www.thebenzzcreations.com/).

## Canonical URL validation

Run `python scripts/validate_seo.py` from this repository before publishing. The dependency-free check validates exact page canonicals, Open Graph URLs, website/application JSON-LD URLs, sitemap locations, robots sitemap references and literal framework site metadata against `seo-sites.json`. It checks deployment path prefixes as well as domains, so one GitHub Pages project cannot canonicalize to another.

Only URLs whose live HTML matched the local page on 2026-11-21 are configured. Unverified pages have no canonical or social URL; `python scripts/validate_seo.py --require-verified` also fails for those pending pages. Reverify the configuration if the deployment moves. Dynamic framework expressions still require runtime validation.

TheBenzzCreations attribution, creator organization URLs and existing normal same-tab developer credit links are preserved. These outbound attribution links are separate from site identity.
