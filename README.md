# Projeto Final - Modelos Preditivos Conexionistas

### Victor Queiroga Crescêncio da Costa

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens|Modelo construído utilizando o keras|Tensorflow|

## Performance

O modelo treinado possui performance de **75%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```
Found 116 images belonging to 4 classes.
Found 28 images belonging to 4 classes.
/usr/local/lib/python3.7/dist-packages/ipykernel_launcher.py:54: UserWarning: `Model.fit_generator` is deprecated and will be removed in a future version. Please use `Model.fit`, which supports generators.
Epoch 1/100
2/2 [==============================] - ETA: 0s - loss: 0.7760 - accuracy: 0.6154WARNING:tensorflow:Your input ran out of data; interrupting training. Make sure that your dataset or generator can generate at least `steps_per_epoch * epochs` batches (in this case, 2 batches). You may need to use the repeat() function when building your dataset.

Epoch 1: saving model to training_1/cp.ckpt
2/2 [==============================] - 2s 577ms/step - loss: 0.7760 - accuracy: 0.6154 - val_loss: 0.6496 - val_accuracy: 0.7500
Epoch 2/100
2/2 [==============================] - ETA: 0s - loss: 0.8504 - accuracy: 0.7212
Epoch 2: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 210ms/step - loss: 0.8504 - accuracy: 0.7212
Epoch 3/100
2/2 [==============================] - ETA: 0s - loss: 0.7772 - accuracy: 0.6250
Epoch 3: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 261ms/step - loss: 0.7772 - accuracy: 0.6250
Epoch 4/100
2/2 [==============================] - ETA: 0s - loss: 0.8422 - accuracy: 0.6538
Epoch 4: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 251ms/step - loss: 0.8422 - accuracy: 0.6538
Epoch 5/100
2/2 [==============================] - ETA: 0s - loss: 0.8279 - accuracy: 0.6923
Epoch 5: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 201ms/step - loss: 0.8279 - accuracy: 0.6923
Epoch 6/100
2/2 [==============================] - ETA: 0s - loss: 0.7317 - accuracy: 0.6797
Epoch 6: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 251ms/step - loss: 0.7317 - accuracy: 0.6797
Epoch 7/100
2/2 [==============================] - ETA: 0s - loss: 0.6983 - accuracy: 0.6827
Epoch 7: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 221ms/step - loss: 0.6983 - accuracy: 0.6827
Epoch 8/100
2/2 [==============================] - ETA: 0s - loss: 0.7175 - accuracy: 0.6641
Epoch 8: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 218ms/step - loss: 0.7175 - accuracy: 0.6641
Epoch 9/100
2/2 [==============================] - ETA: 0s - loss: 0.7060 - accuracy: 0.6719
Epoch 9: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 230ms/step - loss: 0.7060 - accuracy: 0.6719
Epoch 10/100
2/2 [==============================] - ETA: 0s - loss: 0.7121 - accuracy: 0.7212
Epoch 10: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 191ms/step - loss: 0.7121 - accuracy: 0.7212
Epoch 11/100
2/2 [==============================] - ETA: 0s - loss: 0.6778 - accuracy: 0.7212
Epoch 11: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 190ms/step - loss: 0.6778 - accuracy: 0.7212
Epoch 12/100
2/2 [==============================] - ETA: 0s - loss: 0.6479 - accuracy: 0.7019
Epoch 12: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 278ms/step - loss: 0.6479 - accuracy: 0.7019
Epoch 13/100
2/2 [==============================] - ETA: 0s - loss: 0.7043 - accuracy: 0.6635
Epoch 13: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 209ms/step - loss: 0.7043 - accuracy: 0.6635
Epoch 14/100
2/2 [==============================] - ETA: 0s - loss: 0.6439 - accuracy: 0.6875
Epoch 14: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 234ms/step - loss: 0.6439 - accuracy: 0.6875
Epoch 15/100
2/2 [==============================] - ETA: 0s - loss: 0.6538 - accuracy: 0.6719
Epoch 15: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 265ms/step - loss: 0.6538 - accuracy: 0.6719
Epoch 16/100
2/2 [==============================] - ETA: 0s - loss: 0.6262 - accuracy: 0.6953
Epoch 16: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 251ms/step - loss: 0.6262 - accuracy: 0.6953
Epoch 17/100
2/2 [==============================] - ETA: 0s - loss: 0.6271 - accuracy: 0.7109
Epoch 17: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 245ms/step - loss: 0.6271 - accuracy: 0.7109
Epoch 18/100
2/2 [==============================] - ETA: 0s - loss: 0.6576 - accuracy: 0.7212
Epoch 18: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 262ms/step - loss: 0.6576 - accuracy: 0.7212
Epoch 19/100
2/2 [==============================] - ETA: 0s - loss: 0.6805 - accuracy: 0.6827
Epoch 19: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 196ms/step - loss: 0.6805 - accuracy: 0.6827
Epoch 20/100
2/2 [==============================] - ETA: 0s - loss: 0.6624 - accuracy: 0.7404
Epoch 20: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 187ms/step - loss: 0.6624 - accuracy: 0.7404
Epoch 21/100
2/2 [==============================] - ETA: 0s - loss: 0.6217 - accuracy: 0.7308
Epoch 21: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 277ms/step - loss: 0.6217 - accuracy: 0.7308
Epoch 22/100
2/2 [==============================] - ETA: 0s - loss: 0.6320 - accuracy: 0.6953
Epoch 22: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 252ms/step - loss: 0.6320 - accuracy: 0.6953
Epoch 23/100
2/2 [==============================] - ETA: 0s - loss: 0.6216 - accuracy: 0.7188
Epoch 23: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 233ms/step - loss: 0.6216 - accuracy: 0.7188
Epoch 24/100
2/2 [==============================] - ETA: 0s - loss: 0.6258 - accuracy: 0.6923
Epoch 24: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 187ms/step - loss: 0.6258 - accuracy: 0.6923
Epoch 25/100
2/2 [==============================] - ETA: 0s - loss: 0.6145 - accuracy: 0.7266
Epoch 25: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 227ms/step - loss: 0.6145 - accuracy: 0.7266
Epoch 26/100
2/2 [==============================] - ETA: 0s - loss: 0.5889 - accuracy: 0.7500
Epoch 26: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 195ms/step - loss: 0.5889 - accuracy: 0.7500
Epoch 27/100
2/2 [==============================] - ETA: 0s - loss: 0.5905 - accuracy: 0.7404
Epoch 27: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 194ms/step - loss: 0.5905 - accuracy: 0.7404
Epoch 28/100
2/2 [==============================] - ETA: 0s - loss: 0.6075 - accuracy: 0.7422
Epoch 28: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 230ms/step - loss: 0.6075 - accuracy: 0.7422
Epoch 29/100
2/2 [==============================] - ETA: 0s - loss: 0.6000 - accuracy: 0.7266
Epoch 29: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 229ms/step - loss: 0.6000 - accuracy: 0.7266
Epoch 30/100
2/2 [==============================] - ETA: 0s - loss: 0.6006 - accuracy: 0.7344
Epoch 30: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 225ms/step - loss: 0.6006 - accuracy: 0.7344
Epoch 31/100
2/2 [==============================] - ETA: 0s - loss: 0.5982 - accuracy: 0.7266
Epoch 31: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 248ms/step - loss: 0.5982 - accuracy: 0.7266
Epoch 32/100
2/2 [==============================] - ETA: 0s - loss: 0.6221 - accuracy: 0.7115
Epoch 32: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 217ms/step - loss: 0.6221 - accuracy: 0.7115
Epoch 33/100
2/2 [==============================] - ETA: 0s - loss: 0.6048 - accuracy: 0.7404
Epoch 33: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 263ms/step - loss: 0.6048 - accuracy: 0.7404
Epoch 34/100
2/2 [==============================] - ETA: 0s - loss: 0.6080 - accuracy: 0.7344
Epoch 34: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 251ms/step - loss: 0.6080 - accuracy: 0.7344
Epoch 35/100
2/2 [==============================] - ETA: 0s - loss: 0.5922 - accuracy: 0.7500
Epoch 35: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 246ms/step - loss: 0.5922 - accuracy: 0.7500
Epoch 36/100
2/2 [==============================] - ETA: 0s - loss: 0.5873 - accuracy: 0.7404
Epoch 36: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 199ms/step - loss: 0.5873 - accuracy: 0.7404
Epoch 37/100
2/2 [==============================] - ETA: 0s - loss: 0.5898 - accuracy: 0.7308
Epoch 37: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 273ms/step - loss: 0.5898 - accuracy: 0.7308
Epoch 38/100
2/2 [==============================] - ETA: 0s - loss: 0.6023 - accuracy: 0.7308
Epoch 38: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 191ms/step - loss: 0.6023 - accuracy: 0.7308
Epoch 39/100
2/2 [==============================] - ETA: 0s - loss: 0.5858 - accuracy: 0.7500
Epoch 39: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 241ms/step - loss: 0.5858 - accuracy: 0.7500
Epoch 40/100
2/2 [==============================] - ETA: 0s - loss: 0.6007 - accuracy: 0.7500
Epoch 40: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 195ms/step - loss: 0.6007 - accuracy: 0.7500
Epoch 41/100
2/2 [==============================] - ETA: 0s - loss: 0.6003 - accuracy: 0.7266
Epoch 41: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 243ms/step - loss: 0.6003 - accuracy: 0.7266
Epoch 42/100
2/2 [==============================] - ETA: 0s - loss: 0.5850 - accuracy: 0.7404
Epoch 42: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 235ms/step - loss: 0.5850 - accuracy: 0.7404
Epoch 43/100
2/2 [==============================] - ETA: 0s - loss: 0.5901 - accuracy: 0.7266
Epoch 43: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 240ms/step - loss: 0.5901 - accuracy: 0.7266
Epoch 44/100
2/2 [==============================] - ETA: 0s - loss: 0.5947 - accuracy: 0.7344
Epoch 44: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 228ms/step - loss: 0.5947 - accuracy: 0.7344
Epoch 45/100
2/2 [==============================] - ETA: 0s - loss: 0.5812 - accuracy: 0.7500
Epoch 45: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 236ms/step - loss: 0.5812 - accuracy: 0.7500
Epoch 46/100
2/2 [==============================] - ETA: 0s - loss: 0.5822 - accuracy: 0.7500
Epoch 46: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 229ms/step - loss: 0.5822 - accuracy: 0.7500
Epoch 47/100
2/2 [==============================] - ETA: 0s - loss: 0.5746 - accuracy: 0.7500
Epoch 47: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 232ms/step - loss: 0.5746 - accuracy: 0.7500
Epoch 48/100
2/2 [==============================] - ETA: 0s - loss: 0.5764 - accuracy: 0.7500
Epoch 48: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 228ms/step - loss: 0.5764 - accuracy: 0.7500
Epoch 49/100
2/2 [==============================] - ETA: 0s - loss: 0.5790 - accuracy: 0.7500
Epoch 49: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 257ms/step - loss: 0.5790 - accuracy: 0.7500
Epoch 50/100
2/2 [==============================] - ETA: 0s - loss: 0.5859 - accuracy: 0.7500
Epoch 50: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 195ms/step - loss: 0.5859 - accuracy: 0.7500
Epoch 51/100
2/2 [==============================] - ETA: 0s - loss: 0.5872 - accuracy: 0.7404
Epoch 51: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 248ms/step - loss: 0.5872 - accuracy: 0.7404
Epoch 52/100
2/2 [==============================] - ETA: 0s - loss: 0.5869 - accuracy: 0.7404
Epoch 52: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 199ms/step - loss: 0.5869 - accuracy: 0.7404
Epoch 53/100
2/2 [==============================] - ETA: 0s - loss: 0.5832 - accuracy: 0.7500
Epoch 53: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 241ms/step - loss: 0.5832 - accuracy: 0.7500
Epoch 54/100
2/2 [==============================] - ETA: 0s - loss: 0.5837 - accuracy: 0.7500
Epoch 54: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 257ms/step - loss: 0.5837 - accuracy: 0.7500
Epoch 55/100
2/2 [==============================] - ETA: 0s - loss: 0.5810 - accuracy: 0.7500
Epoch 55: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 244ms/step - loss: 0.5810 - accuracy: 0.7500
Epoch 56/100
2/2 [==============================] - ETA: 0s - loss: 0.5786 - accuracy: 0.7500
Epoch 56: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 251ms/step - loss: 0.5786 - accuracy: 0.7500
Epoch 57/100
2/2 [==============================] - ETA: 0s - loss: 0.5805 - accuracy: 0.7500
Epoch 57: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 224ms/step - loss: 0.5805 - accuracy: 0.7500
Epoch 58/100
2/2 [==============================] - ETA: 0s - loss: 0.5755 - accuracy: 0.7500
Epoch 58: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 255ms/step - loss: 0.5755 - accuracy: 0.7500
Epoch 59/100
2/2 [==============================] - ETA: 0s - loss: 0.5810 - accuracy: 0.7500
Epoch 59: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 239ms/step - loss: 0.5810 - accuracy: 0.7500
Epoch 60/100
2/2 [==============================] - ETA: 0s - loss: 0.5737 - accuracy: 0.7500
Epoch 60: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 240ms/step - loss: 0.5737 - accuracy: 0.7500
Epoch 61/100
2/2 [==============================] - ETA: 0s - loss: 0.5750 - accuracy: 0.7500
Epoch 61: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 229ms/step - loss: 0.5750 - accuracy: 0.7500
Epoch 62/100
2/2 [==============================] - ETA: 0s - loss: 0.5748 - accuracy: 0.7500
Epoch 62: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 286ms/step - loss: 0.5748 - accuracy: 0.7500
Epoch 63/100
2/2 [==============================] - ETA: 0s - loss: 0.5769 - accuracy: 0.7500
Epoch 63: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 251ms/step - loss: 0.5769 - accuracy: 0.7500
Epoch 64/100
2/2 [==============================] - ETA: 0s - loss: 0.5747 - accuracy: 0.7500
Epoch 64: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 227ms/step - loss: 0.5747 - accuracy: 0.7500
Epoch 65/100
2/2 [==============================] - ETA: 0s - loss: 0.5752 - accuracy: 0.7500
Epoch 65: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 239ms/step - loss: 0.5752 - accuracy: 0.7500
Epoch 66/100
2/2 [==============================] - ETA: 0s - loss: 0.5785 - accuracy: 0.7500
Epoch 66: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 245ms/step - loss: 0.5785 - accuracy: 0.7500
Epoch 67/100
2/2 [==============================] - ETA: 0s - loss: 0.5752 - accuracy: 0.7500
Epoch 67: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 251ms/step - loss: 0.5752 - accuracy: 0.7500
Epoch 68/100
2/2 [==============================] - ETA: 0s - loss: 0.5752 - accuracy: 0.7500
Epoch 68: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 196ms/step - loss: 0.5752 - accuracy: 0.7500
Epoch 69/100
2/2 [==============================] - ETA: 0s - loss: 0.5804 - accuracy: 0.7500
Epoch 69: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 261ms/step - loss: 0.5804 - accuracy: 0.7500
Epoch 70/100
2/2 [==============================] - ETA: 0s - loss: 0.5765 - accuracy: 0.7500
Epoch 70: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 201ms/step - loss: 0.5765 - accuracy: 0.7500
Epoch 71/100
2/2 [==============================] - ETA: 0s - loss: 0.5777 - accuracy: 0.7500
Epoch 71: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 261ms/step - loss: 0.5777 - accuracy: 0.7500
Epoch 72/100
2/2 [==============================] - ETA: 0s - loss: 0.5762 - accuracy: 0.7500
Epoch 72: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 196ms/step - loss: 0.5762 - accuracy: 0.7500
Epoch 73/100
2/2 [==============================] - ETA: 0s - loss: 0.5732 - accuracy: 0.7500
Epoch 73: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 204ms/step - loss: 0.5732 - accuracy: 0.7500
Epoch 74/100
2/2 [==============================] - ETA: 0s - loss: 0.5757 - accuracy: 0.7500
Epoch 74: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 228ms/step - loss: 0.5757 - accuracy: 0.7500
Epoch 75/100
2/2 [==============================] - ETA: 0s - loss: 0.5717 - accuracy: 0.7500
Epoch 75: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 250ms/step - loss: 0.5717 - accuracy: 0.7500
Epoch 76/100
2/2 [==============================] - ETA: 0s - loss: 0.5836 - accuracy: 0.7422
Epoch 76: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 239ms/step - loss: 0.5836 - accuracy: 0.7422
Epoch 77/100
2/2 [==============================] - ETA: 0s - loss: 0.5757 - accuracy: 0.7500
Epoch 77: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 247ms/step - loss: 0.5757 - accuracy: 0.7500
Epoch 78/100
2/2 [==============================] - ETA: 0s - loss: 0.5735 - accuracy: 0.7500
Epoch 78: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 231ms/step - loss: 0.5735 - accuracy: 0.7500
Epoch 79/100
2/2 [==============================] - ETA: 0s - loss: 0.5748 - accuracy: 0.7500
Epoch 79: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 195ms/step - loss: 0.5748 - accuracy: 0.7500
Epoch 80/100
2/2 [==============================] - ETA: 0s - loss: 0.5742 - accuracy: 0.7500
Epoch 80: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 224ms/step - loss: 0.5742 - accuracy: 0.7500
Epoch 81/100
2/2 [==============================] - ETA: 0s - loss: 0.5729 - accuracy: 0.7500
Epoch 81: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 197ms/step - loss: 0.5729 - accuracy: 0.7500
Epoch 82/100
2/2 [==============================] - ETA: 0s - loss: 0.5769 - accuracy: 0.7500
Epoch 82: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 237ms/step - loss: 0.5769 - accuracy: 0.7500
Epoch 83/100
2/2 [==============================] - ETA: 0s - loss: 0.5741 - accuracy: 0.7500
Epoch 83: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 247ms/step - loss: 0.5741 - accuracy: 0.7500
Epoch 84/100
2/2 [==============================] - ETA: 0s - loss: 0.5744 - accuracy: 0.7500
Epoch 84: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 255ms/step - loss: 0.5744 - accuracy: 0.7500
Epoch 85/100
2/2 [==============================] - ETA: 0s - loss: 0.5773 - accuracy: 0.7500
Epoch 85: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 189ms/step - loss: 0.5773 - accuracy: 0.7500
Epoch 86/100
2/2 [==============================] - ETA: 0s - loss: 0.5701 - accuracy: 0.7500
Epoch 86: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 247ms/step - loss: 0.5701 - accuracy: 0.7500
Epoch 87/100
2/2 [==============================] - ETA: 0s - loss: 0.5747 - accuracy: 0.7500
Epoch 87: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 188ms/step - loss: 0.5747 - accuracy: 0.7500
Epoch 88/100
2/2 [==============================] - ETA: 0s - loss: 0.5718 - accuracy: 0.7500
Epoch 88: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 263ms/step - loss: 0.5718 - accuracy: 0.7500
Epoch 89/100
2/2 [==============================] - ETA: 0s - loss: 0.5732 - accuracy: 0.7500
Epoch 89: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 249ms/step - loss: 0.5732 - accuracy: 0.7500
Epoch 90/100
2/2 [==============================] - ETA: 0s - loss: 0.5748 - accuracy: 0.7500
Epoch 90: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 245ms/step - loss: 0.5748 - accuracy: 0.7500
Epoch 91/100
2/2 [==============================] - ETA: 0s - loss: 0.5720 - accuracy: 0.7500
Epoch 91: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 192ms/step - loss: 0.5720 - accuracy: 0.7500
Epoch 92/100
2/2 [==============================] - ETA: 0s - loss: 0.5719 - accuracy: 0.7500
Epoch 92: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 220ms/step - loss: 0.5719 - accuracy: 0.7500
Epoch 93/100
2/2 [==============================] - ETA: 0s - loss: 0.5749 - accuracy: 0.7500
Epoch 93: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 251ms/step - loss: 0.5749 - accuracy: 0.7500
Epoch 94/100
2/2 [==============================] - ETA: 0s - loss: 0.5688 - accuracy: 0.7500
Epoch 94: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 191ms/step - loss: 0.5688 - accuracy: 0.7500
Epoch 95/100
2/2 [==============================] - ETA: 0s - loss: 0.5717 - accuracy: 0.7500
Epoch 95: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 206ms/step - loss: 0.5717 - accuracy: 0.7500
Epoch 96/100
2/2 [==============================] - ETA: 0s - loss: 0.5715 - accuracy: 0.7500
Epoch 96: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 250ms/step - loss: 0.5715 - accuracy: 0.7500
Epoch 97/100
2/2 [==============================] - ETA: 0s - loss: 0.5733 - accuracy: 0.7500
Epoch 97: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 225ms/step - loss: 0.5733 - accuracy: 0.7500
Epoch 98/100
2/2 [==============================] - ETA: 0s - loss: 0.5730 - accuracy: 0.7500
Epoch 98: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 252ms/step - loss: 0.5730 - accuracy: 0.7500
Epoch 99/100
2/2 [==============================] - ETA: 0s - loss: 0.5732 - accuracy: 0.7500
Epoch 99: saving model to training_1/cp.ckpt
2/2 [==============================] - 1s 256ms/step - loss: 0.5732 - accuracy: 0.7500
Epoch 100/100
2/2 [==============================] - ETA: 0s - loss: 0.5720 - accuracy: 0.7500
Epoch 100: saving model to training_1/cp.ckpt
2/2 [==============================] - 0s 218ms/step - loss: 0.5720 - accuracy: 0.7500
  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

Exemplo de adição de imagem:
![Evolução da accuracy e da loss ao longo do treinamento](assets/evidências.png)

## Roboflow

[https://universe.roboflow.com/classification/cats--dogs-and-birds]

## HuggingFace

https://huggingface.co/vqcc/dogs_cats_birds