# Mateus Zunino Espindola

Agronomist in training at the Federal University of Santa Catarina (UFSC), Brazil.
I work on **agrometeorology and plant disease decision support**: weather-driven models
for crop protection, tested against simulation, held-out years and field sensor data.

## Featured work

**[vitirule](https://github.com/mateuszunino/vitirule)** · [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24449844.svg)](https://doi.org/10.5281/zenodo.24449844)
How far can a plant disease alert computed from free weather data be trusted?
[Technical report (PDF)](https://github.com/mateuszunino/vitirule/blob/main/docs/v2/report_v2.pdf) ·
[Browser tool](https://mateuszunino.github.io/vitirule/app/)

- Four published warning rules (Rule 3-10, Goidànich, revised Mills, TOM-CAST) run on
  station data with a leaf wetness sensor, then on the same station without the sensor
  and on free gridded data (ERA5, Open-Meteo forecasts, NASA POWER).
- Preregistered: rules, metrics and quality control were frozen in Git tags before any
  comparison was run.
- In the European exploratory set (INRAE AgroClim, Politecnico di Torino), no free
  gridded source met the usability criterion for any rule. For apple scab, a local
  station without the leaf wetness sensor did.
- Transfer to 11 INMET stations in Santa Catarina, Brazil, selected blindly before the
  data were downloaded.
- The browser tool runs the frozen rules on a grower's own station data, with no installation.

**Development and validation of a deep learning model for the detection of flaxseed capsules**
(undergraduate thesis, UFSC, 2026). Co-author of `flax_capsule_det`, a YOLO26 model for detecting and counting flax
(*Linum usitatissimum*) capsules, published by NEPEM-UFSC on
[Hugging Face](https://huggingface.co/datasets/NEPEM-UFSC/dl_models).
I collected and annotated the complex-background training images.
On the held-out test set (295 images, 5,718 capsules): precision 98.9%,
recall 99.0%, mAP@50 0.98, counting R² 0.999.

## Background

- Field trials with flax at NEPEM-UFSC (plant breeding and experimentation lab): plot management, assessments and data analysis.
- Data reporting with Power BI in public administration (2019–2021).

## Tools

Python (NumPy, SciPy, pandas) · R (`pliman`, `metan`, `agricolae`) · YOLO-based
computer vision · PostgreSQL · Git

I build software with AI coding assistants and state in each project what they did
and what I did.

## Languages

Portuguese (native) · English (fluent) · French (B1)

## Contact

Florianópolis, SC, Brazil · open to roles in Brazil, Europe and remote
[zuninoespindola@gmail.com](mailto:zuninoespindola@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/mateuszunino/)
