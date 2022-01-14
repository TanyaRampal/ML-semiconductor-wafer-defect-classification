# ML-semiconductor-wafer-defect-classification

In electronics, a wafer is a thin slice of semiconductor, such as a crystalline silicon (c-Si), used for the fabrication of integrated circuits. Even though other conductors are employed in more particular applications, silicon is the best and the most used semiconductor due to its extreme mobility both at high temperatures and at room temperature. In today’s world, almost every electronic device (computers, cell phones, cars, televisions, digital watches) use ICs made out of Si wafers due to its small size and high reliability and efficiency.

However, due to imperfections during the manufacturing of wafers and then ICs, certain defects occur on the wafers due to foreign particles, contact rubbing causing scratches, solvent and other chemical residues etc. Thus, defect detection is an integral part of wafer (chip) fabrication process. Once the defect is detected, it needs to be classified in order to enable the correction of the fabrication process. This classification is based on the defect properties such as specific patterns, geometries, frequency of imperfections etc.

In this project, construction of a model for defect classification of fully manufactured Si wafer chips was attempted via machine learning classification models, using the dataset WM811K provided by [MIR Labs], with the image array of the chip taken as the features, and the defect classes as the target. In this report, firstly, an overview of the manufacturing process of Si wafers and ICs is covered, then the process identifying defective wafers via image mapping is studied. Finally, the methodology of making the machine learning classification model is gone through stepwise, and the final model selected is used to further classify the instances within the ‘none’ category. Based on this model, certain conclusions and insights are drawn.

The code file is the python notebook attached above, and a detailed report is also attached herewith.

Note: The dataset (WM811K) used is too large to be uploaded on Google drive, hence a link to the download it as well as the original source link is given in the report at the end (just before references).
