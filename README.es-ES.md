<div align="center">

<img src="assets/banner.svg" alt="Awesome Sign-Language Processing Banner" width="100%"/>

<br/>
<br/>

🚀 **La colección más completa y actualizada de recursos de Procesamiento de Lenguas de Señas en internet.**<br/>
Modelos · Datasets · Herramientas · Investigación · Empresas

</div>

---

## 📑 Tabla de Contenidos

<table>
<tr>
<td width="50%" valign="top">

- [🏢 Organizaciones Clave](#-key-organizations)
- [🤖 Modelos Estado del Arte](#-state-of-the-art-models)
- [🏆 Benchmarks y Tablas de Clasificación](#-benchmarks--leaderboards)
- [📊 Datasets](#-datasets)
- [🔧 Herramientas y Librerías Esenciales](#-essential-tools--libraries)
- [📄 Artículos Populares](#-popular-papers)
- [✂️ Segmentación de Lenguas de Señas](#-sign-language-segmentation)
- [🧩 Aumentación de Lenguas de Señas](#-sign-language-augmentation)
- [🪧 Sistemas de Notación](#-notation-systems)
- [📱 Despliegue en Edge y Móvil](#-edge--mobile-deployment)
- [🤝 Ética y Co-Diseño Comunitario](#-ethics--community-co-design)
- [🏁 Competiciones y Talleres](#-competitions--workshops)

</td>
<td width="50%" valign="top">

- [🧭 Estimación, Extracción y Procesamiento de Pose](#-pose-estimation-extraction-and-processing)
- [🔤 Proyectos de Seña a Texto](#-sign-to-text-projects)
- [👐 Proyectos de Texto a Seña](#-text-to-sign-projects)
- [🧍 Conversión de Pose a Avatar](#-pose-to-avatar-conversion)
- [🎓 Tutoriales y Recursos de Aprendizaje](#-tutorials--learning-resources)
- [🏛️ Instituciones de Investigación](#-research-institutions)
- [🏭 Empresas y Startups](#-companies--startups)
- [🌍 Recursos de Aprendizaje por Idioma](#-learning-resources-by-language)

</td>
</tr>
</table>


## 🏢 Organizaciones Clave

> Laboratorios de investigación, universidades y grupos comunitarios que dan forma al Procesamiento de Lenguas de Señas.


| Organización | Categoría | Enfoque | Contribuciones Clave | Enlace |
|:---|:---|:---|:---|:---:|
| AraSLP Lab | Lab de Investigación | Tecnologías de lengua de señas árabe | Investigación en reconocimiento, traducción y generación; construye datasets anotados, modelos de reconocimiento robustos y marcos de traducción end-to-end | [Sitio](https://hamzah-luqman.github.io/AraSLP/index.html) |
| World Federation of the Deaf | Organización de Defensa Global | Derechos de las personas sordas y acceso a la lengua de señas | Federación internacional que aboga por la igualdad de derechos, la accesibilidad, el reconocimiento legal y el uso de la lengua de señas en todo el mundo | [Sitio](https://wfdeaf.org/) |


---

## 🤖 Modelos Estado del Arte

> Modelos fundamentales para reconocimiento, traducción, generación, recuperación y comprensión unificada de lenguas de señas.

| Modelo | Categoría | Tarea | Características Clave | Enlace |
|:---|:---|:---|:---|:---:|
| Uni-Sign | Unificado | Comprensión | Modelado unificado a gran escala | [Código](https://github.com/ZechengLi19/Uni-Sign) |
| SignBERT | Reconocimiento | ISLR | Pre-entrenamiento consciente del modelo de mano | [Artículo](https://openaccess.thecvf.com/content/ICCV2021/html/Hu_SignBERT_Pre-Training_of_Hand-Model-Aware_Representation_for_Sign_Language_Recognition_ICCV_2021_paper.html) |
| BEST | Reconocimiento | ISLR | Pre-entrenamiento BERT con tokenización acoplada | [Artículo](https://ojs.aaai.org/index.php/AAAI/article/view/25470) |
| CVT-SLR | Reconocimiento | CSLR | Alineación visual-textual contrastiva | [Código](https://github.com/binbinjiang/CVT-SLR) |
| C2SLR | Reconocimiento | CSLR | Reconocimiento continuo mejorado por consistencia | [Artículo](https://openaccess.thecvf.com/content/CVPR2022/html/Zuo_C2SLR_Consistency-Enhanced_Continuous_Sign_Language_Recognition_CVPR_2022_paper.html) |
| Sign2GPT | Traducción | SLT | Traducción libre de glosas impulsada por LLM | [Código](https://github.com/ryanwongsa/Sign2GPT/tree/main) |
| SLTUNET | Traducción | SLT | Modelo de traducción unificado | [Código](https://github.com/bzhangGo/sltunet) |
| T2S-GPT | Producción | SLP | Producción autorregresiva de texto a seña | [Proyecto](https://t2sgpt-demo.yinaoxiong.cn/) |
| SignGen | Producción | SLP | Generación latente por difusión end-to-end | [Código](https://github.com/mingtiannihao/SignGen) |
| SignCLIP | Recuperación | SLR | Representación contrastiva texto-seña | [Código](https://github.com/J22Melody/fairseq/tree/main/examples/MMPT) |

---

## 🏆 Benchmarks y Tablas de Clasificación

> Recursos de evaluación estandarizados para tareas de lengua de señas a través de diversos datasets, idiomas y modalidades.

| Benchmark | Área de Tarea | Descripción | Métrica(s) | Enlace |
|:---|:---|:---|:---|:---:|
| WLASL | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión Top-1 / Top-5 | [Enlace](https://dxli94.github.io/WLASL/) |
| MSASL | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión Top-1 / Top-5 | [Enlace](https://www.microsoft.com/en-us/research/project/ms-asl/) |
| NMFs-CSL | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión | [Enlace](https://ustc-slr.github.io/datasets/2020_nmfs_csl/) |
| SLR500 | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión | [Enlace](http://home.ustc.edu.cn/~hagjie/) |
| Slovo | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión | [Enlace](https://github.com/hukenovs/slovo) |
| ASL Citizen | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión | [Enlace](https://www.microsoft.com/en-us/research/project/asl-citizen/) |
| Auslan-Daily | ISLR | Benchmark de reconocimiento de señas aisladas | Precisión | [Enlace](https://uq-cvlab.github.io/Auslan-Daily-Dataset/) |
| Phoenix-2014 | CSLR | Benchmark de reconocimiento de señas continuo | WER | [Enlace](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX/) |
| Phoenix-2014T | CSLR / SLT | Benchmark de reconocimiento y traducción continua | WER / BLEU / ROUGE | [Enlace](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/) |
| CSL-Daily | CSLR / SLT | Benchmark de reconocimiento y traducción continua | WER / BLEU | [Enlace](http://home.ustc.edu.cn/~zhouh156/dataset/csl-daily/) |
| TVB-HKSL-News | CSLR / SLT | Benchmark de reconocimiento y traducción continua | WER / BLEU | [Enlace](https://tvb-hksl-news.github.io/) |
| OpenASL | SLT | Benchmark de traducción de lengua de señas | BLEU / ROUGE | [Enlace](https://github.com/chevalierNoir/OpenASL/) |
| How2Sign | SLT | Benchmark de traducción de lengua de señas | BLEU / ROUGE | [Enlace](https://how2sign.github.io/) |
| BOBSL | SLT | Benchmark de traducción a gran escala | BLEU / ROUGE | [Enlace](https://www.robots.ox.ac.uk/~vgg/data/bobsl/) |
| Auslan-Daily Communication | SLT | Benchmark de traducción | BLEU / ROUGE | [Enlace](https://uq-cvlab.github.io/Auslan-Daily-Dataset/) |
| Auslan-Daily News | SLT | Benchmark de traducción | BLEU / ROUGE | [Enlace](https://uq-cvlab.github.io/Auslan-Daily-Dataset/) |

---

## 📊 Datasets

> Conjuntos de datos que cubren múltiples lenguas de señas, tamaños, formatos y modalidades.

| Dataset | Modalidad | Lengua de Señas | Tamaño / Escala | Enlace |
|:---|:---|:---|:---|:---:|
| YouTube-ASL | Video | ASL | Corpus de pre-entrenamiento a gran escala | [Enlace](https://github.com/google-research/google-research/tree/master/youtube_asl) |
| CSL-News | Video | CSL | Corpus de pre-entrenamiento a gran escala | [Enlace](https://huggingface.co/datasets/ZechengLi19/CSL-News) |
| YouTube-SL-25 | Video | Multi-idioma | Corpus de pre-entrenamiento a gran escala | [Enlace](https://github.com/google-research/google-research/tree/master/youtube_sl_25) |
| WLASL | Video | ASL | Dataset de señas aisladas | [Enlace](https://dxli94.github.io/WLASL/) |
| MSASL | Video | ASL | Dataset de señas aisladas | [Enlace](https://www.microsoft.com/en-us/research/project/ms-asl/) |
| NMFs-CSL | Video | CSL | Dataset de señas aisladas | [Enlace](https://ustc-slr.github.io/datasets/2020_nmfs_csl/) |
| SLR500 | Video | CSL | Dataset de señas aisladas | [Enlace](http://home.ustc.edu.cn/~hagjie/) |
| Slovo | Video | RSL | Dataset de señas aisladas | [Enlace](https://github.com/hukenovs/slovo) |
| ASL Citizen | Video | ASL | Dataset de señas aisladas | [Enlace](https://www.microsoft.com/en-us/research/project/asl-citizen/) |
| Auslan-Daily | Video | Auslan | Dataset de señas aisladas | [Enlace](https://uq-cvlab.github.io/Auslan-Daily-Dataset/) |
| Phoenix-2014 | Video | DGS | Dataset de señas continuo | [Enlace](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX/) |
| Phoenix-2014T | Video | DGS | Dataset de señas continuo + traducción | [Enlace](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/) |
| CSL-Daily | Video | CSL | Dataset de señas continuo + traducción | [Enlace](http://home.ustc.edu.cn/~zhouh156/dataset/csl-daily/) |
| TVB-HKSL-News | Video | HKSL | Dataset de señas continuo + traducción | [Enlace](https://tvb-hksl-news.github.io/) |
| OpenASL | Video | ASL | Dataset de traducción | [Enlace](https://github.com/chevalierNoir/OpenASL/) |
| How2Sign | Video + Multimodal | ASL | Dataset de traducción | [Enlace](https://how2sign.github.io/) |
| BOBSL | Video | BSL | Dataset de traducción | [Enlace](https://www.robots.ox.ac.uk/~vgg/data/bobsl/) |
| Auslan-Daily Communication | Video | Auslan | Dataset de traducción | [Enlace](https://uq-cvlab.github.io/Auslan-Daily-Dataset/) |
| Auslan-Daily News | Video | Auslan | Dataset de traducción | [Enlace](https://uq-cvlab.github.io/Auslan-Daily-Dataset/) |

---

## 🔧 Herramientas y Librerías Esenciales

> Herramientas prácticas para preprocesamiento, anotación, visualización, extracción de pose y flujos de trabajo de lengua de señas.

| Herramienta / Librería | Categoría | Caso de Uso | Plataforma | Enlace |
|:---|:---|:---|:---|:---:|
| react-pose-viewer | Visualización de Pose | Ver e inspeccionar secuencias de pose | Web | [Código](https://github.com/bipinkrish/react-pose-viewer) |
| pose-format | Procesamiento de Pose | Formato de archivo y kit de herramientas para leer, escribir, normalizar, aumentar, visualizar e importar datos de pose | Python / JavaScript | [Código](https://github.com/sign-language-processing/pose) |
| pose-dart | Procesamiento de Pose | Trabajar con datos de pose | Dart | [Código](https://github.com/bipinkrish/pose-dart) |
| vscode-pose | Extensión de VS Code | Flujo de trabajo de edición relacionado con la pose | VS Code | [Código](https://github.com/bipinkrish/vscode-pose) |
| multimodalhugs | Herramientas Multimodales | Experimentación multimodal | Desconocido | [Código](https://github.com/GerrySant/multimodalhugs) |

---

## 📄 Artículos Populares

> Artículos organizados cronológica y por tareas según el problema que resuelven.

| Artículo | Año | Área de Tarea | Sede / Tipo | Enlace Clave |
|:---|:---:|:---|:---|:---:|
| Deep Sign: Hybrid CNN-HMM for Continuous Sign Language Recognition | 2016 | CSLR | BMVC | [Artículo](https://bmva-archive.org.uk/bmvc/2016/papers/paper136/index.html) |
| Iterative Reference Driven Metric Learning for Signer Independent Isolated Sign | 2016 | ISLR | ECCV | [Artículo](http://vipl.ict.ac.cn/uploadfile/upload/2018112115134267.pdf) |
| SubUNets: End-To-End Hand Shape and Continuous Sign Language Recognition | 2017 | CSLR | ICCV | [Artículo](https://openaccess.thecvf.com/content_iccv_2017/html/Camgoz_SubUNets_End-To-End_Hand_ICCV_2017_paper.html) |
| Recurrent Convolutional Neural Networks for Continuous Sign Language Recognition by Staged Optimization | 2017 | CSLR | CVPR | [Artículo](https://openaccess.thecvf.com/content_cvpr_2017/html/Cui_Recurrent_Convolutional_Neural_CVPR_2017_paper.html) |
| Deep Sign: Enabling Robust Statistical Continuous Sign Language Recognition via Hybrid CNN-HMMs | 2018 | CSLR | IJCV | [Artículo](https://link.springer.com/article/10.1007/s11263-018-1121-3) |
| Neural Sign Language Translation | 2018 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content_cvpr_2018/html/Camgoz_Neural_Sign_Language_CVPR_2018_paper.html) |
| GestureGAN for Hand Gesture-to-Gesture Translation in the Wild | 2018 | SLP | ACM MM | [Artículo](https://dl.acm.org/doi/abs/10.1145/3240508.3240704) |
| Skeleton-Based Gesture Recognition Using Several Fully Connected Layers with Path Signature Features and Temporal Transformer Module | 2019 | ISLR | AAAI | [Artículo](https://ojs.aaai.org/index.php/AAAI/article/view/4878) |
| Iterative Alignment Network for Continuous Sign Language Recognition | 2019 | CSLR | CVPR | [Artículo](https://openaccess.thecvf.com/content_CVPR_2019/html/Pu_Iterative_Alignment_Network_for_Continuous_Sign_Language_Recognition_CVPR_2019_paper.html) |
| Weakly Supervised Learning with Multi-Stream CNN-LSTM-HMMs to Discover Sequential Parallelism in Sign Language Videos | 2019 | CSLR | TPAMI | [Artículo](https://ieeexplore.ieee.org/document/8691602/) |
| Transferring Cross-Domain Knowledge for Video Sign Language Recognition | 2020 | ISLR | CVPR | [Artículo](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Transferring_Cross-Domain_Knowledge_for_Video_Sign_Language_Recognition_CVPR_2020_paper.html) |
| BSL-1K: Scaling up co-articulated sign language recognition using mouthing cues | 2020 | ISLR | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1279_ECCV_2020_paper.php) |
| Word-level Deep Sign Language Recognition from Video: A New Large-scale Dataset and Methods Comparison | 2020 | ISLR | WACV | [Artículo](https://openaccess.thecvf.com/content_WACV_2020/html/Li_Word-level_Deep_Sign_Language_Recognition_from_Video_A_New_Large-scale_WACV_2020_paper.html) |
| FineHand: Learning Hand Shapes for American Sign Language Recognition | 2020 | ISLR | FG | [Artículo](https://ieeexplore.ieee.org/document/9320289) |
| Boosting Continuous Sign Language Recognition via Cross Modality Augmentation | 2020 | CSLR | ACM MM | [Artículo](https://dl.acm.org/doi/abs/10.1145/3394171.3413931) |
| Stochastic Fine-grained Labeling of Multi-state Sign Glosses for Continuous Sign Language Recognition | 2020 | CSLR | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2527_ECCV_2020_paper.php) |
| Fully Convolutional Networks for Continuous Sign Language Recognition | 2020 | CSLR | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/4763_ECCV_2020_paper.php) |
| Spatial-Temporal Multi-Cue Network for Continuous Sign Language Recognition | 2020 | CSLR | AAAI | [Artículo](https://ojs.aaai.org/index.php/AAAI/article/view/7001) |
| Sign Language Transformers: Joint End-to-end Sign Language Recognition and Translation | 2020 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content_CVPR_2020/html/Camgoz_Sign_Language_Transformers_Joint_End-to-End_Sign_Language_Recognition_and_Translation_CVPR_2020_paper.html) |
| TSPNet: Hierarchical Feature Learning via Temporal Semantic Pyramid for Sign Language Translation | 2020 | SLT | NeurIPS | [Artículo](https://proceedings.neurips.cc/paper_files/paper/2020/hash/8c00dee24c9878fea090ed070b44f1ab-Abstract.html) |
| Neural Sign Language Translation by Learning Tokenization | 2020 | SLT | FG | [Artículo](https://ieeexplore.ieee.org/document/9320278?denied=) |
| Neural Sign Language Synthesis: Words Are Our Glosses | 2020 | SLP | WACV | [Artículo](https://openaccess.thecvf.com/content_WACV_2020/papers/Zelinka_Neural_Sign_Language_Synthesis_Words_Are_Our_Glosses_WACV_2020_paper.pdf) |
| Adversarial Training for Multi-Channel Sign Language Production | 2020 | SLP | BMVC | [Artículo](https://arxiv.org/abs/2008.12405) |
| Progressive Transformers for End-to-End Sign Language Production | 2020 | SLP | ECCV | [Artículo](https://arxiv.org/pdf/2004.14874.pdf) |
| Text2Sign: Towards Sign Language Production Using Neural Machine Translation and Generative Adversarial Networks | 2020 | SLP | IJCV | [Artículo](https://link.springer.com/article/10.1007/s11263-019-01281-2#citeas) |
| Hand-Model-Aware Sign Language Recognition | 2021 | ISLR | AAAI | [Artículo](https://ojs.aaai.org/index.php/AAAI/article/view/16247) |
| Global-Local Enhancement Network for NMF-Aware Sign Language Recognition | 2021 | ISLR | TOMM | [Artículo](https://dl.acm.org/doi/10.1145/3436754) |
| Hand Pose Guided 3D Pooling for Word-level Sign Language Recognition | 2021 | ISLR | WACV | [Artículo](https://openaccess.thecvf.com/content/WACV2021/html/Hosain_Hand_Pose_Guided_3D_Pooling_for_Word-Level_Sign_Language_Recognition_WACV_2021_paper.html) |
| Pose-based Sign Language Recognition using GCN and BERT | 2021 | ISLR | WACVW | [Artículo](https://openaccess.thecvf.com/content/WACV2021W/HBU/html/Tunga_Pose-Based_Sign_Language_Recognition_Using_GCN_and_BERT_WACVW_2021_paper.html) |
| Skeleton Aware Multi-modal Sign Language Recognition | 2021 | ISLR | CVPRW | [Artículo](https://arxiv.org/pdf/2103.08833.pdf) |
| Sign Language Recognition via Skeleton-Aware Multi-Model Ensemble | 2021 | ISLR | arXiv | [Artículo](https://arxiv.org/pdf/2110.06161.pdf) |
| SignBERT: Pre-Training of Hand-Model-Aware Representation for Sign Language Recognition | 2021 | ISLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2021/html/Hu_SignBERT_Pre-Training_of_Hand-Model-Aware_Representation_for_Sign_Language_Recognition_ICCV_2021_paper.html) |
| Visual Alignment Constraint for Continuous Sign Language Recognition | 2021 | CSLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2021/html/Min_Visual_Alignment_Constraint_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html) |
| Self-Mutual Distillation Learning for Continuous Sign Language Recognition | 2021 | CSLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2021/html/Hao_Self-Mutual_Distillation_Learning_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html) |
| Spatial-Temporal Multi-Cue Network for Sign Language Recognition and Translation | 2021 | SLT | TMM | [Artículo](https://ieeexplore.ieee.org/document/9354538) |
| Conditional Sentence Generation and Cross-Modal Reranking for Sign Language Translation | 2021 | SLT | TMM | [Artículo](https://ieeexplore.ieee.org/document/9447976) |
| How2Sign: A Large-scale Multimodal Dataset for Continuous American Sign Language | 2021 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2021/html/Duarte_How2Sign_A_Large-Scale_Multimodal_Dataset_for_Continuous_American_Sign_Language_CVPR_2021_paper.html) |
| Improving Sign Language Translation with Monolingual Data by Sign Back-Translation | 2021 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Model-Aware_Gesture-to-Gesture_Translation_CVPR_2021_paper.html) |
| Skeleton-Aware Neural Sign Language Translation | 2021 | SLT | ACM MM | [Artículo](https://dl.acm.org/doi/abs/10.1145/3474085.3475577) |
| SimulSLT: End-to-End Simultaneous Sign Language Translation | 2021 | SLT | ACM MM | [Artículo](https://arxiv.org/abs/2112.04228) |
| Towards Fast and High-Quality Sign Language Production | 2021 | SLP | ACM MM | [Artículo](https://dl.acm.org/doi/10.1145/3474085.3475463) |
| Mixed SIGNals: Sign Language Production via a Mixture of Motion Primitives | 2021 | SLP | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2021/papers/Saunders_Mixed_SIGNals_Sign_Language_Production_via_a_Mixture_of_Motion_ICCV_2021_paper.pdf) |
| Model-Aware Gesture-to-Gesture Translation | 2021 | SLP | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2021/html/Hu_Model-Aware_Gesture-to-Gesture_Translation_CVPR_2021_paper.html) |
| Continuous 3D Multi-Channel Sign Language Production via Progressive Transformers and Mixture Density Networks | 2021 | SLP | IJCV | [Artículo](https://link.springer.com/article/10.1007/s11263-021-01457-9) |
| Signing Outside the Studio: Benchmarking Background Robustness for Continuous Sign Language Recognition | 2022 | CSLR | BMVC | [Artículo](https://bmvc2022.mpi-inf.mpg.de/322/) |
| Temporal Lift Pooling for Continuous Sign Language Recognition | 2022 | CSLR | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/160_ECCV_2022_paper.php) |
| Deep Radial Embedding for Visual Sequence Learning | 2022 | CSLR | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5670_ECCV_2022_paper.php) |
| C2SLR: Consistency-Enhanced Continuous Sign Language Recognition | 2022 | CSLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2022/html/Zuo_C2SLR_Consistency-Enhanced_Continuous_Sign_Language_Recognition_CVPR_2022_paper.html) |
| Prior Knowledge and Memory Enriched Transformer for Sign Language Translation | 2022 | SLT | ACL Findings | [Artículo](https://aclanthology.org/2022.findings-acl.297/) |
| Open-Domain Sign Language Translation Learned from Online Video | 2022 | SLT | EMNLP | [Artículo](https://aclanthology.org/2022.emnlp-main.427/) |
| Automatic Gloss-level Data Augmentation for Sign Language Translation | 2022 | SLT | LREC | [Artículo](https://aclanthology.org/2022.lrec-1.734.pdf) |
| A Simple Multi-Modality Transfer Learning Baseline for Sign Language Translation | 2022 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2022/html/Chen_A_Simple_Multi-Modality_Transfer_Learning_Baseline_for_Sign_Language_Translation_CVPR_2022_paper.html) |
| MLSLT: Towards Multilingual Sign Language Translation | 2022 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2022/html/Yin_MLSLT_Towards_Multilingual_Sign_Language_Translation_CVPR_2022_paper.html) |
| Two-Stream Network for Sign Language Recognition and Translation | 2022 | SLT | NeurIPS | [Artículo](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6cd3ac24cdb789beeaa9f7145670fcae-Abstract-Conference.html) |
| Sign Language Translation With Hierarchical Spatio-Temporal Graph Neural Network | 2022 | SLT | WACV | [Artículo](https://openaccess.thecvf.com/content/WACV2022/html/Kan_Sign_Language_Translation_With_Hierarchical_Spatio-Temporal_Graph_Neural_Network_WACV_2022_paper.html) |
| Sign Language Translation based on Transformers for the How2Sign Dataset | 2022 | SLT | Report | [Artículo](https://imatge.upc.edu/web/sites/default/files/pub/xCabot22.pdf) |
| Signing at Scale: Learning to Co-Articulate Signs for Large-Scale Photo-Realistic Sign Language Production | 2022 | SLP | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2022/html/Saunders_Signing_at_Scale_Learning_to_Co-Articulate_Signs_for_Large-Scale_Photo-Realistic_CVPR_2022_paper.html) |
| Sign Language Video Retrieval with Free-Form Textual Queries | 2022 | SLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2022/papers/Duarte_Sign_Language_Video_Retrieval_With_Free-Form_Textual_Queries_CVPR_2022_paper.pdf) |
| Isolated Sign Language Recognition based on Tree Structure Skeleton Images | 2023 | ISLR | CVPRW | [Artículo](https://arxiv.org/pdf/2304.05403.pdf) |
| Natural Language-Assisted Sign Language Recognition | 2023 | ISLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2023/html/Zuo_Natural_Language-Assisted_Sign_Language_Recognition_CVPR_2023_paper.html) |
| Human Part-wise 3D Motion Context Learning for Sign Language Recognition | 2023 | ISLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2023/papers/Lee_Human_Part-wise_3D_Motion_Context_Learning_for_Sign_Language_Recognition_ICCV_2023_paper.pdf) |
| BEST: BERT Pre-Training for Sign Language Recognition with Coupling Tokenization | 2023 | ISLR | AAAI | [Artículo](https://ojs.aaai.org/index.php/AAAI/article/view/25470) |
| Self-Supervised Representation Learning with Spatial-Temporal Consistency for Sign Language Recognition | 2023 | ISLR | TIP | [Artículo](https://arxiv.org/pdf/2406.10501) |
| AdaBrowse: Adaptive Video Browser for Efficient Continuous Sign Language Recognition | 2023 | CSLR | ACM MM | [Artículo](https://dl.acm.org/doi/10.1145/3581783.3611745) |
| CoSign: Exploring Co-occurrence Signals in Skeleton-based Continuous Sign Language Recognition | 2023 | CSLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2023/html/Jiao_CoSign_Exploring_Co-occurrence_Signals_in_Skeleton-based_Continuous_Sign_Language_Recognition_ICCV_2023_paper.html) |
| Improving Continuous Sign Language Recognition with Cross-Lingual Signs | 2023 | CSLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2023/html/Wei_Improving_Continuous_Sign_Language_Recognition_with_Cross-Lingual_Signs_ICCV_2023_paper.html) |
| C2ST: Cross-modal Contextualized Sequence Transduction for Continuous Sign Language Recognition | 2023 | CSLR | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_C2ST_Cross-Modal_Contextualized_Sequence_Transduction_for_Continuous_Sign_Language_Recognition_ICCV_2023_paper.html) |
| CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition with Variational Alignment | 2023 | CSLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) |
| Continuous Sign Language Recognition with Correlation Network | 2023 | CSLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2023/html/Hu_Continuous_Sign_Language_Recognition_With_Correlation_Network_CVPR_2023_paper.html) |
| Distilling Cross-Temporal Contexts for Continuous Sign Language Recognition | 2023 | CSLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2023/html/Guo_Distilling_Cross-Temporal_Contexts_for_Continuous_Sign_Language_Recognition_CVPR_2023_paper.html) |
| Self-Emphasizing Network for Continuous Sign Language Recognition | 2023 | CSLR | AAAI | [Artículo](https://ojs.aaai.org/index.php/AAAI/article/view/25164) |
| Prior-Aware Cross Modality Augmentation Learning for Continuous Sign Language Recognition | 2023 | CSLR | TMM | [Artículo](https://ieeexplore.ieee.org/document/10105511) |
| SLTUNET: A Simple Unified Model for Sign Language Translation | 2023 | SLT | ICLR | [Artículo](https://openreview.net/forum?id=EBS4C77p_5S) |
| Gloss-Free End-to-End Sign Language Translation | 2023 | SLT | ACL | [Artículo](https://aclanthology.org/2023.acl-long.722/) |
| Neural Machine Translation Methods for Translating Text to Sign Language Glosses | 2023 | SLT | ACL | [Artículo](https://aclanthology.org/2023.acl-long.700/) |
| Considerations for meaningful sign language machine translation based on glosses | 2023 | SLT | ACL | [Artículo](https://aclanthology.org/2023.acl-short.60/) |
| ISLTranslate: Dataset for Translating Indian Sign Language | 2023 | SLT | ACL Findings | [Artículo](https://aclanthology.org/2023.findings-acl.665/) |
| Cross-modality Data Augmentation for End-to-End Sign Language Translation | 2023 | SLT | EMNLP | [Artículo](https://arxiv.org/pdf/2305.11096.pdf) |
| YouTube-ASL: A Large-Scale, Open-Domain American Sign Language-English Parallel Corpus | 2023 | SLT | NeurIPS Datasets | [Artículo](https://proceedings.neurips.cc/paper_files/paper/2023/file/5c61452daca5f0c260e683b317d13a3f-Paper-Datasets_and_Benchmarks.pdf) |
| Sign Language Translation from Instructional Videos | 2023 | SLT | CVPRW | [Artículo](https://openaccess.thecvf.com/content/CVPR2023W/WiCV/papers/Tarres_Sign_Language_Translation_from_Instructional_Videos_CVPRW_2023_paper.pdf) |
| Gloss Attention for Gloss-free Sign Language Translation | 2023 | SLT | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2023/html/Yin_Gloss_Attention_for_Gloss-Free_Sign_Language_Translation_CVPR_2023_paper.html) |
| Gloss-free Sign Language Translation: Improving from Visual-Language Pretraining | 2023 | SLT | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2023/html/Zhou_Gloss-Free_Sign_Language_Translation_Improving_from_Visual-Language_Pretraining_ICCV_2023_paper.html) |
| CiCo: Domain-Aware Sign Language Retrieval via Cross-Lingual Contrastive Learning | 2023 | SLR | CVPR | [Artículo](https://arxiv.org/pdf/2303.12793.pdf) |
| SignBERT+: Hand-model-aware Self-supervised Pre-training for Sign Language Understanding | 2023 | Unificado | TPAMI | [Artículo](https://ieeexplore.ieee.org/document/10109128) |
| MASA: Motion-aware Masked Autoencoder with Semantic Alignment for Sign Language Recognition | 2024 | ISLR | TCSVT | [Artículo](https://arxiv.org/pdf/2405.20666) |
| Towards Online Continuous Sign Language Recognition and Translation | 2024 | CSLR | EMNLP | [Artículo](https://aclanthology.org/2024.emnlp-main.619.pdf) |
| Sign Language Translation with Sentence Embedding Supervision | 2024 | SLT | ACL | [Artículo](https://aclanthology.org/2024.acl-short.40.pdf) |
| Sign2GPT: Leveraging Large Language Models for Gloss-Free Sign Language Translation | 2024 | SLT | ICLR | [Artículo](https://openreview.net/forum?id=LqaEEs3UxU) |
| Conditional Variational Autoencoder for Sign Language Translation with Cross-Modal Alignment | 2024 | SLT | AAAI | [Artículo](https://arxiv.org/pdf/2312.15645.pdf) |
| Factorized Learning Assisted with Large Language Model for Gloss-free Sign Language Translation | 2024 | SLT | LREC-COLING | [Artículo](https://arxiv.org/pdf/2403.12556.pdf) |
| Towards Privacy-Aware Sign Language Translation at Scale | 2024 | SLT | ACL | [Artículo](https://arxiv.org/pdf/2402.09611) |
| LLMs are Good Sign Language Translators | 2024 | SLT | CVPR | [Artículo](https://arxiv.org/pdf/2404.00925) |
| Improving Gloss-free Sign Language Translation by Reducing Representation Density | 2024 | SLT | NeurIPS | [Artículo](https://openreview.net/forum?id=FtzLbGoHW2) |
| Scaling Sign Language Translation | 2024 | SLT | NeurIPS | [Artículo](https://openreview.net/forum?id=M80WgiO2Lb) |
| Visual Alignment Pre-training for Sign Language Translation | 2024 | SLT | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05894.pdf) |
| EvSign: Sign Language Recognition and Translation with Streaming Events | 2024 | SLT | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00799.pdf) |
| Sign Language Production with Latent Motion Transformer | 2024 | SLP | WACV | [Artículo](https://arxiv.org/pdf/2312.12917.pdf) |
| SignAvatar: Sign Language 3D Motion Reconstruction and Generation | 2024 | SLP | FG | [Artículo](https://arxiv.org/pdf/2405.07974) |
| Select and Reorder: A Novel Approach for Neural Sign Language Production | 2024 | SLP | LREC-COLING | [Artículo](https://arxiv.org/pdf/2404.11532) |
| T2S-GPT: Dynamic Vector Quantization for Autoregressive Sign Language Production from Text | 2024 | SLP | ACL | [Artículo](https://arxiv.org/pdf/2406.07119) |
| G2P-DDM: Generating Sign Pose Sequence from Gloss Sequence with Discrete Diffusion Model | 2024 | SLP | AAAI | [Artículo](https://arxiv.org/pdf/2208.09141) |
| SignGen: End-to-End Sign Language Video Generation with Latent Diffusion | 2024 | SLP | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06988.pdf) |
| A Simple Baseline for Spoken Language to Sign Language Translation with 3D Avatars | 2024 | SLP | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06499.pdf) |
| SEDS: Semantically Enhanced Dual-Stream Encoder for Sign Language Retrieval | 2024 | SLR | ACM MM | [Artículo](https://arxiv.org/pdf/2407.16394) |
| Uncertainty-aware Sign Language Video Retrieval with Probability Distribution Modeling | 2024 | SLR | ECCV | [Artículo](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06074.pdf) |
| SignCLIP: Connecting Text and Sign Language by Contrastive Learning | 2024 | SLR | EMNLP | [Artículo](https://arxiv.org/pdf/2407.01264) |
| VSNet: Focusing on the Linguistic Characteristics of Sign Language | 2025 | ISLR | CVPR | [Artículo](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_VSNet_Focusing_on_the_Linguistic_Characteristics_of_Sign_Language_CVPR_2025_paper.pdf) |
| Cross-Modal Consistency Learning for Sign Language Recognition | 2025 | ISLR | CVPRW | [Artículo](https://openaccess.thecvf.com/content/CVPR2025W/SLRTP/papers/Wu_Cross-Modal_Consistency_Learning_for_Sign_Language_Recognition_CVPRW_2025_paper.pdf) |
| KD-MSLRT: Lightweight Sign Language Recognition Model Based on Mediapipe and 3D to 1D Knowledge Distillation | 2025 | CSLR | AAAI | [Artículo](https://arxiv.org/pdf/2501.02321) |
| A Signer-Invariant Conformer and Multi-Scale Fusion Transformer for Continuous Sign Language Recognition | 2025 | CSLR | ICCVW | [Artículo](https://arxiv.org/pdf/2508.09372) |
| A Closer Look at Skeleton-based Continuous Sign Language Recognition | 2025 | CSLR | ICCVW | N/A |
| Beyond Gloss: A Hand-Centric Framework for Gloss-Free Sign Language Translation | 2025 | SLT | BMVC | [Artículo](https://arxiv.org/pdf/2507.23575) |
| Improvement in Sign Language Translation Using Text CTC Alignment | 2025 | SLT | COLING | [Artículo](https://arxiv.org/pdf/2412.09014) |
| Lost in Translation, Found in Context: Sign Language Translation with Contextual Cues | 2025 | SLT | CVPR | [Artículo](https://arxiv.org/pdf/2501.09754) |
| Multilingual Gloss-free Sign Language Translation: Towards Building a Sign Language Foundation Model | 2025 | SLT | ACL | [Artículo](https://arxiv.org/pdf/2505.24355) |
| SHuBERT: Self-Supervised Sign Language Representation Learning via Multi-Stream Cluster Prediction | 2025 | SLT | ACL | [Artículo](https://arxiv.org/pdf/2411.16765) |
| An Efficient Gloss-Free Sign Language Translation Using Spatial Configurations and Motion Dynamics with LLMs | 2025 | SLT | NAACL | [Artículo](https://aclanthology.org/2025.naacl-long.197.pdf) |
| SONAR-SLT: Multilingual Sign Language Translation via Language-Agnostic Sentence Embedding Supervision | 2025 | SLT | WMT | [Artículo](https://aclanthology.org/2025.wmt-1.18.pdf) |
| SAGE: Segment-Aware Gloss-Free Encoding for Token-Efficient Sign Language Translation | 2025 | SLT | ICCVW | [Artículo](https://www.arxiv.org/pdf/2507.09266) |
| Geo-Sign: Hyperbolic Contrastive Regularisation for Geometrically-Aware Sign-Language Translation | 2025 | SLT | NeurIPS | [Artículo](https://arxiv.org/pdf/2506.00129) |
| Sign-IDD: Iconicity Disentangled Diffusion for Sign Language Production | 2025 | SLP | AAAI | [Artículo](https://arxiv.org/pdf/2412.13609) |
| Discrete to Continuous: Generating Smooth Transition Poses from Sign Language Observations | 2025 | SLP | CVPR | [Artículo](https://arxiv.org/pdf/2411.16810) |
| SLRTP2025 Sign Language Production Challenge: Methodology, Results, and Future Work | 2025 | SLP | CVPRW | [Artículo](https://arxiv.org/pdf/2508.06951) |
| Signs as Tokens: A Retrieval-Enhanced Multilingual Sign Language Generator | 2025 | SLP | ICCV | [Artículo](https://openaccess.thecvf.com/content/ICCV2025/papers/Zuo_Signs_as_Tokens_A_Retrieval-Enhanced_Multilingual_Sign_Language_Generator_ICCV_2025_paper.pdf) |
| Scaling up Multimodal Pre-training for Sign Language Understanding | 2025 | Unificado | TPAMI | [Artículo](https://arxiv.org/pdf/2408.08544) |
| Uni-Sign: Toward Unified Sign Language Understanding at Scale | 2025 | Unificado | ICLR | [Artículo](https://openreview.net/pdf?id=0Xt7uT04cQ) |

---

## ✂️ Segmentación de Lenguas de Señas

> Recursos para segmentar señas, glosas, movimientos y límites temporales.

| Recurso | Subtarea | Tipo de Entrada | Tipo de Salida | Enlace |
|:---|:---|:---|:---|:---:|
| signlang-segmenter (24-mohamedyehia) | Segmentación de lengua de señas | Video | Unidades de seña segmentadas / límites | [Código](https://github.com/24-mohamedyehia/signlang-segmenter) |
| sign-segmentation (RenzKa) | Segmentación de lengua de señas | Video | Unidades de seña segmentadas / límites | [Código](https://github.com/RenzKa/sign-segmentation) |
| sign-segmentation (bricksdont) | Segmentación de lengua de señas | Video | Unidades de seña segmentadas / límites | [Código](https://github.com/bricksdont/sign-segmentation) |
---

## 🧩 Aumentación de Lenguas de Señas

> Técnicas y herramientas para mejorar la diversidad de los datos y la robustez del modelo.

| Recurso | Tipo de Aumentación | Modalidad de Entrada | Propósito | Enlace |
|:---|:---|:---|:---|:---:|
| signlang-augmenter | Aumentación de lengua de señas | Video / Pose | Flujos de trabajo de aumentación de datos | [Código](https://github.com/24-mohamedyehia/signlang-augmenter) |

---

## 🧭 Estimación, Extracción y Procesamiento de Pose

> Herramientas y tuberías para extraer, limpiar y utilizar datos de pose/puntos clave.

| Recurso | Etapa de Procesamiento | Entrada | Salida | Enlace |
|:---|:---|:---|:---|:---:|
| SL-TSSI-DenseNet | Transformación de imagen de esqueleto | Pose / Esqueleto | Clases de señas aisladas | [Código](https://github.com/davidlainesv/SL-TSSI-DenseNet) |
| SignAvatar | Reconstrucción de movimiento 3D | Video | Movimiento de seña 3D | [Proyecto](https://dongludeeplearning.github.io/SignAvatar.html) |
| G2P-DDM | Generación de glosa a pose | Glosa | Secuencia de poses | [Proyecto](https://slpdiffusier.github.io/g2p-ddm/) |
| MediaPipe | Extracción de pose / en dispositivo | Video | Puntos clave de pose 2D/3D | [Código](https://github.com/google-ai-edge/mediapipe) |
| OpenPose | Estimación de pose multipersona | Video | Puntos clave de pose 2D | [Código](https://github.com/CMU-Perceptual-Computing-Lab/openpose) |
| AlphaPose | Pose multipersona / tiempo real | Video | Puntos clave de pose 2D/3D | [Código](https://github.com/MVIG-SJTU/AlphaPose) |
| MMPose | Caja de herramientas de investigación para pose | Video | Puntos clave de pose 2D/3D | [Código](https://github.com/open-mmlab/mmpose) |
| Blaze2Cap_AI_Motioner | Tubería de pose→movimiento / subtitulado | Video | Salidas de movimiento / subtítulos | [Código](https://github.com/BlazeWild/Blaze2Cap_AI_Motioner) |
| EasyMocap | Mocap 3D multipersona | Video | Movimientos 3D / esqueletos | [Código](https://github.com/zju3dv/EasyMocap) |
| Monocular_3D_human | Reconstrucción 3D monocular | Video | Mallas humanas 3D / poses | [Código](https://github.com/zju3dv/Monocular_3D_human) |
| HybrIK | Estimación de pose 3D + IK | Video | Poses de articulaciones 3D / salida IK | [Código](https://github.com/jeffffffli/HybrIK) |
| sapiens (FacebookResearch) | Modelado del cuerpo humano | Datos 3D / mallas | Modelos humanos paramétricos / activos | [Código](https://github.com/facebookresearch/sapiens) |

---

## 🔤 Proyectos de Seña a Texto

> Proyectos de reconocimiento y traducción para entradas de lengua de señas aisladas y continuas.

| Proyecto | Tipo de Tarea | Modalidad de Entrada | Salida | Enlace |
|:---|:---|:---|:---|:---:|
| VAC_CSLR | Reconocimiento continuo | Video | Secuencia de glosas | [Código](https://github.com/ycmin95/VAC_CSLR) |
| Temporal-Lift-Pooling | Reconocimiento continuo | Video | Secuencia de glosas | [Código](https://github.com/hulianyuyy/Temporal-Lift-Pooling) |
| AdaBrowse | Reconocimiento continuo | Video | Secuencia de glosas | [Código](https://github.com/hulianyuyy/AdaBrowse) |
| CVT-SLR | Reconocimiento continuo | Video + Texto | Secuencia de glosas | [Código](https://github.com/binbinjiang/CVT-SLR) |
| CorrNet | Reconocimiento continuo | Video | Secuencia de glosas | [Código](https://github.com/hulianyuyy/CorrNet) |
| SLRT | Reconocimiento + Traducción | Video | Glosa / Texto | [Código](https://github.com/FangyunWei/SLRT) |
| TwoStreamNetwork | Reconocimiento + Traducción | Video + Pose | Glosa / Texto | [Código](https://github.com/FangyunWei/SLRT/tree/main/TwoStreamNetwork) |
| Uni-Sign | Comprensión unificada | Video + Texto | Salidas multi-tarea | [Código](https://github.com/ZechengLi19/Uni-Sign) |

---

## 👐 Proyectos de Texto a Seña

> Sistemas que generan salidas de lengua de señas a partir de texto, glosas o representaciones intermedias.

| Proyecto | Tipo de Tarea | Entrada | Salida | Enlace |
|:---|:---|:---|:---|:---:|
| ProgressiveTransformersSLP | Producción de señas | Texto / Glosa | Secuencia de pose / movimiento | [Código](https://github.com/BenSaunders27/ProgressiveTransformersSLP) |
| SANet | Traducción de señas | Video / Pose | Texto | [Código](https://github.com/SignLanguageCode/SANet) |
| SimulSLT | Traducción simultánea | Video | Texto | [Código](https://github.com/Robert0125/SimulSLT) |
| PET | Traducción de señas | Video | Texto | [Código](https://github.com/hugddygff/PET) |
| OpenASL | Traducción de dominio abierto | Video | Texto | [Código](https://github.com/chevalierNoir/OpenASL) |
| MLSLT SP-10 | Traducción multilingüe | Video | Texto | [Código](https://github.com/MLSLT/SP-10) |
| SLTUNET | Traducción de señas | Video | Texto | [Código](https://github.com/bzhangGo/sltunet) |
| GloFE | Traducción libre de glosas | Video | Texto | [Código](https://github.com/HenryLittle/GloFE) |
| ISLTranslate | Dataset de traducción + baseline | Video | Texto | [Código](https://github.com/Exploration-Lab/ISLTranslate) |
| GASLT | Traducción libre de glosas | Video | Texto | [Código](https://github.com/YinAoXiong/GASLT) |
| GFSLT-VLP | Traducción libre de glosas | Video | Texto | [Código](https://github.com/zhoubenjia/GFSLT-VLP) |
| Sign2GPT | Traducción libre de glosas basada en LLM | Video | Texto | [Código](https://github.com/ryanwongsa/Sign2GPT/tree/main) |
| CV-SLT | Traducción alineada cross-modal | Video | Texto | [Código](https://github.com/rzhao-zhsq/CV-SLT) |
| SSVP-SLT | Traducción consciente de la privacidad | Video | Texto | [Código](https://github.com/facebookresearch/ssvp_slt) |
| BeyondGloss | Traducción libre de glosas centrada en la mano | Video | Texto | [Código](https://github.com/elsobhano/BeyondGloss) |
| TextCTC-SLT | Traducción alineada por Text CTC | Video | Texto | [Código](https://github.com/Claire874/TextCTC-SLT) |
| Gloss-free-MLSLT | Traducción multilingüe libre de glosas | Video | Texto | [Código](https://github.com/Claire874/Gloss-free-MLSLT) |
| SpaMo | Traducción de movimiento espacial con LLMs | Video | Texto | [Código](https://github.com/eddie-euijun-hwang/SpaMo) |
| sonar-slt | Traducción multilingüe independiente del idioma | Video | Texto | [Código](https://github.com/DFKI-SignLanguage/sonar-slt) |
| Geo-Sign | Traducción consciente de la geometría | Video | Texto | [Código](https://github.com/ed-fish/Geo-Sign) |

---

## 🧍 Conversión de Pose a Avatar

> Proyectos que convierten poses o puntos clave en avatares de lengua de señas animados.

| Proyecto | Tipo de Conversión | Entrada | Avatar / Motor | Enlace |
|:---|:---|:---|:---|:---:|
| SignAvatar | Reconstrucción y generación de movimiento 3D | Video | Tubería de movimiento de cuerpo y mano 3D | [Proyecto](https://dongludeeplearning.github.io/SignAvatar.html) |
| T2S-GPT | Generación de movimiento de seña $\to$ texto | Texto | Movimiento de seña autorregresivo | [Proyecto](https://t2sgpt-demo.yinaoxiong.cn/) |
| G2P-DDM | Generador de difusión glosa $\to$ pose | Glosa | Generador de secuencias de poses | [Proyecto](https://slpdiffusier.github.io/g2p-ddm/) |
| SignGen | Generador de video $\to$ representación de seña | Tokens de seña latentes | Generador de video por difusión | [Código](https://github.com/mingtiannihao/SignGen) |
| SOKE | Generador mejorado por recuperación | Texto / Contexto de recuperación | Generación de señas basada en tokens | [Código](https://github.com/2000ZRL/SOKE) |
| UPose | Transferencia de pose / tubería de entrada de avatar | Pose | Poses listas para avatar | [Código](https://github.com/digitalworlds/UPose) |
| DigiHuman | Tubería de personajes / herramientas de avatar | Pose / Movimiento | Salidas de personajes 3D | [Código](https://github.com/Danial-Kord/DigiHuman) |
| upose (PyPI) | Paquete de Python para UPose | Pose | Utilidades / Paquete PyPI | [PyPI](https://pypi.org/project/upose/0.1.0/) |
| Real-Time-Motion-Transfer-to-a-3D-Avatar | Transferencia de movimiento en tiempo real | Video | Movimiento de avatar 3D | [Código](https://github.com/BlazeWild/Real-Time-Motion-Transfer-to-a-3D-Avatar) |
| mediapipe-to-mixamo | Puente MediaPipe $\to$ Mixamo | Pose | Movimiento listo para Mixamo | [Código](https://github.com/Nor-s/mediapipe-to-mixamo) |
| Anim | Utilidades de animación de avatares | Pose / Movimiento | Herramientas de animación | [Código](https://github.com/Nor-s/Anim) |
| Godot 3D mannequin demos | Ejemplos de integración de motor | Pose / Movimiento | Demos de avatares en Godot | [Código](https://github.com/gdquest-demos/godot-3d-mannequin) |
| Mixamo | Mercado de movimiento y retargeting | Paquetes de movimiento | Animaciones de avatar con retargeting | [Sitio](https://www.mixamo.com/#/?page=1&type=Motion%2CMotionPack) |
| mediapipe-avatar | Ayudantes MediaPipe $\to$ avatar | Pose | Herramientas de avatar | [Código](https://github.com/k03302/mediapipe-avatar) |
| Freemocap | Mocap sin marcadores para avatares | Video | Salidas de mocap 3D | [Código](https://github.com/freemocap/freemocap) |
| 3D_Character_Animation_Using_MediaPipe | Ejemplo de animación con MediaPipe | Video | Animación de personaje 3D | [Código](https://github.com/rihemar/3D_Character_Animation_Using_MediaPipe) |
| three.js + MediaPipe | Integración de avatar web | Pose | Demos de avatares en three.js | [Código](https://github.com/donguk071/three.js-with-mediapipe) |
| Kalidokit | Retargeting y rigging en tiempo de ejecución | Pose / Cara | Ayudantes de rig de avatar | [Código](https://github.com/yeemachine/kalidokit) |
| Mesekai | Framework de avatar / demo | Sistema de avatar | Activos y herramientas de avatar | [Código](https://github.com/Neleac/Mesekai) |
| VRM (what is VRM) | Descripción general del formato de avatar | — | Especificación / ecosistema de avatares VRM | [Info](https://avatar.viverse.com/avatar/what-is-vrm) |
| VRoid (Mobile / Studio) | Herramientas de autoría de avatares | — | Avatares VRoid / studio | [Móvil](http://vroid.com/en/mobile) / [Studio](https://vroid.com/en/studio) |
| TurboSquid | Mercado de activos 3D | — | Modelos y activos 3D | [Sitio](https://www.turbosquid.com/) |
| CWA Signing Avatars | Investigación / ejemplos de avatares | — | Recursos de avatares de lengua de señas | [Artículo / Sitio](https://vh.cmp.uea.ac.uk/index.php/CWA_Signing_Avatars) |
| three-gltf-viewer | Visor GLTF para avatares | GLTF | Visor de modelos de avatar | [Código](https://github.com/donmccurdy/three-gltf-viewer) |
| gltf-viewer (online) | Visualizador GLTF | GLTF | Vista previa de modelo | [Visor](https://gltf-viewer.donmccurdy.com/) |
| model-viewer (Google) | Componente web para modelos 3D | GLTF / USDZ | Renderizado de avatares web | [Código](https://github.com/google/model-viewer) |
---

## 🤟 Sistemas de Notación

> Sistemas de escritura y representaciones formales utilizadas para codificar la lengua de señas en forma simbólica.

| Sistema | Tipo | Qué representa | Uso Típico | Enlace |
|:---|:---|:---|:---|:---:|
| signwriting-flutter | Librería | Notación SignWriting | Apps de Flutter y renderizado | [Código](https://github.com/bipinkrish/signwriting-flutter) |
| signwriting-dart | Librería | Notación SignWriting | Apps de Dart y renderizado | [Código](https://github.com/bipinkrish/signwriting-dart) |

<!-- ---

## 🎓 Tutoriales & Recursos de Aprendizaje

> Material de aprendizaje práctico para investigadores, ingenieros y estudiantes.

| Recurso | Formato | Tema | Audiencia | Enlace |
|:---|:---|:---|:---|:---:|
| TBD | TBD | TBD | TBD | TBD | -->

<!-- ---

## 🏛️ Instituciones de Investigación

> Grupos académicos y de investigación que trabajan en el procesamiento de lengua de señas.

| Institución | Tipo | País / Región | Enfoque | Enlace |
|:---|:---|:---|:---|:---:|
| TBD | TBD | TBD | TBD | TBD | -->

---

## 🏭 Empresas y Startups

> Equipos comerciales y startups que crean tecnología de lengua de señas.

| Empresa | Categoría | Enfoque | Productos Notables | Enlace |
|:---|:---|:---|:---|:---:|
| Mind Rockets Inc | Tecnología Asistiva / IA | Avatares de Lengua de Señas y Herramientas de Accesibilidad | Avatares de Interpretación de Lengua de Señas, Barra de Herramientas de Accesibilidad | [Enlace](https://main.mindrocketsinc.com/) |
| Hand Talk | Tecnología Asistiva / IA | Traducción Automática de Lengua de Señas | App Hand Talk, Plugin Hand Talk | [Enlace](https://www.handtalk.me/) |

---

## 🏁 Competiciones y Talleres

> Tareas compartidas, desafíos de benchmark, hackathons y talleres de investigación.

| Evento | Tipo | Año | Enfoque | Enlace |
|:---|:---|:---:|:---|:---:|
| SLRTP2025 Sign Language Production Challenge | Desafío | 2025 | Producción de lengua de señas | [Artículo](https://arxiv.org/pdf/2508.06951) |

## 🤝 Contribuir

Las contribuciones se organizarán según las secciones anteriores. Cada recurso debe incluir una descripción corta, categoría de tarea y un enlace funcional una vez que se agregue el contenido.

---

## 📜 Licencia

Este trabajo está licenciado bajo una Licencia Creative Commons Attribution 4.0 International.

---

<div align="center">

**Si encuentras este recurso útil, por favor dale una ⭐**

Hecho para la comunidad de Procesamiento de Lenguas de Señas

</div>
