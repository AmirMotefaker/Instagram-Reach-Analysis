# Instagram Reach Analysis

[![GitHub stars](https://img.shields.io/github/stars/AmirMotefaker/Instagram-Reach-Analysis?style=flat&logo=github)](https://github.com/AmirMotefaker/Instagram-Reach-Analysis/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AmirMotefaker/Instagram-Reach-Analysis?style=flat&logo=github)](https://github.com/AmirMotefaker/Instagram-Reach-Analysis/network/members)
[![Python](https://img.shields.io/badge/Python-Data%20Analysis-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

A practical Python/Jupyter project for exploring Instagram reach, engagement, traffic sources, captions, and hashtags.

## Project snapshot

The notebook works with a dataset containing **119 rows and 13 columns**. The observed fields include:

- Impressions
- From Home
- From Hashtags
- From Explore
- From Other
- Saves
- Comments
- Shares
- Likes
- Profile Visits
- Follows
- Caption
- Hashtags

The project uses Python data-analysis and visualization tooling to explore how reach and engagement signals relate to Instagram content performance.

## Open the analysis

- **GitHub Notebook:** [`instagram-reach-analysis.ipynb`](instagram-reach-analysis.ipynb)
- **Kaggle Notebook:** [Open on Kaggle](https://www.kaggle.com/code/amirmotefaker/instagram-reach-analysis)
- **Dataset source referenced by the notebook:** [Instagram data archive](https://statso.io/wp-content/uploads/2022/10/archive.zip)

## Analysis workflow

1. Load the Instagram dataset with pandas.
2. Inspect data quality and column types.
3. Explore impression sources such as Home, Hashtags, and Explore.
4. Compare engagement signals such as Saves, Comments, Shares, Likes, Profile Visits, and Follows.
5. Explore text fields including captions and hashtags.
6. Visualize patterns using Python plotting libraries.

## Tech stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Plotly` · `Jupyter Notebook`

The notebook also imports additional analysis/visualization libraries for experimentation.

## Run locally

```bash
git clone https://github.com/AmirMotefaker/Instagram-Reach-Analysis.git
cd Instagram-Reach-Analysis
jupyter notebook
```

Open `instagram-reach-analysis.ipynb` and point the data-loading cell to your local dataset path if needed.

## Why star this repository?

If you are learning data analysis, social-media analytics, or exploratory Python workflows, a ⭐ helps other learners find the project and signals that this type of practical analysis is useful.

## Author

**Amir Motefaker** — [GitHub](https://github.com/AmirMotefaker) · [Kaggle](https://www.kaggle.com/amirmotefaker) · [Website](https://amirmotefaker.ir)
