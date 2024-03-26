# Setting_accent

# В данном ноутбуке решена задача постановки ударений для русского языка 

# EDA 

Ниже приведелно распределение, на какую букву падает ударение словах из датасета

![image](https://github.com/BerezinDaniil/Setting_accents/assets/78606208/8d0d1691-292a-4bc4-b3de-a3cc33625565)



# Model

_________________________________________________________________

 Layer (type) |Output Shape  |    Param   
:------------:|:------------:|:------------:|
 text_vectorization (TextVectorization)  | (None, None)  |     0                                                                                              
 embedding (Embedding)      | (None, None, 256)    |     8960      
 batch_normalization (Batch Normalization) | (None, None, 256)    | 1024                                         
 bidirectional (Bidirectional) | (None, None, 256)    |     394240                                                                                                                      
 dropout (Dropout)          | (None, None, 256)    |     0                     
 bidirectional_1 (Bidirectional) |  (None, None, 128)     |    164352              
 bidirectional_2 (Bidirectional)   | (None, None, 128)    |     98816         
 dropout_1 (Dropout)     |    (None, None, 128)     |    0                                                                    
 bidirectional_3 (Bidirectional) |  (None, None, 128)    |     98816                                       
 bidirectional_4 (Bidirectional) |  (None, 128)        |       98816                                                             
 dropout_2 (Dropout)     |    (None, 128)        |       0              
 dense (Dense)          |     (None, 64)        |        8256                             
 dense_1 (Dense)        |     (None, 32)       |         2080                                                
 dropout_3 (Dropout)     |    (None, 32)      |          0                                                            
 dense_2 (Dense)        |     (None, 16)      |          528                                                          

### Total params: 875888 (3.34 MB)

### Trainable params: 875376 (3.34 MB)

### Non-trainable params: 512 (2.00 KB)

_________________________________________________________________

# Train 
![image](https://github.com/BerezinDaniil/Setting_accents/assets/78606208/ac2a7d51-5cab-4f06-8363-1bb10144c019)

# Accuracy - 0.90 

