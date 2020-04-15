---
title: "Master's Thesis"
excerpt: "Probabilistic Forecasting with Monte-Carlo Dropout Network"
header:
  image: /assets/images/unsplash-gallery-image-1.jpg
  teaser: assets/images/unsplash-gallery-image-1-th.jpg
sidebar:
  - title: "Supervisors"
    image: /assets/images/cs-ut-logo.png 
    image_alt: "logo"
    text: "Meelis Kull, Sebastian Haglund El Gaidi, Erik Ylipää"
  - title: "Year"
    text: "2019"
gallery:
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
---

Last year I completed my master thesis which was conducted jointly with [Greenlytics AB](https://greenlytics.io/) and [SICS @ RI.SE](https://www.ri.se/sv?refdom=sics.se) in Stockholm, Sweden. In my master's I had a diverse experience within the data science / machine learning specialization but most of my focus was on applications of machine learning in time-series forecasting. That is partly due to interest and partly how it came out. Nevertheless my final layer was a mix experience of Erasmus+ exchange studies and doing my master thesis abroad in Sweden with the Greenlytics and RISE. My experience at KTH and in Sweden was pretty exciting and I am grateful to the program and the opportunity. Here's the abstract form my master thesis:

<!--{% include gallery caption="This is a sample gallery to go along with this case study." %}-->

Integration of intelligent systems in our industries and society require more accurate and reliable algorithms. Recent attempts to model and explain uncertainty in deep learning has had many achievements, stepping forward toward making these models more reliable and respectively more practical. At the same time, probabilistic forecasting is a similar attempt to estimate the future value of a variable by a probabilistic expression rather a point estimate. The former is more useful as it incorporates uncertainty information on the forecast while the latter lacks this. To this day, there has not been much research or study on probabilistic forecasts with Bayesian deep learning, making it an interesting area for contribution. We considered this research to be more interesting by carrying it out on a real-world problem and therefore, chose the wind power forecast beside the analytical study. We applied Monte-Carlo Dropout (MCDO), a variant of deep Bayesian network approximator, together with a network capable of estimating the variance. This predictive variance, produced by the model, is equivalent to a probabilistic forecast and further, we show how to obtain higher quality forecasts that are accurate and better-calibrated by scenario forecasting at test-time. We also show that the results of the MCDO implementation were consistent with other works. Moreover, our approach proved to be capable of producing a high-quality probabilistic forecast with rather a simple setup and no special treatment. Results obtained in this thesis not only reflect on probabilistic forecasting but, also on the Bayesian deep learning. Our experiments show a successful use case of employing Bayesian deep learning and suggest that these methods are the way to go, with promises on improving the accuracy, scalability, and interpretability.

[Linked to the thesis (English)](https://comserv.cs.ut.ee/ati_thesis/datasheet.php?language=en)
[Linked to the thesis (Estonian)](https://comserv.cs.ut.ee/ati_thesis/datasheet.php?language=et)
