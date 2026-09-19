# Unsloth Studio — one-click notebooks

Two simple notebooks to launch [Unsloth Studio](https://unsloth.ai/docs/new/studio) on free cloud GPUs.

| Platform | Notebook | Open |
|---|---|---|
| **Google Colab** | [`Unsloth_Studio_Colab.ipynb`](./Unsloth_Studio_Colab.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/StudentOffersco/unsloth-studio-oneclick/blob/main/Unsloth_Studio_Colab.ipynb) |
| **Kaggle** | [`Unsloth_Studio_Kaggle.ipynb`](./Unsloth_Studio_Kaggle.ipynb) | See Kaggle steps below (no one-tap GitHub → Kaggle link) |

Each notebook is **one cell**: install + start (~4–5 minutes first run). Then open the Cloudflare link and enter the **password** (log in as `unsloth`).

## Google Colab
1. Open the Colab badge link above
2. Runtime → GPU (T4)
3. Run the cell → wait ~4–5 minutes
4. Open Unsloth Studio / Cloudflare URL → enter password → Model Hub or Chat `hi`

## Kaggle (first-time setup)
Kaggle is separate from Colab. Do this once, then share your **public Kaggle notebook URL** in posts.

1. Go to [kaggle.com](https://www.kaggle.com) and sign up / sign in
2. **Verify your phone** (mandatory) at https://www.kaggle.com/settings — needed to enable GPU + Internet
3. Finish any other quick account checks on that page if asked
4. **Create → New notebook**
5. **File → Import notebook** → import [`Unsloth_Studio_Kaggle.ipynb`](./Unsloth_Studio_Kaggle.ipynb) from this repo  
   (or open someone’s public copy → **Copy and Edit**)
6. Top menu **Settings** → Accelerator **GPU T4 x2** (or P100) → **Internet: On**
7. Run the cell → wait ~4–5 minutes
8. Open Unsloth Studio / Cloudflare URL → enter password → Model Hub or Chat `hi`
9. **Save Version** → make the notebook **Public** → copy `https://www.kaggle.com/code/YOU/slug` to share

### Edit sources
- Colab notebook: https://github.com/StudentOffersco/unsloth-studio-oneclick/edit/main/Unsloth_Studio_Colab.ipynb
- Kaggle notebook: https://github.com/StudentOffersco/unsloth-studio-oneclick/edit/main/Unsloth_Studio_Kaggle.ipynb

## Not affiliated with Unsloth
Helper launchers only. They clone official [`unslothai/unsloth`](https://github.com/unslothai/unsloth). Studio UI is AGPL-3.0.

Official Unsloth Colab: https://colab.research.google.com/github/unslothai/unsloth/blob/main/studio/Unsloth_Studio_Colab.ipynb
