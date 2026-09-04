# thetatau-chichapter.github.io

This website serves as the main website for Theta Tau Chi Chapter at the University of Arizona. The website is currently visible at thetatauchi.org

## Maintainers
Paloma Ortiz (pcortiz@arizona.edu) is the lead maintainer of the website. Any questions regarding the content or format of the website should be directed towards her.

Logan Pageler (pagelerlogan@gmail.com) maintains ownership of the domain. Any issues with the domain should be sent to her.

Frank Ventura (venturafranklin@gmail.com) is the manager of the Theta Tau Tucson alumni association. If unable to contact Logan or Paloma please reach out to him.

## Deploying

The website is served at the root of this repo on the main branch. To deploy a new version of the website simply push to main.

## Structure

The website uses basic JavaScript, HTML, and CCS for its design. We also include the [bootstraps library](https://getbootstrap.com/) for easy component usage.

## Domain

The domain is managed by Cloud Flare.
To register a domain with github pages first you must create 4 A name records:
| Type | Name |   IPv4 address  | Proxy Status |
| ---- | ---- | --------------- | ------------ |
|  A   |   @  | 185.199.108.153 |   DNS only   |
|  A   |   @  | 185.199.109.153 |   DNS only   |
|  A   |   @  | 185.199.110.153 |   DNS only   |
|  A   |   @  | 185.199.111.153 |   DNS only   |

Then you must update the github settings with the new domain at:

`Settings` > `Pages` > `Custom Domain`

After typing in the new domain press `Save`. If you have an issue with saving note that it can take a day for the records to update and you may need to wait.


