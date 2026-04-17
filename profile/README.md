Mabuhay!👋

<div align="center">
  <img src="assets/phlogo.png" width="120" />
  <h1>Pinoy R Registry</h1>
  <p><i>The Central Infrastructure for Philippine R Software</i></p>
</div>

---

### The Decentralized Software Registry for the Philippine R Ecosystem

The **PHL-R Registry** is a community-driven repository hosted on [R-Universe](https://r-universe.dev). Our mission is to consolidate, build, and distribute R packages developed by Filipino scientists and researchers, specifically those addressing the unique challenges of an archipelagic nation.

---

## 🏛️ Our Mission
We provide the open-source infrastructure for:
* **Archipelagic Spatial Modeling:** R Packages like `roroph` and `ArchipelagoEngine` that account for maritime logistics.
* **National Statistics:** Streamlining access to PSA and LGU-level data.
* **Public Health:** Hosting foundational epidemiology tools built for the Philippine context.

## 🚀 How to use
To install packages from this registry, add the following to your R profile or session:

```r
options(repos = c(
  phlr = "[https://phl-r.r-universe.dev](https://phl-r.r-universe.dev)",
  CRAN = "[https://cloud.r-project.org](https://cloud.r-project.org)"
))
```
Then install as usual. For example:
```
install.packages("roroph")
```
## 🤝 Contributing
Are you a Filipino R developer? If you have a package on GitHub or CRAN that serves the Philippine context, we invite you to be inducted.

1.Open an Issue with your repository link.

2. Or submit a Pull Request to the packages.json file.
-->
