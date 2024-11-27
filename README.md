# Introduction to basics of R

I have written some of these explainers to help my students transition into `R`. Most of them are coming from Stata, so much of my code reflects that. Nonetheless, I hope you find these helpful.

You can find the actual website [here](https://joshmerfeld.github.io/rintro/datawrangling.html).

Some notes:

- I use the `tidyverse` package for data wrangling. I find it to be the most intuitive and user-friendly package for beginners.
- I use data from Malawi for all of my examples. Specifically, I use the 2019 fifth integrated household survey (aka the IHS5). This data is publicly available from the National Statistical Office of Malawi (NSO) and from the [World Bank's microdata repository](https://microdata.worldbank.org/index.php/catalog/3818).As this is a public dataset and since I am using it as part of a class I teach at the [KDI School](https://www.kdischool.ac.kr/), I have uploaded the data to this GitHub repository. However, two small notes:
  - I have *not* included one specific module from the survey: `HH_MOD_G1` (section G1 from the household module). The file itself is almost 500 MB, which is above GitHub's limit. If you want to play around with that specific module, you can download it yourself from the website above. (I of course will not use it here.)
  - I have created a single `.zip` file that you can download from my Dropbox. You can download it [here](https://www.dropbox.com/scl/fi/6nv737pv60u7941kbzlql/ihs5.zip?rlkey=95bglhhqunc059zqpvpcmobbk&dl=0). **(If this link ever breaks, please e-mail me so I can fix it.)** The file is about 115 MB. Alternatively, you can just download the individual modules from this repository, in the [datawranglingfiles folder](datawranglingfiles).
  
- If you want me to add something specific to the explainer, please feel free to open an issue (within reason, of course).
- I created the entire explainer using `Quarto` in `RStudio`. You can find the raw code in the `datawrangling.qmd` file.


