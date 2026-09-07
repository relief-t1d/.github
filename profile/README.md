# <img src="https://projects.ugr.es/relief-t1d/assets/img/project/Logo.png" width="85" alt="RELIEF-T1D Logo" align="center" /> &nbsp;&nbsp; RELIEF-T1D

**RELIEF-T1D: towards Clinically Reliable AI Prediction of Adverse Glycemic Events for Improved Quality of Life in Type 1 Diabetes**

[![Website](https://img.shields.io/badge/Website-projects.ugr.es%2Frelief--t1d-005691?style=flat-square&logo=googlechrome&logoColor=white)](https://projects.ugr.es/relief-t1d/index.html)

---

### At a Glance

The **RELIEF-T1D** project is working to make nights safer for people living with Type 1 Diabetes (T1D). Our aim is to enable a new generation of clinically robust "early warning systems" building on AI to predict dangerous shifts in blood sugar before they happen.

> **Further Information:** Visit the [RELIEF-T1D Website](https://projects.ugr.es/relief-t1d/index.html) for detailed project scope, updates, and research publications.

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <h4>The Challenge of Overnight Glucose Management</h4>
      <p>Overnight glucose control in Type 1 Diabetes is particularly challenging because sleep removes the patient’s ability to notice symptoms and react in real time. That creates a vulnerable window where glucose can drift into dangerous lows (hypoglycemia) or rise into sustained highs (hyperglycemia) without immediate correction. <b>RELIEF-T1D</b> focuses on predicting these nocturnal adverse glycemic events to reduce the guesswork involved in nighttime decisions and to ease the anxiety that often surrounds going to sleep with uncertain glucose trends.</p>
    </td>
    <td width="33%" valign="top">
      <h4>Advancing AI through CGM Data</h4>
      <p>The project leverages Continuous Glucose Monitoring (CGM), which provides dense, time-stamped glucose trajectories rather than occasional spot measurements. While today’s CGM-based tools already help, <b>RELIEF-T1D</b> aims to push beyond them by developing AI models that prioritize clinical reliability, not just average numerical accuracy. By learning meaningful patterns in CGM time series, these models estimate both the expected timing and the likely intensity of an upcoming event, with the explicit goal of improving trustworthiness and reducing false positives that can lead to alarm fatigue for patients and caregivers.</p>
    </td>
    <td width="33%" valign="top">
      <h4>Enabling Proactive Care</h4>
      <p><b>RELIEF-T1D</b> is designed to shift nighttime care from reactive correction to proactive prevention through earlier, higher-confidence warnings. If the model can flag risk hours before an event becomes clinically significant, it gives the user a chance to intervene at the most effective moment—before glucose leaves a safe range. In practice, this could support small, precise actions such as taking carbohydrates to avert a low or adjusting insulin dosing to prevent a high, ultimately increasing time-in-range and helping people achieve safer, more restful, uninterrupted sleep.</p>
    </td>
  </tr>
</table>

---

### Code & Repositories

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/relief-t1d/relief-t1d-core"><code>relief-t1d-core</code></a></h4>
      <p>Source code and data processing pipelines for Continuous Glucose Monitoring (CGM) time series. Contains reusable, packageable software logic.</p>
      <p><sub><code>Python</code> &nbsp;•&nbsp; <code>Data Pipelines</code> &nbsp;•&nbsp; <code>Core Package</code></sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/relief-t1d/relief-t1d-data"><code>relief-t1d-data</code></a></h4>
      <p>Repository for storing, documenting, and versioning continuous glucose monitoring datasets used throughout the research.</p>
      <p><sub><code>CGM Datasets</code> &nbsp;•&nbsp; <code>Data Versioning</code> &nbsp;•&nbsp; <code>Documentation</code></sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/relief-t1d/relief-t1d-experiments"><code>relief-t1d-experiments</code></a></h4>
      <p>Experimental workflows, scripts, and documented results providing all necessary information for full research reproducibility.</p>
      <p><sub><code>Reproducibility</code> &nbsp;•&nbsp; <code>Experiment Tracking</code> &nbsp;•&nbsp; <code>Research Logs</code></sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/relief-t1d/relief-t1d-models"><code>relief-t1d-models</code></a></h4>
      <p>Model registry housing stable, versioned artifacts and checkpoints of trained machine learning and deep learning models.</p>
      <p><sub><code>Model Registry</code> &nbsp;•&nbsp; <code>Trained Models</code> &nbsp;•&nbsp; <code>ML Artifacts</code></sub></p>
    </td>
  </tr>
</table>

---

### Acknowledgment

Grant PID2023-148188OA-I00 funded by: MICIU/AEI /10.13039/501100011033 and by ERDF, EU.

<img src="https://projects.ugr.es/relief-t1d/assets/img/project/MICIU+Cofinanciado+AEI.jpg" alt="Institutional Funding Logos" width="400" />
