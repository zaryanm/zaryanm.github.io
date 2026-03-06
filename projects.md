---
layout: page
title: Projects
---

## Multisport Comparison of Head Impact Biomechanics

### Overview
In this project, I contributed to the collection of instrumented mouthguard data from over 50 athletes. Combining this novel data with existing datasets, our primary objective was to determine whether head impact biomechanics can be reliably differentiated between sports using advanced statistical techniques and machine learning.

### Methodology
We uniformly processed a multisport dataset of direct head impacts across men’s American football, men’s ice hockey, women’s rugby, and women’s soccer. We statistically compared directional and resultant peak kinematics, alongside impulse durations. To examine clustering in impact magnitude and frequency, we applied unsupervised machine learning models, specifically k-means and t-distributed stochastic neighbor embedding (t-SNE).

### Key Findings
* **Shared Biomechanics:** While we identified some sport-specific differences, impact features (such as magnitude and frequency) largely transcended sport boundaries, showing similar clusters across American football, rugby, and ice hockey.
* **Soccer Specifics:** Impacts in women's soccer demonstrated distinct, tight clustering patterns due to consistent heading biomechanics. 
* **Future Directions:** The data highlighted that soccer may produce similar directional accelerations to football and rugby, suggesting that head impacts in soccer warrant more extensive and rigorous study.

<p style="margin-top: 20px; font-size: 1.1em;">
  <strong><a href="https://www.nature.com/articles/s41598-025-31145-4" target="_blank" style="color: #0056b3 !important; text-decoration: underline !important;">Check out the published paper here!</a></strong>
</p>

<div style="display: flex; justify-content: space-between; gap: 20px; margin-top: 30px; margin-bottom: 40px;">
  <img src="{{ site.baseurl }}/plot1.png" alt="Head Impact Data Visualization 1" style="width: 48%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
  <img src="{{ site.baseurl }}/plot2.png" alt="Head Impact Data Visualization 2" style="width: 48%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
</div>

---
