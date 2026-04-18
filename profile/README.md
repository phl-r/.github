## Mabuhay! 🇵🇭 

**PinasR: Philippine Software Registry** is an independent, community-driven repository which aims to **consolidate, build, and distribute R packages developed by Filipino scientists,researchers, and developers**, ensuring that local data and specialized packages are translated into actionable insights for the Filipino people. Our current and updated registry is hosted in [R-Universe.](https://pinasr.r-universe.dev/builds) #ParaSaBayan ✊💻

## 🏛️ Our Mission
To empower the Filipino scientific community by providing a centralized, localized home for R software. We bridge the gap between researchers and developers to foster a culture of reproducible and accessible science in the Philippines.

## 🎯 Core Objectives
*   **🇵🇭 Visibility:** Providing a dedicated stage for Filipino-led R packages to ensure local research reaches a global audience.
*   **🌀 Resilience:** Promoting computational tools tailored specifically to our unique geographic and socioeconomic landscape.
*   **🤝 Collaboration:** Connecting Pinoy R users to share knowledge and build better tools together.

## ⚒️ Setup
You can add the entire Philippine R ecosystem to your session with one line of code:

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

Are you a Filipino R developer? 🇵🇭 If you have a package on GitHub or CRAN that serves the Philippine context or was built by a Pinoy, we want to showcase your work!

1. **Open an Issue:** Simply open an issue with your repository link OR;
2. **Submit a PR:** If you're comfortable with JSON, submit a Pull Request to our packages.json file.
3. **Spread the Word:** Use the hashtag #PinasR on social media to highlight Filipino-made packages!

## 📝 About the Logo & Identity
The PHL-R Registry logo is a derivative of the official R Project logo by the R Foundation, used under the CC-BY-SA 4.0 license. Our adaptation incorporates the Philippine Sun and Stars to represent our local community of practice.

*The PHL-R Registry is an independent, community-driven project and is not officially affiliated with or endorsed by the R Foundation.*
