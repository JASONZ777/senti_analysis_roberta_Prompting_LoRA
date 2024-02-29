Intend to fine tune a Bert model to do the sentiment analysis.

Method 1: Hard prompt + BERT

Method 2: QLoRA using PEFT library

we find that Method 2 (more than 90% after 10 epoches) performs better than Method 1 (87% after 10 epoches), but it may require a smaller batch size for training
