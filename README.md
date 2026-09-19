# EE 3040 Introduction to AI · Labs

Self-paced Colab labs for **EE 3040 Introduction to Artificial Intelligence**, College of Engineering, Prince Sattam bin Abdulaziz University.

Click a badge to open the lab in Google Colab, then choose **File → Save a copy in Drive** before you start, so your work is kept.

| Lab | What you practise | Open |
|---|---|---|
| 1 · Colab, Python, and your first look at data | Python basics, a first look at a table, the baseline, a checked AI assistant | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab01_First_Look_at_Data.ipynb) |
| 2 · From a messy table to a clean one | Missing readings, a current-transformer change, gaps, leaks, splitting by time, scaling, the pipeline | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab02_Clean_Table.ipynb) |
| 3 · Predicting a number: the load forecast | Linear regression, MAE, RMSE and R², columns from physics, Ridge and Lasso | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab03_Load_Forecast.ipynb) |
| 4 · Will it overload? A warning and an honest test | Classification, precision and recall, a threshold from costs, the test season | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab04_Overload_Warning.ipynb) |
| 5 · Trees, forests, and boosting | Information gain, over-fitting, random forests, honest feature importance, leaks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab05_Trees_and_Forests.ipynb) |
| 6 · Learning without labels | K-means, PCA, anomaly detection, reading the false alarms | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab06_Loggers_Without_Labels.ipynb) |
| 7 · Neural networks: seeing hot spots | Neurons, convolutions, a CNN in Keras, transfer learning, thermal images | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab07_Seeing_Hot_Spots.ipynb) |
| 8 · Language models at work | Next-word prediction, prompts, retrieval (RAG), agents and prompt injection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab08_Language_Models_at_Work.ipynb) |
| 9 · Who does it fail for? | Slices, bias and its sources, fixes and their costs, explaining one alert | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab09_Who_Does_It_Fail_For.ipynb) |
| 10 · From the notebook to the field | Packaging, input checks, silent failures, monitoring, the model card | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/assirims/ee3040-labs/blob/main/Lab10_Into_the_Field.ipynb) |

Each lab explains every step, checks your answers as you go (✅ or ❌ with a hint), and ends with a hand-in block to submit the way your instructor asks.
Every section has a folded **🌐 Arabic translation** under it; open it whenever it helps.

**Stuck, or solved something tricky?** Ask your classmates, and share what worked for you. Two lines from you can save a classmate an hour.

The course data in the labs is a declared simulation of a city electricity distribution network: an 11/0.4 kV transformer through five years of heat waves, an asset register of 900 transformers, 40 load loggers, thermal images from inspection rounds, and twelve transformers in two districts. It is generated inside each notebook, so there is nothing to download. Your project uses real data.

---

<div dir="rtl" align="right">

## لابات مقرر ٣٠٤٠ كهر مقدمة في الذكاء الاصطناعي

لابات Colab للتعلم الذاتي. اضغط زر **Open in Colab** بجانب اللاب في الجدول أعلاه، ثم اختر **File ثم Save a copy in Drive** قبل أن تبدأ حتى يُحفظ عملك.

- كل خطوة مشروحة داخل الدفتر، وكل تمرين يُصحَّح فوراً بـ ✅ أو ❌ مع تلميح.
- تحت كل قسم مربع مطوي **🌐 الترجمة العربية**؛ افتحه متى أفادك.
- في آخر كل لاب كتلة تسليم تسلّمها بالطريقة التي يطلبها أستاذك.

**واجهتك مشكلة، أو حللت مشكلة صعبة؟** اسأل زملاءك، وشاركهم ما نجح معك. سطران منك قد يوفّران ساعة على زميل.

بيانات المقرر في اللابات محاكاة معلنة لشبكة توزيع كهرباء في مدينة: محوّل 11/0.4 ك.ف عبر خمس سنوات من موجات الحر، وسجل أصول لـ900 محوّل، و40 مسجّل حمل، وصور حرارية من جولات التفتيش، واثنا عشر محوّلاً في منطقتين. تُولَّد داخل كل دفتر فلا تحتاج تنزيل أي ملف. أما مشروعك فيستخدم بيانات حقيقية.

</div>
