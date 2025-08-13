# ProAc-Python

**Visual, multi-metric academic profiling — Python version**

This repository hosts the **Python implementation** of ProAc: a visual, multi-metric academic profile designed to support **time-saving**, **objective**, and **inclusive academic evaluation**. ProAc helps highlight diverse talents beyond traditional evaluation metrics. Learn more at [www.fabiocrameri.ch/proac](https://www.fabiocrameri.ch/proac) :contentReference[oaicite:0]{index=0}.

To actually create your personal ProAc profile, simply go to the ProAc online toolbox at proac.pythonanywhere.com. Upload your CSV, enter your name, choose your output format, and you'll get the visual profile instantly. This repository just hosts the underlying code for development reasons.


---

##  Why ProAc?

- Traditional metrics like the **h-index** misrepresent academic performance and reinforce inequality.
- ProAc provides a **multi-metric profile**, offering a fairer, more nuanced view of academic contributions :contentReference[oaicite:1]{index=1}.
- Developed by Fabio Crameri to shift the narrative away from ranking and toward profiling :contentReference[oaicite:2]{index=2}.

---

##  Features

- Read a structured CSV with publication metadata and generate a visual academic profile.
- Output formats include **PDF**, **PNG (transparent)**, **SVG**, and **dark-background variants** :contentReference[oaicite:3]{index=3}.
- Built with accessibility and clarity in mind—leveraging Python and scientific colour maps for universal readability :contentReference[oaicite:4]{index=4}.
- Offered under the **MIT License** :contentReference[oaicite:5]{index=5}.

---

##  Getting Started

### 1. Prepare your data

Use the ProAc **data template**, available via [www.fabiocrameri.ch/proac](https://www.fabiocrameri.ch/proac), and export your filled file as CSV :contentReference[oaicite:6]{index=6}.

**Required columns**:

| Column              | Description                                  | Type     |
|---------------------|----------------------------------------------|----------|
| `Year`              | Publication year                             | Integer  |
| `Kind`              | E.g., "Peer-reviewed paper", "Blog post", etc. | String   |
| `First authored`    | Was it first-authored?                       | Binary   |
| `Including PhD supervisor` | Was your PhD supervisor a co-author?   | Binary   |
| `Open access`       | Is it openly accessible?                     | Binary   |
| `Citations`         | Number of citations                          | Integer  |

Optional extras (helpful but not mandatory): `Tag`, `Title`, `Publisher`, `Full reference`, `Link`, `Single authored` :contentReference[oaicite:7]{index=7}.

### 2. Run ProAc-Python

1. Clone this repo:
   ```bash
   git clone https://github.com/Crameri/ProAc-Python.git
   cd ProAc-Python


##  References

- Crameri, F. (2023). Multi-metric academic profiling with ProAc (1.0.0). Zenodo. [https://doi.org/10.5281/zenodo.4899015](https://doi.org/10.5281/zenodo.4899015)
- ProAc user guide and templates: [www.fabiocrameri.ch/proac](https://www.fabiocrameri.ch/proac)


