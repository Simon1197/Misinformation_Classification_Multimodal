# Misinformation_Classification_Multimodal

### Purpose
Using multimodal to solve misinformation problem.

### Datesets
For this research, we used the data from tweet 2016, which included 9142 observations in training datasets and 796 observations in testing datasets, each dataset contains text, image, and label. The original dataset is labeled as “real” or ”fake” for each observation. Tweets labeled as ”fake” incorporate any post that offers mixed media substance that does not reliably speak to the occasion it alludes to. This incorporates substance from a past occasion reposted as being captured for a right now unfurling comparable event, a setting that has been deliberately controlled, or mixed media substance distributed with a wrong claim almost the portrayed occasion. 

### Data pre-processing
For the image information, we pre-process each picture by resizing the pictures to 224 x 224 pixels and normalizing them. 

To get ready the information for utilization in include extraction, we clean the content information by expelling emoji characters, halt words, URLs, time stamps, and Twitter handles, selecting accentuation, and normalizing the content information by using lowercase content. In addition, minimize multi-spaces to one space, lemmatize the content, and keep as it were words that are more noteworthy than two characters long. Moreover, we removed observations with more than 512 tokens long after cleaning to plan for future forms. Of the training data tweets, 5,129 and 4,013 are considered fake and real. Of the test data tweets, 467 and 329 are considered fake and real.
