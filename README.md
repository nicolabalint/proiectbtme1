# Proiect BTME1 – Bistabil D_v1 și Numărător asincron pe 12 stări

## Descriere
Acest repository conține proiectarea completă (schematic, layout, simulare și extracție) a unui **bistabil D (D_v1)** realizat cu porți **NAND2**, precum și implementarea unui **numărător binar asincron cu 12 stări**.

Proiectul a fost realizat folosind **Cadence Virtuoso** și include:
- proiectarea tranzistoarelor NMOS/PMOS
- realizarea porții NAND2
- realizarea bistabilului D
- realizarea numărătorului asincron
- simulări pre-layout și post-layout (AV extracted)
- verificări DRC și LVS

---

## Structura repository-ului

## Structura repository-ului

```text
├── dv1proiect
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   ├── schematic_STERS
│   └── symbol
├── dv1proiecttest
│   └── schematic
├── layout_nmos
│   ├── av_extracted
│   ├── layout
│   └── schematic
├── layout_pmos
│   ├── av_extracted
│   ├── layout
│   └── schematic
├── n
│   └── schematic
├── nand2proiect
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── nand2proiecttest
│   └── schematic
├── nmos_lay
│   └── schematic
├── numarator12st
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── numarator12sttest
│   └── schematic
├── p
│   └── schematic
├── tema4_nand2
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── tema4_nand2_test
│   └── schematic
├── tema5
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── tema5_test
│   └── schematic
├── tema_inv
│   ├── av_extracted
│   ├── layout
│   ├── schematic
│   └── symbol
├── tema_inv_test
│   └── schematic
└── TG
    ├── schematic
    └── symbol
```

---

## Tehnologii și unelte folosite
- Cadence Virtuoso
- Spectre (simulare)
- DRC / LVS
- AV Extracted (post-layout)
- Tehnologie CMOS (NMOS + PMOS)

---

## Conținut tehnic
- **Invertor CMOS**
- **Poartă NAND2**
- **Bistabil D (D_v1)** realizat din porți NAND
- **Numărător asincron cu 12 stări**
- Simulări tranzitorii (clock, reset, ieșiri)
- Compararea simulărilor schematic vs. post-layout

---

## Cum se rulează simulările
1. Deschide librăria în **Cadence Virtuoso**
2. Accesează directorul `*_test`
3. Rulează simulările tranzitorii (Spectre)
4. Pentru post-layout, folosește netlist-ul din `av_extracted`
5. Compară formele de undă pre/post-layout

---

## Rezultate
- funcționare corectă a bistabilului D
- secvență corectă de 12 stări pentru numărător
- DRC și LVS fără erori
- diferențe minore între pre-layout și post-layout datorate parasiticelor

---

## Documentație
Documentația completă (scheme, layout-uri, forme de undă) se găsește în PDF-ul proiectului.
