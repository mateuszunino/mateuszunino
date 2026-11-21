# Mateus Zunino Espindola

Agronomist in training at the Federal University of Santa Catarina (UFSC), Brazil.
I work on **agrometeorology and plant disease decision support**: weather-driven models
for crop protection, tested against simulation, held-out years and field sensor data.

## Featured work

**[vitirule](https://github.com/mateuszunino/vitirule)**
An open, reproducible protocol for evaluating weather-driven spray rules against
grapevine downy mildew (*Plasmopara viticola*) before field trials.
[Technical report (PDF)](https://github.com/mateuszunino/vitirule/blob/main/docs/technical_report.pdf)

- Rules were frozen in Git before each evaluation, with separate year blocks for
  selection and validation (2016–2025, Moselle, Bordeaux, Alsace, Champagne, Burgundy).
- Negative result: assimilating leaf severity into the forecast added nothing over a
  forecast-and-rain-wash-off rule at an equal spray budget.
- Leaf wetness estimators were checked against 80,000 hours of field sensor data
  (INRAE AgroClim, Politecnico di Torino). The weather data source mattered more
  than the choice of formula.
- The rule beats fixed calendars by sizing each season's spray campaign, not by
  better timing within a season. Its two worst failure seasons are documented.

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
