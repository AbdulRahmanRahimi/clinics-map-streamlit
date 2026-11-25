# Clinics Map (Python + Streamlit)

An interactive map of health clinics in Afghanistan, built in Python with Streamlit and Folium. It is the Python version of the [Afghanistan Clinics Dashboard](https://github.com/rahimiabdulrahmanab/afghanistan-clinics-dashboard), which also loads its clinic data from this repository.

## Features

- Folium web map with custom clinic and hospital markers and labels
- Filter clinics by province
- Search by facility name
- Optional view of the distances between clinics
- Clinic data loaded from CSV with pandas

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

The repository also includes a dev container, so it opens ready to run in GitHub Codespaces.

## Files

| File | Purpose |
|---|---|
| `app.py` | Streamlit app |
| `app.ipynb` | Notebook used for data exploration |
| `Afghanistan Clinics.csv`, `Clinics.csv`, `Clinics.xlsx` | Clinic datasets |
| `*.png`, `*.webp` | Map markers, logo and images |

---

Built by **Abdul Rahman Rahimi**, Software Developer & Geospatial Analyst, [Rahimi Tech Solution](https://github.com/rahimiabdulrahmanab).
