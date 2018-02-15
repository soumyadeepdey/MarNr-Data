# MarNr-Data
A dataset for Margin Noise Removal

The margin noise removal dataset consists of 75 scanned images of pages from `Bengali' books. The dataset consists of $46$ images from epics like `Mahabharata' and `Ramayana', 14 images from `Rabindra Rachanabali' (Collection of literary works by Rabindranath Tagore), and 15 images from different story books and magazines. All these images are scanned in 300~dpi.  The dataset is called as\emph{MarNR}dataset. For each image in the dataset, pixel level annotation is generated using a groundtruth generation tool Anveshak {http://www.facweb.iitkgp.ernet.in/~jay/anveshak/anveshak.html}. In the annotated image, each foreground pixel of a particular class is represented with a unique integer value. An XML file with annotated image path, number of labels present in the image, and the class name with its corresponding integer value in the annotated image is also generated for a particular image. The dataset consists of different types of margin noises like, black clutter noise present at the junction of two pages, textual noises like readers scribblings, notes, text part of the adjacent pages, etc. It also consists of images with different different types of layout. 




For a single image the groundtruth is present in a folder of same name as of the image.
The dataset can also be downloaded from http://www.facweb.iitkgp.ernet.in/~jay/MarNR/MarNR.html

citation

@INPROCEEDINGS{dey_MarNR_ICDAR17, 
author={S. Dey and B. Mitra and J. Mukhopadhyay and S. Sural}, 
booktitle={2017 14th IAPR International Conference on Document Analysis and Recognition (ICDAR)}, 
title={A Comparative Study of Margin Noise Removal Algorithms on MarNR: A Margin Noise Dataset of Document Images}, 
year={2017}, 
volume={04}, 
number={}, 
pages={35-39}, 
keywords={Classification algorithms;Clutter;High definition video;Image segmentation;Measurement;Optical character recognition software;Tools;Margin noise dataset;Margin noise removal;Performance evaluation}, 
doi={10.1109/ICDAR.2017.310},
month={Nov},}

@InProceedings{dey_ICVGIP_DAR16, 
author="Dey, Soumyadeep and Mukherjee, Jayanta and Sural, Shamik and Nandedkar, Amit Vijay", 
editor="Mukherjee, Snehasis and Mukherjee, Suvadip and Mukherjee, Dipti Prasad and Sivaswamy, Jayanthi and Awate, Suyash and Setlur, Srirangaraj and Namboodiri, Anoop M. and Chaudhury, Santanu", 
title="Anveshak - A Groundtruth Generation Tool for Foreground Regions of Document Images", 
booktitle="Computer Vision, Graphics, and Image Processing", 
year="2017", 
publisher="Springer International Publishing", 
address="Cham", 
pages="255--264",  
isbn="978-3-319-68124-5" }
