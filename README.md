# flickr

This page provides an overview of the flickr-related resources used for  
the JSALT Rosetta workshop, links to the original images, text, and speech  
databases, as well as additional resources not collected/used within the
JSALT Rosetta workshop but that might be relevant for researchers working  
with the flickr database.

When using the flickr database, please ensure you have the  
license/permission to do so. For more information, see the corresponding  
database websites.


FLICKR DATABASES
- link to FlickR text captions and instructions how to obtain the images:
     * http://nlp.cs.illinois.edu/HockenmaierGroup/Framing_Image_Description/KCCA.html

- link to professional German and French translations of the English  
captions:
   * http://www.statmt.org/wmt17/multimodal-task.html

- link to FlickR speech corpus:
     * https://groups.csail.mit.edu/sls/downloads/flickraudio/

- link to semantically labelled Flickr speech corpus (details in https://arxiv.org/abs/1710.01949):
    * https://github.com/kamperh/semantic_flickraudio


JSALT ROSETTA RESOURCES
- download Japanese NMT translations (created by Google NMT) +  
tokenization (created by Graham Neubig):
     * flickr_jp_all.txt (translations)
     * flickr_ar_all.txt (with tokenization)

- download forced phone alignments (created by Markus Müller):
     * flickr_labels.tar
Note: this file only contains 37794 and not all 40000 files because  
sometimes forced-alignments failed due to discrepancies between the audio  
and the transcriptions

- download the used training/validation/test splits for the images and  
speech:
     * speech_data_splits.zip (speech)
     * images_data_splits.zip (images)


OTHER AND EXTERNAL RESOURCES
- download the VGG image features:
     * http://isle.illinois.edu/sst/data/images_40k.npz
     * http://isle.illinois.edu/sst/data/vgg_flickr8k.html
- download visual tags for the Flickr8k images (details in https://arxiv.org/abs/1710.01949):
    * flickr8k.tags.all.txt.zip


EDIT HISTORY
- Created 22/05/2018, Odette Scharenborg
- Minor revision (moved images_40k off github) 25/05/2018, Mark Hasegawa-Johnson
- Added visual tags and link to semantic labels, 18/06/2018, Herman Kamper

