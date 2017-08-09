# MarNr-Data
A dataset for Margin Noise Removal

The margin noise removal dataset consists of 75 scanned images of pages from `Bengali' books. The dataset consists of $46$ images from epics like `Mahabharata' and `Ramayana', 14 images from `Rabindra Rachanabali' (Collection of literary works by Rabindranath Tagore), and 15 images from different story books and magazines. All these images are scanned in 300~dpi.  The dataset is called as\emph{MarNR}dataset. For each image in the dataset, pixel level annotation is generated using a groundtruth generation tool Anveshak {http://www.facweb.iitkgp.ernet.in/~jay/anveshak/anveshak.html}. In the annotated image, each foreground pixel of a particular class is represented with a unique integer value. An XML file with annotated image path, number of labels present in the image, and the class name with its corresponding integer value in the annotated image is also generated for a particular image. The dataset consists of different types of margin noises like, black clutter noise present at the junction of two pages, textual noises like readers scribblings, notes, text part of the adjacent pages, etc. It also consists of images with different different types of layout. 




For a single image the groundtruth is present in a folder of same name as of the image.
The dataset can also be downloaded from http://www.facweb.iitkgp.ernet.in/~jay/MarNR/MarNR.html

citation


