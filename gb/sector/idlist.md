# UK cell sector ID list

This is a list of sectors that UK networks have deployed for 4G and 5G communications varying by band.

## O2 - UK (234 10)

### 4G

> **Note:** Band 1 EARFCN likely to change in the future as O2/VF/3 performs spectrum swap and the carrier is widened to 20MHz.

#### O2 host
* 1x0: Band 20 (EARFCN 6400)
* 1x2: Band 8 (EARFCN 3725)
* 1x4: Band 3 (EARFCN 1226/1228) [Sites with 1228 are micro cells]
* 1x5: Band 1 (EARFCN 199)
* 1x6: Band 40 (EARFCN 39250)
* 1x7: Band 40 (EARFCN 39448)
* 1x8: Band 38 (EARFCN 38100/38125)
* 1x9: Band 28 (EARFCN 9260)

#### Vodafone host
* 1x0: Band 20 (EARFCN 6400)
* 1x2: Band 8 (EARFCN 3725)
* 1x4: Band 1 (EARFCN 199)
* 1x5: Band 40 (EARFCN 39250) [This sector is used if there's B3 in the area usually]
* 1x6: Band 3 (EARFCN 1226) or Band 40 (EARFCN 39250) [This sector is used for B40 if B3 isn't in the area usually]
* 1x7: Band 40 (EARFCN 39448)
* 1x9: Band 38 (EARFCN 38100)

### 5G

> **Note:** This isn't something I've realised until earlier today, but for what seems to be O2 host 5G sectors, O2 actually seems to base them off of the frequency. Example, 10701 is for n28 which is in the 700MHz range. If we ignore the digit at the start and we pretend the digit at the end is a 0, we get 0700 which matches the frequency. Another example, 12101 is for n1 which is 2100MHz, which would become 2100 matching the frequency. I've tried to highlight the frequency more easily for the O2 host ones to show this.

* 510, 520, 530: Band n8 (NRARFCN 190590) [Likely Vodafone host only]
* 515, 525, 535: Band n28 (NRARFCN 152690) [Seems to be a Vodafone host sector ID but not sure]
* 1**0701**, 10702, 10703: Band n28 (NRARFCN 152690)
* 1**0901**, 10902, 10903: Band n8 (NRARFCN 189850)
* 1**2101**, 12102, 12103: Band n1 (NRARFCN 426010)
* 1**2601**, 12602, 12603: Band n38 (NRARFCN 517230)
* 1**3401**, 13402, 13403: Band n78 (NRARFCN 634080)
* 1**3701**, 13702, 13703: Band n78 (NRARFCN 648768/651360)

## vodafone UK (234 15)

### 4G

> **Note:** Band 38 is going to be withdrawn soon with spectrum transferring over to O2. Band 1 EARFCN is likely to change soon with the VF/O2/3 spectrum swap and will be widened to 20MHz. I suspect band 3 should use EARFCN 1363 shortly too.

#### Vodafone host
* x0: Band 20 (EARFCN 6300)
* x2: Band 8 (EARFCN 3501)
* x4: Band 1 (EARFCN 299/323/347)
* x6: Band 3 (EARFCN 1288/1363)
* x8: Band 7 (EARFCN 2850)
* x9: Band 38 (EARFCN 37900)

#### O2 host
* x0: Band 20 (EARFCN 6300)
* x2: Band 8 (EARFCN 3501)
* x4: Band 3 (EARFCN 1288)
* x5: Band 1 (EARFCN 299/323/347)
* x8: Band 7 (EARFCN 2850)

> **Note:** Three sites are the same as what's being broadcast on 3 UK at the moment.

### 5G

* 15, 25, 35: Band n78 (NRARFCN 628032)
* 17, 27, 37: Band n1 (NRARFCN 428190)
* 410, 420, 430: Band n8 (NRARFCN 186030)
* 416, 426, 436: Band n78 (NRARFCN 634080)
* 419, 429, 439: Band n78 (NRARFCN 634080)

## 3 UK (234 20)

### 4G
* 0, 1, 2: Band 3 (EARFCN 1363/1392)
* 6, 7, 8: Band 20 (EARFCN 6175)
* 10-43: Band 3 (EARFCN 1363) [DAS systems only, unconfirmed max sector ID]
* 71, 72, 73: Band 1 (EARFCN 76/99)
* 91, 92, 93: Band 28 (EARFCN 9360)
* 110-143: Band 1 (EARFCN 76/99) [DAS systems only, unconfirmed max sector ID]

Also B20/28 DAS cells in the 200 range but I can't confirm anything yet.

### 5G
* 101, 102, 103: Band n78 (NRARFCN 641376)
* 201, 202, 203: Band n78 (NRARFCN 631392)
* 301, 302, 303: Band n1 (NRARFCN 424130)

## EE (234 30), including ESN (234 32)

### 4G
* 0, 1, 2: Band 3 (EARFCN 1617)
* 3, 4, 5: Band 3 (EARFCN 1761/1815)
* 6, 7, 8: Band 7 (EARFCN 3350)
* 9, 10, 11: Band 7 (EARFCN 3179)
* 12, 13, 14: Band 20 (EARFCN 6225)
* 15, 16, 17: Band 7 (EARFCN 3026) [Micro cells only]
* 18, 19, 20: Band 1 (EARFCN 497)
* 24, 25, 26: Band 3 (EARFCN 1791) [Micro cells only]
* 27, 28, 29: Band 28 (EARFCN 9460) [Very rare: seen in Edinburgh and rural areas]
* 30, 31, 32: Band 7 (EARFCN 3029)

### 5G
* 0, 1, 2: Band n78 (NRARFCN 636768/636960)
* 3, 4, 5: Band n78 (NRARFCN 646080/646272)
* 6, 7, 8: Band n28 (NRARFCN 156510)
* 9, 10, 11: Band n1 (NRARFCN 431810)
* 12, 13, 14: Band n3 (NRARFCN 372490)
* 15, 16, 17: Band n7 (NRARFCN 529490)
