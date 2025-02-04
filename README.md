<h2><b>Twitter Topic Modelling.</b></h2></h3>

LDA Model Training
The LDA model was trained using the following parameters:
- Number of Topics (num_topics): 12 topics were extracted to capture the diversity in the dataset.
- Random State (random_state): Set to 42 for reproducibility.
- Passes (passes): 100 iterations were used to ensure the model converged.
- Alpha (alpha): Set to 'asymmetric' to allow asymmetric topic distributions.
- Eta (eta): Set to 'auto' to let the model learn the word distributions.
- Chunksize (chunksize): 200 documents were processed at a time for efficiency.
- Update Frequency (update_every): The model was updated after every document.

The coherence score of 0.50C suggests that your LDA model has a reasonable topic, meaning the topics are interpretable.


Topics with weights: 

![image](https://github.com/user-attachments/assets/debfb330-8536-49d9-b738-354a2561ac1b)


The pyLDAvis visualization presents the discovered topics as bubbles, where larger bubbles indicate dominant topics in the dataset. The distance between bubbles represents topic similarity.

![image](https://github.com/user-attachments/assets/0070590d-b1f4-4838-92cc-1d3810cdc75e)
