On blokker.nl, roughly 500,000 unique products are being sold. The vast majority (98-99%) of these products are pushed by our external sellers. Unfortunately, the categorization for these products is not always correct. In this notebook, we are recategorizing the best selling products from our external sellers with the help of AI. We are using ChatGPT with the gpt-4o model. The idea is to use a recursive API call, where each time a list of (sub)categories are sent to the ChatGPT API in combination with product name and product description.

Our first category level (L1) contains the categories below:
- Speelgoed
- Dieren
- Wonen
- Reizen
- Eten & tafelen
- Persoonlijke verzorging
- Schoonmaak & huishoud
- Elektronica
- Koken & bakken
- Tuin
- Baden & slapen
- Wassen & strijken
- Vrije tijd
- Baby
- Boeken & kantoorartikelen
