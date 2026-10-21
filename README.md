# Bed and mattress sizes: US, UK and France

Mattress dimensions for three markets in one place, in inches and centimetres, with the published source for each row. The same names mean different sizes from country to country: a UK King (150 x 200 cm) is narrower than a US Queen (152.4 x 203.2 cm), and a French "queen size" is 160 x 200 cm.

Files:

- `us.csv`: Twin to California King. Where US sources disagree, both figures are kept (`alt_*` columns) instead of averaging them.
- `uk.csv`: Small Single to Emperor, with the imperial name, the metric label shops use, the exact imperial conversion and whether the National Bed Federation lists it as a standard UK size.
- `fr.csv`: French sizes from 1 place to king size.
- `sizes.json`: all three tables in one file.

## US

| Size | Inches | Centimetres |
|---|---|---|
| Twin | 39 x 75 (Sleep Foundation: 38 x 75) | 99.1 x 190.5 |
| Twin XL | 39 x 80 (Sleep Foundation: 38 x 80) | 99.1 x 203.2 |
| Full | 54 x 75 (Sleep Foundation twin guide: 54 x 74) | 137.2 x 190.5 |
| Queen | 60 x 80 | 152.4 x 203.2 |
| King | 76 x 80 | 193 x 203.2 |
| California King | 72 x 84 | 182.9 x 213.4 |

## UK

| Size | Imperial | Centimetres | NBF standard |
|---|---|---|---|
| Small Single | 2ft 6in x 6ft 3in | 75 x 190 | yes |
| Single | 3ft x 6ft 3in | 90 x 190 | yes |
| Euro Single | 3ft x 6ft 6in | 90 x 200 | no |
| Small Double | 4ft x 6ft 3in | 120 x 190 | yes |
| Double | 4ft 6in x 6ft 3in | 135 x 190 | yes |
| Euro Double | 4ft 7in x 6ft 6in | 140 x 200 | no |
| King | 5ft x 6ft 6in | 150 x 200 | yes |
| Euro King | 5ft 3in x 6ft 6in | 160 x 200 | no |
| Super King | 6ft x 6ft 6in | 180 x 200 | yes |
| Emperor | 6ft 6in x 6ft 6in | 200 x 200 | no |

The metric label is rounded. 6ft 3in is really 190.5 cm and 6ft 6in is 198.1 cm, so a "200 cm" UK King is 1.9 cm longer than its imperial name.

## France

| Size | Centimetres |
|---|---|
| 1 place | 90 x 190 or 90 x 200 |
| 2 places | 140 x 190 or 140 x 200 |
| Queen size | 160 x 200 |
| King size | 180 x 200 |

## Sources

All figures were checked on 24 September 2026.

- Target mattress size chart: https://digitalcontent.target.com/itemcontent/sizecharts/htmlfragments/mattress/all-mattress/mattress.html
- Sleep Foundation twin guide: https://www.sleepfoundation.org/mattress-sizes/twin-size-bed-dimensions
- Sleep Foundation double bed guide: https://www.sleepfoundation.org/mattress-sizes/what-is-a-double-bed
- Which? UK mattress size guide: https://www.which.co.uk/reviews/mattresses/article/uk-mattress-sizes-bed-mattress-size-guide-aDx4r9b4T99o
- National Bed Federation buyer's guide: https://bedadvice.co.uk/bed-buyers-guide/2-shopping-for-a-new-bed/
- IKEA France mattress size guide: https://www.ikea.com/fr/fr/rooms/bedroom/how-to/tailles-de-matelas-pub455f28b0/

The tables come from [Bed Size Chart](https://bedsizechart.com/), where the full dataset, the source disagreements and the room-size checks are kept up to date. If a figure here goes stale, the site has the current one.

## Licence

CC BY 4.0. Reuse the data with a credit to bedsizechart.com.
