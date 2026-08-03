# Ryota Ono / 小野凌太 Academic Homepage

Static bilingual GitHub Pages site using plain HTML and CSS.

## Page structure

- `/index.html`: Japanese version and default landing page
- `/en/index.html`: English version
- `/styles.css`: shared design
- `/profile_zoom.webp`: optimized profile photograph
- `/BCGO1.png`, `/BCGO.png`: research figures
- `/Ryota_Ono_CV.pdf`: downloadable CV
- `/googleb3ea3a791aef016c.html`: Google site verification

The language controls in the upper-right corner link between the Japanese and
English URLs. Separate URLs are used instead of a JavaScript-only switch so
that both language versions can be indexed and shared independently.

## Publish

Upload the entire contents of this package to the root of
`ryotaono10/homepage`, preserving the `en` folder.

```bash
git clone https://github.com/ryotaono10/homepage.git
cd homepage

# Copy all files and the en/ directory into this repository.
git add .
git commit -m "Add Japanese and English versions"
git push origin main
```

The main name is intentionally kept at a moderate size, with the alternate-language name shown beneath it.

Academic degree: Ph.D. in Science / 博士（理学）. Current English affiliation: Japan Atomic Energy Agency, Advanced Science Research Center.

Research profile: https://researchmap.jp/ryota_ono
