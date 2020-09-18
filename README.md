# Kaldi-ASR
The project aims to generate text transcripts of audio inputs giving WER as an output.

Word Error Rates computed on the decoded development data by the AcousticModels which were trained and tested using Bigram Language model are tabluated. Monophone, Triphone   and   DNN   based   Models   and   their corresponding WER are tabulated. Hybrid DNN-HMM models over bigram language model seems to perform better over the training and testing audio samples,as inferred from the log-likelihood per frame, and WER in training, as shown below.

![Alt text](decoderd_WER.png?raw=true "Title") <br/> <br/>

![Alt text](log_likelihoods_test.png?raw=true "Title") <br/> <br/>


