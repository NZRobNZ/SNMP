# Fuji Xerox DocuCentre SC2020

The following OIDs work for pulling stats out of our SC2020, we use Zabbix for the capture.

## Consumables

**Cyan**
```
sc2020_cyan_cap         1.3.6.1.2.1.43.11.1.1.8.1.1
sc2020_cyan_lvl         1.3.6.1.2.1.43.11.1.1.9.1.1
sc2020_cyan_remain_pct	(last(sc2020_cyan_lvl)/last(sc2020_cyan_cap))*100
```
**Magenta**
```
sc2020_magenta_cap        1.3.6.1.2.1.43.11.1.1.8.1.2
sc2020_magenta_lvl        1.3.6.1.2.1.43.11.1.1.9.1.2
sc2020_magenta_remain_pct (last(sc2020_magenta_lvl)/last(sc2020_magenta_cap))*100
```

**Yellow**
```
sc2020_yellow_cap           1.3.6.1.2.1.43.11.1.1.8.1.3
sc2020_yellow_lvl           1.3.6.1.2.1.43.11.1.1.9.1.3
sc2020_yellow_remain_pct    (last(sc2020_yellow_lvl)/last(sc2020_yellow_cap))*100
```

**Black**
```
sc2020_black_cap           1.3.6.1.2.1.43.11.1.1.8.1.4
sc2020_black_lvl           1.3.6.1.2.1.43.11.1.1.9.1.4
sc2020_black_remain_pct    (last(sc2020_black_lvl)/last(sc2020_black_cap))*100
```

**Drum Cartridge [R1]**
```
sc2020_drum_r1_cap           1.3.6.1.2.1.43.11.1.1.8.1.9
sc2020_drum_r1_lvl           1.3.6.1.2.1.43.11.1.1.9.1.9
sc2020_drum_r1_remain_pct    (last(sc2020_drum_r1_lvl)/last(sc2020_drum_r1_cap))*100
```

**Drum Cartridge [R2]**
```
sc2020_drum_r2_cap           1.3.6.1.2.1.43.11.1.1.8.1.6
sc2020_drum_r2_lvl           1.3.6.1.2.1.43.11.1.1.9.1.6
sc2020_drum_r2_remain_pct    (last(sc2020_drum_r2_lvl)/last(sc2020_drum_r2_cap))*100
```

**Drum Cartridge [R3]**
```
sc2020_drum_r3_cap           1.3.6.1.2.1.43.11.1.1.8.1.7
sc2020_drum_r3_lvl           1.3.6.1.2.1.43.11.1.1.9.1.7
sc2020_drum_r3_remain_pct    (last(sc2020_drum_r3_lvl)/last(sc2020_drum_r3_cap))*100
```

**Drum Cartridge [R4]**
```
sc2020_drum_r4_cap           1.3.6.1.2.1.43.11.1.1.8.1.8
sc2020_drum_r4_lvl           1.3.6.1.2.1.43.11.1.1.9.1.8
sc2020_drum_r4_remain_pct    (last(sc2020_drum_r4_lvl)/last(sc2020_drum_r4_cap))*100
```

**Waste Toner Container [R5]**
```
sc2020_waste_r5_cap           1.3.6.1.2.1.43.11.1.1.8.1.6
sc2020_waste_r5_lvl           1.3.6.1.2.1.43.11.1.1.9.1.6
sc2020_waste_r5_remain_pct    (last(sc2020_waste_r5_lvl)/last(sc2020_waste_r5_cap))*100
```

## Page Counts

**Page Count: Black**
```
sc2020_pages_bw    1.3.6.1.4.1.253.8.53.13.2.1.6.1.20.34
```

**Page Count: Colour**
```
sc2020_pages_col   1.3.6.1.4.1.253.8.53.13.2.1.6.1.20.33
```

**Page Count: Total**
```
sc2020_pages_tot    1.3.6.1.2.1.43.10.2.1.4.1.1
```

## Status

**Status 01**
```
sc2020_status01    1.3.6.1.2.1.43.18.1.1.8.1.1
```

**Status 02**
```
sc2020_status02    1.3.6.1.2.1.43.18.1.1.8.1.2
```

**Status 03**
```
sc2020_status03    1.3.6.1.2.1.43.18.1.1.8.1.3
```

**Status 04**
```
sc2020_status04    1.3.6.1.2.1.43.18.1.1.8.1.4
```

