# Diabetes-detection
This project compares various deep learning models for diagnosing diabetic foot ulcers (DFUs) using foot thermography images. Among the models, MobileNet and ConvNext emerge as top performers. MobileNet achieves the highest accuracy (87.61%) and AUC (0.9538), making it the most reliable for precise DFU identification. ConvNext excels in precision (95.44%) and recall (81.85%), offering a balanced approach in identifying DFU cases while minimizing false positives.

Other models like EfficientNet and NasNetMobile perform well in specific areas, with EfficientNet showing strong precision and NasNetMobile good recall. Inception_Resnet has high recall, making it useful for scenarios where capturing all positive cases is crucial, despite lower accuracy.

The project also highlights the superiority of transformer-based models (e.g., BEiT, ViT, Swin TransformerV2) over traditional convolutional neural networks (CNNs) like Xception and SeResNet101. Transformers outperform CNNs due to their advanced attention mechanisms, ability to capture complex patterns, and robustness to variations in input data.
