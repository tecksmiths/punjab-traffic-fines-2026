# Punjab traffic fines and penalty points 2026 (open dataset)

Machine-readable copy of **Punjab's official schedule of traffic fines and penalty points**: every offence, its fine for each of the 7 vehicle classes, and the points it adds to a driving licence.

- **Law:** Provincial Motor Vehicles Ordinance 1965, Twelfth Schedule, as substituted by the Provincial Motor Vehicles (Second Amendment) Act 2026 (Act XXVI of 2026), Punjab Gazette (Extraordinary), 7 May 2026
- **Source:** consolidated text on the [Punjab Code](https://punjablaws.punjab.gov.pk/en/show_article/UWRdaQo7ATU-) (Law & Parliamentary Affairs Department, Government of the Punjab)
- **Last checked against the source:** 9 November 2026
- **Currency:** Pakistani rupees (PKR)

## Files

| File | Format | Contents |
| --- | --- | --- |
| [`data/punjab-traffic-fines-2026.csv`](data/punjab-traffic-fines-2026.csv) | CSV | 26 offences × 7 vehicle classes + points |
| [`data/punjab-traffic-fines-2026.json`](data/punjab-traffic-fines-2026.json) | JSON | Same data, with source and vehicle-class metadata |

An empty cell (CSV) or `null` (JSON) means the offence does not apply to that vehicle class.

## Vehicle classes

| Column | Vehicle class |
| --- | --- |
| `motorcycle_rs` | Motorcycle |
| `three_wheeler_rs` | Three-wheeler / rickshaw |
| `car_jeep_upto_2000cc_rs` | Car / jeep up to 2000cc |
| `car_jeep_above_2000cc_rs` | Car / jeep above 2000cc |
| `motor_cab_delivery_van_rs` | Motor cab / delivery van |
| `ltv_psv_rs` | Light transport / public service vehicle |
| `htv_tractor_trailer_rs` | Heavy transport vehicle / tractor-trailer |

## Sample

| Offence | Motorcycle | Car ≤2000cc | Car >2000cc | Points |
| --- | --- | --- | --- | --- |
| Exceeding the speed limit | 2,000 | 5,000 | 10,000 | 4 |
| Signal violation | 2,000 | 3,000 | 5,000 | 3 |
| Hand-held mobile phone while driving | 1,000 | 3,000 | 3,000 | 3 |
| Riding without a crash helmet | 2,000 | – | – | 2 |
| Seat belt not fastened | – | 2,000 | 3,000 | 2 |
| Parking violation | 2,000 | 3,000 | 3,000 | 1 |

## How the points work (section 116-A)

1. Points are charged **in addition to** the fine.
2. More than **20 points within one year** → the licence is disqualified for **6 months**, extendable by another 6 months.
3. The same offence repeated within one month → fine increases by **5%** of the previous fine for each repeat.
4. A fine not paid in time → complaint before the court; if found guilty at trial, the fine is **doubled**.

## Important notes

- The **Punjab Traffic Police website** still lists an older, higher schedule with no points column (for example, over-speeding for a car above 2000cc: Rs 20,000 there, Rs 10,000 in the law). This dataset follows the law.
- The amount shown on a driver's own e-challan is what is payable.
- This dataset is independent and unofficial. It is not affiliated with the Government of the Punjab, PSCA or the Punjab Traffic Police. Check the source before relying on it for anything formal.

## Use it

- **Calculator:** add up fines and points for your own challans with the free [Punjab challan fine & points calculator](https://checkechallan.pk/punjab-challan-fine-calculator/).
- **Explained in plain English:** [Traffic fines in Pakistan 2026](https://checkechallan.pk/traffic-fines-pakistan-2026/) and [Punjab driving licence penalty points](https://checkechallan.pk/punjab-driving-license-penalty-points-system/).

Corrections are welcome: open an issue with the offence, the vehicle class and a reference to the source.

## License

The underlying law is public. This compilation is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse freely with attribution to "checkechallan.pk".

Maintained by [checkechallan.pk](https://checkechallan.pk/), an independent guide to e-challans, traffic fines and driving-licence rules in Pakistan.
