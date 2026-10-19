# AI-SECRETT Consortium Map

An interactive map of the AI-SECRETT consortium, adapted from the AISHA and AI4Gov-X consortium maps. Open `index.html` through a web server to use the map. The page includes partner search, beneficiary and associated-partner filters, country details, and a partner directory.

**Live map:** https://fracastiglione.github.io/AI-SECRETT-Consortium-Map/

## Source and scope

- The supplied **AI-SECRETT Partners List.docx** provides the numbered partners, their names, acronyms, roles, and beneficiary countries. PICs and street addresses are deliberately omitted from the public map.
- The list names **22 beneficiaries**, including coordinator **UVEG**, and **one associated partner**, **Relais Europe (RE)**.
- The associated partner's country is not specified in the supplied list. It is shown in **France** based on [Relais Culture Europe's own AI-SECRETT announcement](https://www.relais-culture-europe.eu/ressources/lancement-officiel-du-projet-ai-secret) and its [France office information](https://www.relais-culture-europe.eu/). The map uses the document's name “Relais Europe” and shows “Relais Culture Europe” as an alias.
- The map covers **12 countries**, with each organization counted once in its country. The [AI-SECRETT partner directory](https://aisecrett.eu/partners/) offers a public project reference.
- The AI-SECRETT logo was supplied by the project owner. Its violet colors guide the map and interface.

## Technical notes

This is a static website with no build step. It uses Leaflet from a CDN, local country geometry, and Esri map tiles with OpenStreetMap tiles as a fallback. Country highlighting and partner data are stored locally; the background and Leaflet library need an internet connection.
