# metaphor-detection-tamil
metaphor detection and extraction for Tamil language
We propose a metaphor detection tool for Tamil language which is a low resource language. We will be creating a dataset for binary classification of metaphorical and non-metaphorical sentences and then will build the binary classification tool and then we will also create a dataset with metaphrical sentences annotated with target and source pairs. We will be implementing a metaphor extraction tool to extract the target and source pairs and produce output tagged with these two pairs

As a first step I will create binary clasifier to identifiy whether the given lyrics is metaphorical or not. For this I need a binary labelled dataset with lyrics. I have crowsourced and cleaned the dataset and filtered out unncessary details, duplicates and then annotated with the help of people with better understanding and knowledge in Tamil language with very good results in Tamil subject in O/Ls/

I have finalzed the dataset and use the dataset to fine-tune different monolingual and multitlingual language models to compare the accuracy, F1 score and the Recall. I have used Torch with transformers for the above purporse.
