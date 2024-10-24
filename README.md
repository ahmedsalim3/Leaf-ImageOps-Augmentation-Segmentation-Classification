## Abstract

The evolution of deep learning models alongside advancements in image processing has led to groundbreaking solutions in addressing agricultural challenges, particularly in automating the detection of tomato plant diseases. This paper focuses on integrating advanced image segmentation techniques with state-of-the-art machine learning models to accurately identify disease classes in tomato plant leaves, enabling early diagnosis and effective crop management. The Segment Anything Model (SAM), designed for versatile segmentation tasks, aids in zero-shot image segmentation through “everything mode” and “input prompts mode” such as bounding boxes, polygons, or points. This study introduces a novel workflow utilizing HSV color range thresholds and OpenCV operations functioning as an additional input prompt to enhance SAM’s segmentation capabilities, addressing challenges related to variations in tomato leaf colors, shapes, and disease manifestations in the PlantVillage dataset. Additionally, we fine-tuned a VGG16 architecture via transfer learning for disease classification. Our experiments demonstrate promising results, with accuracies of 99.27% and 99.44% achieved on segmented and non-segmented datasets.


_The Python source code for this paper will be available in this repository after the paper is published._

_The datasets and materials utilized in this study are available for researchers upon request._
