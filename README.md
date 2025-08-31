# Flower-Classification-on-TPU-using-Deep-Learning



## Dataset 
Dataset Link: https://www.kaggle.com/competitions/tpu-getting-started/data

The dataset consists of labeled images covering 104 distinct flower categories, compiled from five publicly available datasets. It includes both images with a single flower subtype and those containing multiple subtypes. The collection captures flowers from a wide variety of angles, backgrounds, and environments, including challenging cases such as flowers appearing in unusual locations, alongside modern objects, or under varying lighting and contrast conditions. These imperfections make the dataset more robust, ensuring that models trained on it are better suited for real-world classification tasks.

The data is provided in TFRecord format, a TensorFlow-optimized container for efficient data loading and training. Each pre-split record contains an image ID, its corresponding label, and pixel array information. The complete dataset size is approximately 5.12 GB.
