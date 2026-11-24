# personal-website

The source code for the academic homepage of **Arnoneel Sinha, PhD**, biostatistician and postdoctoral fellow at the Center for Biotechnology & Genomic Medicine, Augusta University.

**Live site:** https://asinha639.github.io/personal-website/

---

## Abstract

This repository contains a personal website. We fail to reject the null hypothesis that it is, in fact, just a website. However, preliminary evidence (n = 1 visitor, namely you) suggests it may also contain research, teaching, publications, and a small number of statistics jokes, all of which are reported below with appropriate uncertainty.

## Methods

The site was built with a deliberately parsimonious model:

- **HTML** for structure
- **CSS** for style
- **A little JavaScript** for the parts that move
- **Zero frameworks, zero build tools, zero dependencies to install**

In keeping with Occam's razor, no additional parameters were introduced without evidence that they improved the fit.

## Data (what's in the repo)

```
index.html          Main page: about, research, publications, teaching, contact
story.html          "My Story": a longer personal essay
playground.html     Stats Playground: small interactive demos
assets/css/         Stylesheets
assets/img/         Images
assets/files/       CV (PDF)
```

## Reproducibility

To view the site on your own machine, clone the repository and open `index.html` in any modern browser. No installation required. If it does not render, please check the assumption that you have a browser; violations of this assumption have not been tested.

To preview it on a phone over the same Wi-Fi network:

```
python -m http.server 8000
```

then open `http://<your-computer's-IP>:8000` on the phone.

## Results

The design follows a quiet, scholarly approach: warm paper tones, serif typography, hairline rules, and generous whitespace. The layout adapts from small phones to large desktop monitors. Every effort was made to ensure that nothing scrolls sideways, which is more than can be said for most conference posters.

## Discussion

**Limitations.** Live weather on the homepage depends on a third-party service (Open-Meteo) and may occasionally report "unavailable." This is a missing-data problem, and we have chosen not to impute the weather.

**Correlation vs. causation.** No causal link has been established between visiting this site and deciding to become a biostatistician. Observational data are, however, encouraging.

**Changelog.** The full history is in the commit log. Readers familiar with the author's research may enjoy attempting to detect the change points.

## Contact

Corrections, questions, and collaboration ideas are welcome. Contact details are on the [website](https://asinha639.github.io/personal-website/).

## License

Content © Arnoneel Sinha. Please ask before reusing text, images, or the CV.