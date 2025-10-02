
<a id="T_DEF03274"></a>

# <span style="color:rgb(213,80,0)">Machine Learning for Biosciences</span>
<a id="H_053613DF"></a>


[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/163696-biosciences-machine-learning) or [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Machine-Learning&project=MachineLearningBiosciences.prj&file=README.mlx)

[![MATLAB Versions Tested](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FMathWorks-Teaching-Resources%2FBiosciences-Machine-Learning%2Frelease%2FImages%2FTestedWith.json)](https://MathWorks-Teaching-Resources.github.io/Biosciences-Machine-Learning)

**Curriculum Module**

_Created with R2025a. Compatible with R2025a and later releases._

# Information

This curriculum module contains interactive [MATLAB® live scripts](https://www.mathworks.com/products/matlab/live-editor.html) that introduces basic machine learning algorithms  and apply them to biological datasets .

<a id="H_F00D98E4"></a>

## Background

You can use these live scripts as demonstrations in lectures, class activities, or interactive assignments outside class. This module covers machine learning applied to various biosciences datasets. 


The instructions inside the live scripts will guide you through the exercises and activities. Get started with each live script by running it one section at a time. To stop running the script or a section midway (for example, when an animation is in progress), use the <img src="Images/EndIcon.png" width="19" alt="EndIcon.png"> Stop button in the **RUN** section of the **Live Editor** tab in the MATLAB Toolstrip.

## Contact Us

Contact the [MathWorks Educator Content Development Team](mailto:onlineteaching@mathworks.com) if you would like to provide feedback, or if you have a question.

<a id="H_30BC7141"></a>

## Prerequisites

This module assumes basic MATLAB® knowledge and we recommend that all students take the [MATLAB Onramp](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) before continuing if they have not already. 

<a id="H_330E72C3"></a>

## Getting Started
### Accessing the Module
### **On MATLAB Online:**

Use the [<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/biosciences-machine-learning&project=MachineLearningBiosciences.prj)  link to download the module. You will be prompted to log in or create a MathWorks account. The project will be loaded, and you will see an app with several navigation options to get you started.

### **On Desktop:**

Download or clone this repository. Open MATLAB, navigate to the folder containing these scripts and double\-click on [MachineLearningBiosciences.prj](<matlab: openProject("MachineLearningBiosciences.prj")>) . It will add the appropriate files to your MATLAB path and open an app that asks you where you would like to start. 


Ensure you have all the required products ([listed below](#H_E850B4FF)) installed. If you need to include a product, add it using the Add\-On Explorer. To install an add\-on, go to the **Home** tab and select  <img src="Images/AddOnsIcon.png" width="16" alt="AddOnsIcon.png"> **Add-Ons** > **Get Add-Ons**. 

<a id="H_E850B4FF"></a>

## Products

MATLAB® is used throughout. Tools from the the [Statistics and Machine Learning Toolbox](https://www.mathworks.com/products/statistics.html)™ , [Deep Learning Toolbox](https://www.mathworks.com/help/deeplearning/index.html?searchHighlight=deeplearningtoolbox&s_tid=srchtitle_support_results_1_deeplearningtoolbox)™ are used frequently as well.

-  MATLAB® 
-  Deep Learning Toolbox™ 
-  Statistics and Machine Learning Toolbox™ 
<a id="H_577C7603"></a>

# Scripts
<a id="TMP_3070"></a>

## [**An Overview of Machine Learning for Science and Engineering**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Machine-Learning&project=MachineLearningBiosciences.prj&file=Scripts/IntrotoMachineLearning.mlx) 
||||
| :-- | :-- | :-- |
| <img src="Images/image_3.png" width="171" alt="image_3.png"> <br>  | **In this script, students will...** <br> $\bullet$ explain the primary goal of machine learning. <br> $\bullet$ distinguish between supervised and unsupervised learning. <br> $\bullet$ describe the key steps in a typical machine learning workflow. <br>  | **Academic disciplines** <br> $\bullet$ Biosciences <br> $\bullet$ Biology <br> $\bullet$ AI | Machine Learning <br> $\bullet$ Engineering <br>   |

<a id="TMP_41f4"></a>

## [**Unsupervised Learning**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Machine-Learning&project=MachineLearningBiosciences.prj&file=Scripts/UnsupervisedLearning.mlx) 
||||
| :-- | :-- | :-- |
| <img src="Images/image_4.png" width="141" alt="image_4.png"> <br>  | **In this script, students will...** <br> $\bullet$ apply Principal Component Analysis (PCA) to reduce dimensions of biosciences data. <br> $\bullet$ use k\-means clustering to identify natural groupings in unlabeled data.  <br> $\bullet$ evaluate clustering performance using confusion matrices.  <br>  | **Academic disciplines** <br> $\bullet$ Biosciences <br> $\bullet$ Biology <br> $\bullet$ AI | Machine Learning <br>   |

<a id="TMP_1fde"></a>

## [**Supervised Learning: Classification**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Machine-Learning&project=MachineLearningBiosciences.prj&file=Scripts/SupervisedLearningClassification.mlx) 
||||
| :-- | :-- | :-- |
| <img src="Images/image_5.png" width="171" alt="image_5.png"> <br>  | **In this script, students will...** <br> $\bullet$ train and evaluate models to classify disease using supervised learning. <br> $\bullet$ assess model performance with accuracy, confusion matrices, and ROC curves. <br> $\bullet$ improve accuracy using feature selection, PCA, and cost weighting. <br>  | **Academic disciplines** <br> $\bullet$ Biosciences <br> $\bullet$ Biology <br> $\bullet$ AI | Machine Learning <br>   |

<a id="TMP_245a"></a>

## [**Supervised Learning: Regression**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Machine-Learning&project=MachineLearningBiosciences.prj&file=Scripts/SupervisedLearningRegression.mlx) 
||||
| :-- | :-- | :-- |
| <img src="Images/image_6.png" width="171" alt="image_6.png"> <br>  | **In this script, students will...** <br> $\bullet$ use supervised learning to train and evaluate regression models that predict mollusk age. <br> $\bullet$ evaluate and compare models using statistical performance metrics such as accuracy, confusion matrices, and RMSE. <br> $\bullet$ apply machine learning in biosciences. <br>  | **Academic disciplines** <br> $\bullet$ Biosciences <br> $\bullet$ AI | Machine Learning <br>   |

<a id="TMP_18d1"></a>

## [**Unsupervised Learning Problem Set**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Machine-Learning&project=MachineLearningBiosciences.prj&file=Scripts/UnsupervisedLearningPS.mlx) 
||||
| :-- | :-- | :-- |
| <img src="Images/image_7.png" width="171" alt="image_7.png"> <br>  | **In this script, students will...** <br> $\bullet$ apply unsupervised learning to a cancer cell dataset. <br>  | **Academic disciplines** <br> $\bullet$ Biosciences <br> $\bullet$ Biology <br> $\bullet$ AI | Machine Learning <br>   |

<a id="H_F61733D7"></a>

# License

The license for this module is available in the [LICENSE.md](./LICENSE.md).

# Related Courseware Modules
<a id="H_868F5748"></a>

## [Machine Learning Methods: Clustering](https://www.mathworks.com/matlabcentral/fileexchange/135381-machine-learning-methods-clustering) 
|||
| :-- | :-- |
| <img src="Images/image_8.png" width="161" alt="image_8.png"> <br>  | **Available on:** <br> [<img src="Images/OpenInFX.png" width="91" alt="OpenInFX.png">](https://www.mathworks.com/matlabcentral/fileexchange/135381-machine-learning-methods-clustering)  <br> [<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/fileexchange/v1?id=135381&project=MLMethodsClustering.prj)  <br> [GitHub](https://github.com/MathWorks-Teaching-Resources/Machine-Learning-Methods-Clustering)  <br>   |

<a id="TMP_8603"></a>

## [ Biosciences: Working With Data](https://www.mathworks.com/matlabcentral/fileexchange/181586-biosciences-working-with-data?s_tid=srchtitle_site_search_4_biosciences) 
|||
| :-- | :-- |
| <img src="Images/image_11.png" width="161" alt="image_11.png"> <br>  | **Available on:** <br> [<img src="Images/OpenInFX.png" width="91" alt="OpenInFX.png">](https://www.mathworks.com/matlabcentral/fileexchange/181586-biosciences-working-with-data?s_tid=srchtitle_site_search_4_biosciences)  <br> [<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Working-With-Data&file=S1_Introduction.mlx)  <br> [GitHub](https://github.com/MathWorks-Teaching-Resources/Biosciences-Working-With-Data)  <br>   |

<a id="TMP_8603"></a>

## [ Biosciences: Genetics](https://www.mathworks.com/matlabcentral/fileexchange/163706-biosciences-genetics?s_tid=srchtitle_site_search_1_biosciences) 
|||
| :-- | :-- |
| <img src="Images/image_14.png" width="161" alt="image_14.png"> <br>  | **Available on:** <br> [<img src="Images/OpenInFX.png" width="91" alt="OpenInFX.png">](https://www.mathworks.com/matlabcentral/fileexchange/163706-biosciences-genetics?s_tid=srchtitle_site_search_1_biosciences)  <br> [<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Biosciences-Working-With-Data&file=S1_Introduction.mlx)  <br> [GitHub](https://github.com/MathWorks-Teaching-Resources/Biosciences-Genetics)  <br>   |


Or feel free to explore our other [modular courseware content](https://www.mathworks.com/matlabcentral/fileexchange/?q=tag%3A%22courseware+module%22&sort=downloads_desc_30d).

# Educator Resources
-  [Educator Page](https://www.mathworks.com/academia/educators.html) 
<a id="H_0FA5DA18"></a>

# Contribute 

Looking for more? Find an issue? Have a suggestion? Please contact the [MathWorks Educator Content Development Team](mailto:%20onlineteaching@mathworks.com). If you want to contribute directly to this project, you can find information about how to do so in the [CONTRIBUTING.md](./CONTRIBUTING.md) page on GitHub.


 *©* Copyright 2025 The MathWorks, Inc


