<div align="center">
  <img src="https://raw.githubusercontent.com/phl-r/.github/main/assets/phflag.png" width="120" />
  <h1>PinasR</h1>
  <p><i>The Central Infrastructure for Philippine R Software</i></p>
</div>

---

### 🌊 Why a Philippine Registry?
The Philippines is a unique archipelagic nation facing distinct challenges—from **typhoon modeling** and **maritime logistics** to **public health** and **local spatial analysis**. 

**PinasR: PHL Software Registry** is a community-driven repository hosted on [R-Universe](https://phl-r.r-universe.dev/builds). Our mission is to consolidate, build, and distribute R packages developed by Filipino scientists,researchers, and developers ensuring that local data is translated into actionable insights for the country.

---

## 🏛️ Our Mission
To empower the Filipino scientific community by providing a centralized, localized home for R software. We bridge the gap between researchers and developers to foster a culture of reproducible and accessible science in the Philippines.

## 🎯 Core Objectives
*   **🇵🇭 Visibility:** Providing a dedicated stage for Filipino-led R packages to ensure local research reaches a global audience.
*   **🌀 Resilience:** Promoting computational tools tailored specifically to our unique geographic and socioeconomic landscape.
*   **🤝 Collaboration:** Connecting Pinoy R users to share knowledge and build better tools together.

---
## 🤔 Why join and contribute to PinasR?

**👨🏻‍💻For the developers:** We’ve built a centralized infrastructure to mirror Filipino-made R packages directly to R-Universe. Here’s why you should list your package here: 

**Instant Compatibility Checks:** Every time you push code, our registry automatically triggers a build across Windows, macOS, and Linux. You get a real-time status on whether your package is cross-platform compatible without setting up complex CI/CD yourself.

**Automatic Binaries:** R-Universe generates CRAN-like binaries. Your users won't need to "build from source" or install heavy development tools (like Rtools or Xcode). They can just install.packages().

**Archipelagic SEO:** By joining PinasR, your package becomes part of a curated "National Collection." We aim for researchers and local agencies to find "Philippine-made tools" in one place than hunting through random GitHub repos.

**Maintain Your Autonomy:** You keep 100% control. We don't host your code; we just index it. You continue to develop on your own repo, and our registry simply acts as a "signal booster."

**👩‍💻For the Users:** Why should you use the phl-r registry instead of just installing from GitHub?

**Reliability & Speed:** Installing from our registry is significantly faster than devtools::install_github() because the packages are pre-compiled.

**Standardized Quality:** Every package in the phl-r universe is monitored. If a build fails, it’s flagged immediately. You can trust that the "current version" is actually functional.

**A Unified Ecosystem:** No more "dependency hell." We ensure that the tools built for the Philippine context—spatial datasets, maritime models, and local palettes—work seamlessly together.

**Easy Setup:** You can add the entire Philippine R ecosystem to your session with one line of code:

```r
# Run this in your R console or add to your .Rprofile
options(repos = c(
  phlr = "https://phl-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))

# Then install as usual, for example:
install.packages("roroph")

# OR alternative: One-liner using the universe helper
install.packages("universe", repos = "https://ropensci.r-universe.dev")
universe::add("phl-r")
```
## 🤝 Sali Na! (How to Contribute)

Are you a Filipino R developer? If you have a package on GitHub or CRAN that serves the Philippine context or was built by a Pinoy, we want to showcase your work!

1. **Open an Issue:** Simply open an issue with your repository link OR;
2. **Submit a PR:** If you're comfortable with JSON, submit a Pull Request to our packages.json file.
3. **Spread the Word:** Use the hashtag #PinasR on social media to highlight Filipino-made packages!

## 📝 About the Logo & Identity
The PHL-R Registry logo is a derivative of the official R Project logo by the R Foundation, used under the CC-BY-SA 4.0 license. Our adaptation incorporates the Philippine Sun and Stars to represent our local community of practice.

*The PHL-R Registry is an independent, community-driven project and is not officially affiliated with or endorsed by the R Foundation.*
