# Setting_accents

# Model


_________________________________________________________________
 Layer (type)                Output Shape              Param   
=================================================================
 text_vectorization (TextVe | (None, None)         |     0         
 ctorization)               |                      |               
                            |                      |               
 embedding (Embedding)      | (None, None, 256)    |     8960      
                            |                      |               
 batch_normalization (Batch | (None, None, 256)    |     1024      
 Normalization)             |                      |              
                            |                      |             
 bidirectional (Bidirection | (None, None, 256)    |     394240    
 al)                        |                      |               
                            |                      |               
 dropout (Dropout)          | (None, None, 256)    |     0         
                            |                      |               
 bidirectional_1 (Bidirecti |(None, None, 128)     |    164352    
 onal)                      |                      |               
                            |                      |               
 bidirectional_2 (Bidirecti | (None, None, 128)    |     98816     
 onal)                      |                      |             
                                                                 
 dropout_1 (Dropout)         (None, None, 128)         0         
                                                                 
 bidirectional_3 (Bidirecti  (None, None, 128)         98816     
 onal)                                                           
                                                                 
 bidirectional_4 (Bidirecti  (None, 128)               98816     
 onal)                                                           
                                                                 
 dropout_2 (Dropout)         (None, 128)               0         
                                                                 
 dense (Dense)               (None, 64)                8256      
                                                                 
 dense_1 (Dense)             (None, 32)                2080      
                                                                 
 dropout_3 (Dropout)         (None, 32)                0         
                                                                 
 dense_2 (Dense)             (None, 16)                528       
                                                                 
=================================================================


Total params: 875888 (3.34 MB)
Trainable params: 875376 (3.34 MB)
Non-trainable params: 512 (2.00 KB)


_________________________________________________________________

# Train 
![image](https://github.com/BerezinDaniil/Setting_accents/assets/78606208/ac2a7d51-5cab-4f06-8363-1bb10144c019)

