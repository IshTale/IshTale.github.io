## AI Engineer Intern Syncopation AI

**Project description:** Trained a custom dataset and fine-tuned object detection models for transparent objects, a challenging domain that required advanced techniques and optimization. Leveraged state-of-the-art technologies like YOLOv8 and Detectron2, implementing hyperparameter tuning to enhance the model's accuracy by 30%.

### 1. Hypotheses about the causes of observed phenomena

In the project, I hypothesized that limited data for transparent object detection significantly hindered model accuracy, especially for nuanced features like tubes and thin edges. This insight led to customized data preparation and strategic data augmentation to address these challenges

```python
# Hypothesis testing example in Python for model improvement
if "data_augmentation" in techniques_used:
    accuracy += 0.1  # Approximate improvement observed
```

### 2. Assess assumptions on which statistical inference will be based

Validated the assumptions for each model, especially regarding data distribution and the model's handling of transparency. Assessed training consistency and model overfitting through cross-validation and statistical metrics.

```python
# Check for overfitting using validation set
if validation_accuracy < training_accuracy - threshold:
    tune_hyperparameters()
```

### 3. Statistical tools and techniques

Chose YOLOv8 and Detectron2 based on their suitability for complex object detection. Applied cross-entropy loss, intersection-over-union (IoU) metrics, and grid search for hyperparameter tuning to maximize model precision.
<img src="images/transparent_object_model.jpg?raw=true"/>

### 4. A basis for further data collection through surveys or experiments

The project highlighted the need for a more extensive, diverse dataset to improve detection of transparent objects further. Recommendations included targeted data collection to better capture edges and fine details in transparent materials.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
