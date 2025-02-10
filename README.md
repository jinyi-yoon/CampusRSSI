# CampusRSSI

_RSSIndoor_ dataset is the real-world RSSI measurements for indoor localization.

## Methodology
We deploy the wireless APs of EFM-Networks ipTIME N104Q-i with a single antenna of dBi. It communicates using IEEE 802.11n of 150 Mbpm over 2.4GHz band. To collect the fine-grained data for every $30cm$, we installed tiles with the size of $0.3\times0.3m^2$ on the floor except for AP 12 and 14 in Medium-Obs (Office). We collect the data using our own Android application for RSSI data collection on 26 LG G Pad 3 10.1 (LG-X760) equipped with wi-fi. We keep the position of the devices at the left bottom of the tile. We do not constrain any pedestrians to make the situation realistic.

## Places

We collect the data in four different in-building places.
- Free-Obs (Hall): 10 APs over $9.6\times9.9~m^2$, where there is a single round pillar
- Low-Obs (Lounge): 11 APs over $6.6\times9.9~m^2$, where the area is partitioned by the waist-high wooden wall
- Medium-Obs (Office): 16 APs over $9.9\times~9.9m^2$, where the room with AP 6 and 15 is enclosed by concrete walls, glass walls enclose other rooms, and the black-colored boxes are the concrete pillars
- High-Obs (Office): 10 APs over $10.8\times12.0m^2$, where the concrete wall at $x=8.4~m$ divides the hall where the AP 9 is located and glass walls enclose the room area, and all rooms

### Floor Plan

The exact AP locations for each place can be found in the 'ap_loc.csv' files.
<img width="1082" alt="Image" src="https://github.com/user-attachments/assets/a3ad829b-d137-4066-a49f-f3037b2634bd" />

### RSSI Heatmap

<img width="1082" alt="Image" src="https://github.com/user-attachments/assets/72858805-46fb-482b-8cb9-c1f72b6c186b" />

## Citation

If you find CampusRSSI dataset useful for your research and applications, please cite using this BibTeX:
```bibtex
@inproceedings{yoon2024ganloc,
  title={GAN-Loc: Empowering Indoor Localization for Unknown Areas via Generative Fingerprint Map},
  author={Yoon, JinYi and You, Yeawon and Kang, Dayeon and Kim, Jeewoon and Lee, HyungJune},
  booktitle={2024 21st Annual IEEE International Conference on Sensing, Communication, and Networking (SECON)},
  pages={282--290},
  year={2024},
  organization={IEEE}
}

@inproceedings{you2025collagemap,
  title={CollageMap: Tailoring Generative Fingerprint Map via Obstacle-Aware Adaptation for Site-Survey-Free Indoor Localization},
  author={You, Yeawon and Yoon, JinYi and Kang, Dayeon and Kim, Jeewoon and Lee, HyungJune},
  booktitle={2025 IEEE International Conference on Pervasive Computing and Communications (PerCom)},
  year={2025},
  organization={IEEE}
}
```
