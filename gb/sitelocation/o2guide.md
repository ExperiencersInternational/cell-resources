# Locate O2 2G/3G/4G/5G sites using the My Network application

Unlike the other 3 networks, O2 publicly publishes where sites are located in the UK (although this is also the case for Germany too and how we initially found it) and you're actually even able to search specific cell IDs too which allows you to find out where a specific cell is located.

## Searching by site ID

First of all, you can literally just search by the site ID if you know it. For example, searching 514421 will take you to an O2 site off the A40 in Monmouth.

![Shows a search box which had just searched 514421 in My Network and was positioned in an area by the A40 in Monmouth](https://experiencersinternational.github.io/cell-resources/img/gb/sitelocation/o2guide/Screenshot_20241126-233039.png)

## Searching by cell ID (2G and 3G)

If you don't know the site ID, you can search by the cell ID. For 2G and 3G, this should be a 5 digit decimal number (including the sector ID). For our test site in particular, this would be 12601 for 2G on the first sector.

> **Note:** If you're searching for a site that doesn't have a 5 digit decimal number here, put as many 0's as necessary at the start to make it 5 digits. For example, in the step below for cell ID 6573 in Blaenporth in Wales, you would input `cell:06573`.

We can then search this on the app or website by inputting `cell:xxxxx` (replacing xxxxx with the cell ID).

You should see a list of site IDs when you've done that and with trial and error, you should be able to find the correct site.

![Shows a list of site IDs that correspond with that cell ID, for example cell:12601 gave us 034590, 034807, 035783, 514421](https://experiencersinternational.github.io/cell-resources/img/gb/sitelocation/o2guide/Screenshot_20241126-233235.png)

Generally, 5xxxxx site IDs are ones in Vodafone host areas (which is essentially majority of the West of England, majority of Wales and parts of Western Scotland). Anything that doesn't start with 5xxxxx means that it's an O2 host area (Northern Ireland, large parts of Scotland and East of England).

## Searching by cell ID (4G and 5G)

Like 2G and 3G, we can also search by the cell ID for 4G and 5G. However this works slightly differently.

We still utilise the cell ID (unfortunately we don't utilise the eNB/gNB number here), but instead we have to format this differently. We have to input our cell ID in hexadecimal due to the way O2 handles this.

> Note: Make sure to capitalise the letters in cell ID when searching, else it won't find anything.

For example, cell ID 747630 (or eNB 2920 on the 110 sector), would correspond to B686E in hexadecimal. We would then input this into the My Network app or website as `cell:B686E`.
