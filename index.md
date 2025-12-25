# **AbjadStyleTransfer**: Shared Task on Authorship Style Transfer (Text Generation)

### Hosted with [AbjadNLP(2026)](https://wp.lancs.ac.uk/abjad/) at EACL 2026, Rabat, Morocco

## 1. Overview of the Shared Task
**AbjadStyleTransfer** focuses on **Authorship Style Transfer (Text Generation)** for languages that use the Arabic script, including **Modern Standard Arabic and Urdu**. The goal is to transform a formal input text into the style of a specified author while preserving semantics, with a strict focus on **literature**.

Unlike general text style analysis, Authorship Style Transfer (AST) aims to actively modify text to conform to a distinctive writing style. This shared task seeks to promote research in AST for Arabic-script languages, an area that remains relatively underdeveloped.

## 2. Motivation
Authorship style transfer has applications in education, cultural preservation, and content generation. The Arabic script is used by diverse languages with rich literary traditions. This task addresses challenges such as:
- **Linguistic diversity**: Covering MSA, Urdu, Persian, and Kurdish.
- **Complex Morphology**: Handling the rich morphology of these languages.
- **Style Preservation**: Capturing the nuances of literary styles.

## 3. Data
The dataset focuses on literature from prominent authors in the target languages.
- **Source**: Literary works (novels, essays, etc.).
- **Task**: Transform formal text into the style of these authors.

### Dataset Statistics (Example for MSA)
| Id | Author                  | Train | Test | Val |
|----|-------------------------|------:|-----:|----:|
|(1) | Ahmed Amin              | 2892  | 594  | 246 |
|(2) | Ahmed Taymour Pasha     |  804  | 142  |  53 |
|(3) | Ahmed Shawqi            |  596  |  46  |  58 |
|(4) | Ameen Rihani            | 1557  | 624  | 142 |
|(5) | Tharwat Abaza           |  755  | 191  |  90 |
|(6) | Gibran Khalil Gibran    |  748  | 240  |  30 |
|(7) | Jurji Zaydan            | 2762  | 562  | 326 |
|(8) | Hassan Hanafi           | 3735  |1002  | 548 |
|(9) | Robert Barr             | 2680  | 512  |  82 |
|(10)| Salama Moussa           |  984  | 282  | 119 |
|(11)| Taha Hussein            | 2371  | 534  | 253 |
|(12)| Abbas M. Al-Aqqad       | 1820  | 499  | 267 |
|(13)| Abdel Ghaffar Makawi    | 1520  | 464  | 396 |
|(14)| Gustave Le Bon          | 1515  | 358  | 150 |
|(15)| Fouad Zakaria           | 1771  | 294  | 125 |
|(16)| Kamel Kilani            |  399  | 109  |  25 |
|(17)| Mohamed H. Heikal       | 2627  | 492  | 260 |
|(18)| Naguib Mahfouz          | 1630  | 343  | 327 |
|(19)| Nawal El Saadawi        | 1415  | 382  | 295 |
|(20)| William Shakespeare     | 1236  | 358  | 238 |
|(21)| Yusuf Idris             | 1140  | 349  | 120 |

## 4. Task Description
### AbjadStyleTransfer
- **Goal**: Transform a formal input text into the style of a specified author while preserving semantics.
- **Scope**: Literature in Modern Standard Arabic, Urdu, Persian, and Kurdish.
- **Evaluation**: 
    - **Automatic**: BLEU, chrF, Style Classification Accuracy.
    - **Human**: Fluency, Semantic Preservation, Style Intensity.

## 5. Tentative Timeline
- **June 10, 2025**: Release of training data  
- **July 20, 2025**: Release of test data  
- **July 25, 2025**: End of evaluation cycle (test submissions close)  
- **July 30, 2025**: Final results released  
- **August 22, 2025**: Shared task papers due date  
- **August 25, 2025**: Notification of acceptance  
- **September 5, 2025**: Camera-ready versions due  
- **November 5–9, 2025**: Main Conference

## 6. Organizers’ Details
- **Shadi Abudalfa**, King Fahd University of Petroleum & Minerals  
- **Saad Ezzini**, King Fahd University of Petroleum & Minerals  
- **Ahmed Abdelali**, HUMAIN  
- **Salima Lamsiyah**, University of Luxembourg  
- **Hamzah Luqman**, King Fahd University of Petroleum & Minerals  
- **Mustafa Jarrar**, Hamad Bin Khalifa University / Birzeit University  
- **Mo El-Haj**, VinUniversity  
- **Abdelkader Elmahdaouy**, Mohammed VI Polytechnic University  
- **Hamza Alami**, Sidi Mohamed Ben Abdellah University  
- **Abdessamad Benlahbib**, Sidi Mohamed Ben Abdellah University  
- **Salmane Chafik**, Mohammed VI Polytechnic University  

## 7. Participation Guidelines
- For participation guidelines, please refer to [Participation Guidelines](guidelines.md).
- Comprehensive instructions for preparing and submitting your paper(s) are available at [Paper Submission Guidelines](PAPER.md).

## References
1. Hu et al. “Text style transfer: A review and experimental evaluation.” _ACM SIGKDD Explorations Newsletter_, 24(1), 2022.  
2. Shao et al. “Authorship style transfer with inverse transfer data augmentation.” _AI Open_, 5, 2024.
3. Patel et al. “Low-Resource Authorship Style Transfer: Can Non-Famous Authors Be Imitated?” _arXiv preprint arXiv:2212.08986_, 2022.  
4. Horvitz et al. “TinyStyler: Efficient Few-Shot Text Style Transfer with Authorship Embeddings.” _arXiv preprint arXiv:2406.15586_, 2024.  

---

### Logistics and Support
- **Website Hosting**: GitHub Pages
- **Submission System**: Codabench
- **Communication Channels**:
  - Slack workspace
  - Mailing list
  - GitHub repository
- **Regular updates and participant support**

### Stay Updated
- Official **GitHub Repository**: https://github.com/ezzini/AraGenEval
- Join our [Slack community](https://join.slack.com/t/arabicnlp2025-oqe5144/shared_invite/zt-39zsj6k6o-LP09lFRhLNuuHzkyahNRxw)

### Announcements and Updates
- The final phase will begin on July 20, 2025 (UTC-12h) and will run for 5 days, ending on July 25, 2025 (UTC-12h). During this time, each team must submit their predictions on the test set (not the validation set) via the Codabench system. Only submissions made within this timeframe will be considered as official contributions when submitting your papers to the OpenReview system.
- The main content of your paper should not exceed 4 pages. There is no page limit on appendices and references; these sections are excluded from the 4-page limit.
  
### Anti-Harassment policy
We uphold the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy), and participants in this shared task are encouraged to reach out with any concerns or questions to any of the shared task organizers.
