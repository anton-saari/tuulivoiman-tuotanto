# Tuulivoiman Tuotannon Estimointi

Projekti estimoi Suomen tuulivoimaloiden tuotantoa ECMWF ERA5 reanalyysi-datan perusteella.

## Kuvaus

Tämä notebook käyttää:
- **ECMWF ERA5** säädataa (tuuli, lämpötila, paine)
- **windpowerlib**-kirjastoa tuotannon mallintamiseen
- **Fingrid**:n todellisia tuotantolukuja vertailuun

## Aineisto

- 100m tuulen komponentit
- 2m lämpötila ja ilmanpaine
- 3 mittauspistettä: Kalajoki, Närpiö, Simo

## Käyttö

```bash
jupyter notebook src.ipynb
```

## Vaatimukset

```
pandas
numpy
xarray
cdsapi
matplotlib
windpowerlib
scikit-learn
```

## Tekijä

Anton S.
