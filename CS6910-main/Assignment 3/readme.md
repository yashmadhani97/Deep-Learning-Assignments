## Geenral Instructions
- Upload Nirmala.ttf file from my repository in local machine
- My whole assignment code is in DL_Assignment_3.ipynb notebook.
- Run section named "Common cells for all questions"

### Seq2seq model
- Run cell under the scetion "Common cell for Questions [1,2,3,4]"
- Then run section "Q.1" which will intailize fucntion for creating model and it is common for Questions [2,3,4].
- Section "Q.2" is code for configurations of sweep.
- Run cells under section "Q.4" to train model with best config, measure test accuracy, plot models and plot grid of predictions.
- I have saved all the test predictions in prediction_vanila folder. 
- Beam search is computationally expensive so I put beam search code separately. To check code for beam search run section named "Beam search".

### Attention model
- Run cells under section "Common cell for Questions [5,6]"
- Run "Loading dataset" section under "Question 5" section.
- Section "Q.5(a)" has code for configurations of sweep.
- Run section "Q.5(b,c,d)" to train the model with best hyperparameters, measure test accuracy, plot heatmaps.
- Here I used multiple layer Attention model where each decoder layer is combined with different Attention layers. So there would be different Attention weights for each decoder layer.So i have plotted heatmaps corresponding to each decoder layer.
- I have saved all the test predictions in prediction_attention folder. 
- Also uploaded "corrected_predictions_with_attention_file.csv" file which has all predictions which are wrongly predicted in seq2seq model but corrected in attention model as asked in c part
- I commented wandb logs so that it can run smoothly on local machine.

#### Q.6 Visualisation
- Run cell under Section "Question 6" to retrain model with best hyperparameters,to get attention weights and plot visualisations.
- Input string can be changed in the last cell. to check visualisation for different ipnut.
- I commented wandb logs so that it can run smoothly on local machine.
