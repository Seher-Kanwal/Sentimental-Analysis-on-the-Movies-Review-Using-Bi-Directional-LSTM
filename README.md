#### Sentimental-Analysis-on-the-Movies-Review-Using-Bi-Directional-LSTM



![Bidirectional-LSTM-model-showing-the-input-and-output-layers-The-red-arrows-represent (1)](https://user-images.githubusercontent.com/92606737/204677363-2127cba1-7257-465a-b6d8-8c3fd1982428.png)



# BI-LSTM(Bi-directional long short term memory)
Bidirectional long-short term memory(bi-lstm) is the process of making any neural network o have the sequence information in both directions backwards (future to past) or forward(past to future). 

In bidirectional, our input flows in two directions, making a bi-lstm different from the regular LSTM. With the regular LSTM, we can make input flow in one direction, either backwards or forward. However, in bi-directional, we can make the input flow in both directions to preserve the future and the past information.


# why we need BI-LSTM?


- ### She love apple becuase an apple keeps the doctor away.
- ### She love apple becuase of the electronic devices.

Here if we want to do NER(named entity recognition) that for apple we have two options:
- fruit or organization
which option to choose it's depend on the next sentence too. So we need to have the info or some contextual information from the future words or upcomming words too.

But with the simple lstm, this is not possible that's why we need to use bi-directional lstm. Here it will have contextual info from the start and from the end too.



# Where to use:

In the above diagram, we can see the flow of information from backward and forward layers. BI-LSTM is usually employed where the sequence to sequence tasks are needed.  This kind of network can be used in:
-  text classification
-  speech recognition 
-  forecasting models. 
