<!-- Header -->
<div align="left">

<br>

# class Aroa:

*"""Answers her own questions with data."""*

<br>

</div>

<br>

<!-- About Me Section -->
<details open>
<summary><h3>Overview</h3></summary>

<br>
<br>

<div align="left">

> I'm in it for the moment "huh" becomes "oh, that's why."
>
> Statistically normal, personally an outlier.

</div>

<br>

</details>

<br>

<!-- Skills & Tools Section -->
<details open>
<summary><h3>Tech Stack</h3></summary>
<br>

<div align="center">

#### Data

<table>
<tr>
<td align="center" width="20%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60"/>
<br><b>Python</b>
</td>
<td align="center" width="20%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="60"/>
<br><b>Pandas</b>
</td>
<td align="center" width="20%">
<img src="icons/polars.svg" width="60"/>
<br><b>Polars</b>
</td>
<td align="center" width="20%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="60"/>
<br><b>SQL</b>
</td>
<td align="center" width="20%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="60"/>
<br><b>Jupyter</b>
</td>
</tr>
</table>

<br>

#### Machine Learning

<table>
<tr>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="60"/>
<br><b>scikit-learn</b>
</td>
<td align="center" width="25%">
<img src="icons/xgboost.png" width="60"/>
<br><b>XGBoost</b>
</td>
<td align="center" width="25%">
<img src="icons/scipy.svg" width="60"/>
<br><b>SciPy</b>
</td>
<td align="center" width="25%">
<img src="icons/statsmodels.svg" width="60"/>
<br><b>statsmodels</b>
</td>
</tr>
</table>

<br>

#### Cloud & Ops

<table>
<tr>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" width="60"/>
<br><b>AWS</b>
</td>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="60"/>
<br><b>Docker</b>
</td>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="60"/>
<br><b>FastAPI</b>
</td>
<td align="center" width="25%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="60"/>
<br><b>Git</b>
</td>
</tr>
</table>

<br>

#### Visualization

<table>
<tr>
<td align="center" width="33%">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="60"/>
<br><b>Matplotlib</b>
</td>
<td align="center" width="33%">
<img src="https://cdn.simpleicons.org/streamlit/FF4B4B" width="60"/>
<br><b>Streamlit</b>
</td>
<td align="center" width="33%">
<img src="https://img.icons8.com/color/48/000000/tableau-software.png" width="60"/>
<br><b>Tableau</b>
</td>
</tr>
</table>

</div>

<br>


<br>

</details>

<br>

<!-- Certifications Section -->
<details open>
<summary><h3>Education</h3></summary>
<br>

```
$ git status -s
A  google-data-analytics   # Google Data Analytics · completed
 M bsc-data-science        # BSc Data Science · UOC · ongoing
 M ironhack-bootcamp       # Data Analytics Bootcamp · Ironhack · ongoing
```

<div align="left">

[UOC](https://github.com/UOC) · [Ironhack](https://github.com/ironhack)

</div>

<br>

</details>

<br>

<!-- Projects Section -->
<details open>
<summary><h3>Featured Projects</h3></summary>
<br>

<div align="left">

#### cloud-cost-predictor

**[cloud-cost-predictor](https://github.com/aroaxinping/cloud-cost-predictor)**

Predicts cloud infrastructure waste from 123K real VMs. XGBoost quantile regression (q=0.10/0.50/0.95) with asymmetric loss recommends which VMs to terminate, downsize, or keep — **$5.9M/month waste identified** on an $11M fleet (54%). Includes a Reserved Instances module pricing real AWS commitment discounts against on-demand cost, and a Monte Carlo simulation for uncertainty-aware savings estimates.

`Python` `XGBoost` `FastAPI` `Docker` `Streamlit` · *SHAP explainability · quantile regression · Monte Carlo*

---

#### leaked-key-impact

**[leaked-key-impact](https://github.com/aroaxinping/leaked-key-impact)**

Deliberately leaked a fake AWS key to see who'd use it. Grew into a fleet of decoy credentials — **1,301 real attacks** logged, mapped to MITRE ATT&CK, enriched with OSINT, and priced with a real cost model.

`Python` `boto3` `MITRE ATT&CK` `Streamlit` · *OSINT enrichment · A/B experiment on credential placement*

---

#### drive-failure-predictor

**[drive-failure-predictor](https://github.com/aroaxinping/drive-failure-predictor)** · [**Pitch deck →**](https://docs.google.com/presentation/d/1Li62E2sg0PKQaqIFmbMlMlFfaS1nOipx/edit?usp=sharing&ouid=103123837645577444399&rtpof=true&sd=true)

Predictive maintenance model that detects 96% of hard drive failures before they happen, using SMART sensor data from 318K production drives. Cost-optimised threshold saves **$49,200/quarter** vs reactive maintenance. Temporal validation with rolling windows confirms the model generalises across time (F1 = 0.77, AUC-ROC = 0.99).

`Python` `XGBoost` `scikit-learn` `Polars` `Pandas` · *28M rows · cost-sensitive threshold · CLI inference*

---

#### redmoon

**[redmoon](https://github.com/aroaxinping/redmoon)** · [![PyPI](https://img.shields.io/pypi/v/redmoon?color=E6A8D7&style=flat-square)](https://pypi.org/project/redmoon/) · [**Live demo →**](https://redmoon.streamlit.app)

Python package that crosses menstrual cycle phases with sleep, HRV and heart rate data from Apple Health exports. Built on 6 years of personal data (76 cycles, 1,153 nights). Wrist temperature rises +0.375°C in luteal phase (p < 0.000001). Random Forest predicts luteal vs non-luteal at F1 = 0.79.

`Python` `pandas` `scipy` `sklearn` `streamlit` `PyPI` · *CLI + dashboard + 37 pytest tests + CI*

---

#### PyPI packages — tokpipe & instapipe

**[tokpipe](https://github.com/aroaxinping/tokpipe)** · [![PyPI](https://img.shields.io/pypi/v/tokpipe?color=E6A8D7&style=flat-square)](https://pypi.org/project/tokpipe/) · [**Live demo →**](https://tokpipe.streamlit.app) &nbsp;|&nbsp; **[instapipe](https://github.com/aroaxinping/instapipe)** · [![PyPI](https://img.shields.io/pypi/v/instapipe?color=E6A8D7&style=flat-square)](https://pypi.org/project/instapipe/) · [**Live demo →**](https://instapipe.streamlit.app)

Two published Python packages for social media analytics. Import your TikTok or Instagram exports, clean the data, compute real metrics and visualize what works — no APIs, no scraping.

`Python` `pandas` `matplotlib` `PyPI` · *pip install tokpipe / pip install instapipe*

---

**Other projects**

| Repo | Stack | About |
|---|---|---|
| [data-playground → Oil, War, and the Price at the Pump](https://github.com/aroaxinping/data-playground) | Python · pandas · scipy · statsmodels | Four independent analyses on fuel pricing: Pearson correlation (r = 0.99), lag cross-correlogram, geopolitical event study, Rocket & Feather asymmetry test |
| [social-media-analytics](https://github.com/aroaxinping/social-media-analytics-aroaxinping) | Python · pandas | TikTok vs Instagram — same creator, same period, two algorithms. Normalized KPIs + scorecard |
| [sql-social-media-analytics](https://github.com/aroaxinping/sql-social-media-analytics-aroaxinping) | SQL · SQLite | Same data analyzed with pure SQL — window functions, CTEs, correlated subqueries |
| [data-playground → Google Trends](https://github.com/aroaxinping/data-playground/tree/main/04-google-trends-bolsa) | Python · pytrends · yfinance | Crisis search terms vs IBEX 35 — Granger causality, cross-correlogram, 3yr weekly data |
| [data-playground → Spotify tristeza](https://github.com/aroaxinping/data-playground/tree/main/05-spotify-tristeza) | Python · spotipy | Do sad songs perform better? Valence, energy and tempo analyzed across mood playlists |
| [data-playground → Vivienda Valencia](https://github.com/aroaxinping/data-playground/tree/main/06-vivienda-valencia) | Python · pandas | Housing prices before and after the DANA floods — supply shock and displacement effect |
| [data-playground → Bitcoin Fear](https://github.com/aroaxinping/data-playground/tree/main/07-bitcoin-fear) | Python · scipy | Fear & Greed Index vs BTC price — does sentiment lead or lag the market? |
| [data-playground → Olay 89%](https://github.com/aroaxinping/data-playground/tree/main/08-olay-89-claim) | Python · scipy | Statistical deconstruction of Olay's "89% more hydration" claim — baseline bias, power analysis |
| [data-playground → Clarins](https://github.com/aroaxinping/data-playground/tree/main/09-clarins-double-serum-claims) | Python · scipy | n=24 instrumental studies vs n=388 self-assessment claims — the placebo gap quantified |
| [data-playground → Vichy M89](https://github.com/aroaxinping/data-playground/tree/main/10-vichy-mineral89) | Python · NCBI API | 5 real PubMed studies vs "100% hydration" marketing claim — methodology quality matrix |
| [data-playground → NFT](https://github.com/aroaxinping/data-playground) | Python · pandas | NFT market lifecycle: OpenSea volume, floor prices, ETH correlation, bubble factors |
| [data-playground → arte-vs-ia](https://github.com/aroaxinping/data-playground) | Python · scipy | Handmade premium 2× → 14× since generative AI boom |
| [data-playground → tech-salaries](https://github.com/aroaxinping/data-playground/tree/main/02-tech-salaries-remote-work) | Python · pandas | 89K+ devs — remote work pays 64% more |
| [scraper-gasolineras-espana](https://github.com/aroaxinping/scraper-gasolineras-espana) | Python · GitHub Actions | Weekly scraper of petrol station prices via Spain's public MINETUR API — auto-updated every Monday |

</div>

</details>

<br>

<!-- Connect Section -->
<details open>
<summary><h3>Contact</h3></summary>
<br>

<div align="left">

Open to work.

<br>

So call me maybe

```python
def hire(self):
    return self.linkedin
```

`aroa.hire()` → <a href="https://linkedin.com/in/aroaxinping"><img src="https://img.shields.io/badge/LinkedIn-D4A5D4?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

</div>

</details>

<br>

<!-- Footer Section -->
<div align="left">

<br>

<img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="40">

`# Thanks for reading until EOF`
<br>

![Profile Views](https://komarev.com/ghpvc/?username=AroaXinping&color=FFB6C1&style=flat-square&label=Profile+Views)

<br>

<br>

*License: MIT — My Ideas, Tested*

<br><br>

</div>
