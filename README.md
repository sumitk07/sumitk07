<p align="center">
  <img src="assets/banner.svg" alt="Sumit Kumar: information retrieval, NLP, federated learning" width="100%">
</p>

<p align="center">
  <a href="mailto:sumitwork03@gmail.com"><img src="https://img.shields.io/badge/Email-sumitwork03%40gmail.com-1c3557?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/sumit-kumar-7b9373196"><img src="https://img.shields.io/badge/LinkedIn-Sumit%20Kumar-0a66c2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Based%20in-India-e08a2c?style=flat-square">
</p>

### Hi, I'm Sumit 👋

I build small, honest research prototypes in **information retrieval** and **privacy-preserving machine learning**, and I have shipped production mobile and web apps since 2023.

🔹 **Now:** measuring how much search gets worse when people ask in English or Hindi about information that exists only in Japanese<br>
🔹 **Also:** personalised federated learning for home sensor data, where raw data never leaves the home, and sentiment of memes in low-resource languages<br>
🔹 **Before:** Flutter and React developer, 4 apps live on Google Play

---

### 🔬 Research prototypes

<table>
<tr>
<td width="50%" valign="top">

**[crosslingual-search-ja](https://github.com/sumitk07/crosslingual-search-ja)**<br>
<sub>English / Hindi questions → Japanese passages</sub>

<a href="https://github.com/sumitk07/crosslingual-search-ja"><img src="https://raw.githubusercontent.com/sumitk07/crosslingual-search-ja/main/results/figures/ndcg_by_language.png" width="100%"></a>

On 100 MIRACL-ja questions, multilingual-E5 drops from **0.818** nDCG@10 (Japanese) to **0.680** (English) and **0.644** (Hindi). Simple rank fusion with BM25 did not help.

<sub>`BM25` `multilingual-E5` `NLLB-200` `RRF` `nDCG@10`</sub>

</td>
<td width="50%" valign="top">

**[fedroutine](https://github.com/sumitk07/fedroutine)**<br>
<sub>Personalised federated anomaly detection for older adults living alone</sub>

<a href="https://github.com/sumitk07/fedroutine"><img src="https://raw.githubusercontent.com/sumitk07/fedroutine/main/results/figures/fig2_fedavg_vs_fedper_by_home.png" width="100%"></a>

On 10 simulated smart homes, FedPer matches central training (AUROC **0.844** vs 0.839) without sharing raw data. FedAvg fails on a late sleeper (**0.50**); FedPer fixes it (**0.84**).

<sub>`FedAvg` `FedPer` `autoencoder` `differential privacy` `explainability`</sub>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[meme-sentiment-bn](https://github.com/sumitk07/meme-sentiment-bn)**<br>
<sub>Where does the feeling of a meme come from: the words, the picture, or both? (Bengali, MemoSen)</sub>

<a href="https://github.com/sumitk07/meme-sentiment-bn"><img src="https://raw.githubusercontent.com/sumitk07/meme-sentiment-bn/main/results/figures/macro_f1_by_system.png" width="80%"></a>

On 871 Bengali test memes, the image alone (CLIP, **0.539** macro-F1) is as good as the best text model (**0.541**). A multilingual sentence model reaches only **0.408**, joining text and image does not help yet, and neutral memes stay below **0.27** F1 for every model.

<sub>`CLIP` `multilingual-E5` `TF-IDF` `fusion` `macro-F1` `low-resource languages`</sub>

</td>
</tr>
</table>

Every repo has the code, the exact command to rerun it, the full results, and a section on what did **not** work.

---

### 📱 Apps I have shipped

| App | What I built | Stack |
|---|---|---|
| [Hireanything customer app](https://play.google.com/store/apps/details?id=com.hireanythingapp.hireanythingapp) | Service discovery, booking flow, in-app payments | Flutter, GetX, REST |
| [Hireanything worker / vendor app](https://play.google.com/store/apps/details?id=com.hireanything.workerapp) | Onboarding, profiles, availability management | Flutter, GetX, REST |
| [QR Buddy staff app](https://play.google.com/store/apps/details?id=com.nxtdesigns.qrbuddy_apexv3) | Task lifecycle, real-time notifications | Flutter |
| [QR Buddy consumer app](https://play.google.com/store/apps/details?id=com.nxtdesigns.qrbudddy.qrbuddy_consumer_app) | QR-based service requests | Flutter |

<sub>Company code is private. Open-source side projects: [call_app_log](https://github.com/sumitk07/call_app_log) (Flutter, Cubit) · [TalkBit](https://github.com/sumitk07/TalkBit) (Flutter, Firebase chat) · [shopeasy-data-validation](https://github.com/sumitk07/shopeasy-data-validation) (SQL data migration testing)</sub>

---

### 🧰 Tools

**Research**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white">

**Apps and web**<br>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"> <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
