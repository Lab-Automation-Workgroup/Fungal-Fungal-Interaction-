A# Fungal-Fungal-Interaction-Abstarct
Fungi offer valuable solutions for various biotechnological applications, including enzymes for the food industry, bioactive metabolites for healthcare, and biocontrol organisms for agriculture. The current workflows for identifying biocontrol fungi typically rely on subjective visual observation of the strains’ performance, rendering the process time-consuming and challenging to reproduce. To tackle these challenges, we develop an AI-automated approach employing five deep learning models which are ViT, VGG16, ResNet50, DensNet121, and MobileNet-V2. Our approach is centered on analyzing standardized images of 96-well microtiter plates containing solid medium on which fungi-fungi challenge experiments are conducted. We use our approach to categorize the outcome of interactions between the plant pathogen *Fusarium graminarium* and individual isolates from a collection of 38,400 fungal strains. Our results strongly support the effectiveness of our approach, attaining a peak accuracy of 95.0% on the test data. Correspondingly, the macro average Precision, Recall, and F1-score during validation were and 92.4%, 94.1%, and 93.1%, respectively. To the best of our knowledge, this paper presents the first automated method for scoring *F. graminarium* – fungal interactions using deep learning, and the technique can easily be trained for other fungal species.



# Performance 
## Table
<img width="587" alt="image" src="https://github.com/mycoverse/fungal-fungal-Classification-/assets/41271921/525c9e62-91be-4dad-a645-87b63cb6132d">

## Boxplot
![image](https://github.com/mycoverse/fungal-fungal-Classification-/assets/41271921/5131b360-746b-45b0-aa69-9fb94fdd9bff)

## Training process of all models 
![image](https://github.com/mycoverse/fungal-fungal-Classification-/assets/41271921/ee54130d-7edd-4a9b-84f5-a94f66364a48)

# Software and Hardware
The code utilized in this study was implemented in Python and TensorFlow library version 2.15. The process of training the deep learning models was performed on Google Colab pro plus, using NVIDIA GPU A100-40G.
