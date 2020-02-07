
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

<!-- Begin Jekyll SEO tag v2.5.0 -->
<title>Modernist theme | Modernist is a theme for GitHub Pages.</title>
<meta name="generator" content="Jekyll v3.8.5">
<meta property="og:title" content="Modernist theme">
<meta property="og:locale" content="en_US">
<meta name="description" content="Modernist is a theme for GitHub Pages.">
<meta property="og:description" content="Modernist is a theme for GitHub Pages.">
<link rel="canonical" href="https://pages-themes.github.io/modernist/">
<meta property="og:url" content="https://pages-themes.github.io/modernist/">
<meta property="og:site_name" content="Modernist theme">
<link rel="stylesheet" crossorigin="anonymous" href="https://gc.kis.v2.scr.kaspersky-labs.com/E3E8934C-235A-4B0E-825A-35A08381A191/abn/main.css?attr=aHR0cHM6Ly9wYWdlcy10aGVtZXMuZ2l0aHViLmlvL21vZGVybmlzdC8"><script type="application/ld+json">
{"@type":"WebSite","url":"https://pages-themes.github.io/modernist/","name":"Modernist theme","description":"Modernist is a theme for GitHub Pages.","headline":"Modernist theme","@context":"http://schema.org"}</script>
</head>
<!-- End Jekyll SEO tag -->


    <link rel="stylesheet" href="/modernist/assets/css/style.css?v=d1f2ae8f2c481e828b95319cc17500eba8969891">
    <script src="/modernist/assets/js/scale.fix.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">

    <!--[if lt IE 9]>
    <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
  </head>

---
# Data Analysis of SAT & ACT of 2017 & 2018

### Overview

Our analysis will contain:
- basic statistics (distributions, confidence intervals, hypothesis testing)
- visualizations
- ACT & SAT exam dataset from 2017 to 2018
- Jupyter notebooks

---
### Problem Statement
There is a low participation for SAT exam as compared to ACT, the analysis will look for correlations in the data and make inferences to ensure that any hypothesis is true

---

### Datasets

#### Provided Data

For this project, there have four datasets:

- [2017 SAT Scores](../data/sat_2017.csv)
- [2017 ACT Scores](../data/act_2017.csv)
- [2018 SAT Scores](../data/sat_2018.csv)
- [2018 ACT Scores](../data/act_2018.csv)
---

#### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**State**|*object*|ACT/SAT|The name of one of United States of America's National state| 
|**ACT_Participation**|*float*|ACT|Percentage of actual number people attending the ACT examination compared to the number people registered | 
|**SAT_Participation**|*float*|SAT|Percentage of actual number people attending the SAT examination compared to the number people registered | 
|**ACT_English**|*float*|ACT|Mean score of participants taking ACT exam for english| 
|**ACT_Math**|*float*|ACT|Mean score of participants taking ACT exam for math| 
|**ACT_Reading**|*float*|ACT|Mean score of participants taking ACT exam for reading| 
|**ACT_Science**|*float*|ACT|Mean score of participants taking ACT exam for science| 
|**ACT_Composite**|*float*|ACT|Mean score of participants taking ACT exam for all examinations|
|**SAT_Evidence-Based_Reading_and_Writing**|*float*|SAT|Mean score of participants taking SAT exam for all examinations| 
|**SAT_Math**|*float*|SAT|Mean score of participants taking SAT exam for maths|
|**SAT_Total**|*float*|SAT|Total score of participants taking SAT exam for all examinations|

#### References
https://blog.prepscholar.com/act-vs-sat
https://blog.prepscholar.com/new-sat-vs-old-sat-quick-summary
---
