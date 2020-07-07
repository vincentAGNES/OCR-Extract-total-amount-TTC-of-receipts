<h2>Extract total amount TTC of receipts</h2>
<br><br>    
After reading this paper: https://arxiv.org/pdf/1903.12363.pdf
<br><br>
I've thought about a way to implement the preprocessing of images receipts described in the article. 
This notebook recaps my code proposal for the preprocessing of receipts before feeding the CNN/NLP/NER algorithm.
The idea of the article is to build a grid with text placed in the cell that corresponds to the place of the text in the image. 
The goal is to use both location of text (CNN) and content of text (NLP) to extract the useful information (Total amount TTC)
<br><br>    

I've used an open-source dataset available at the link below (200 pictures):
 <br> https://expressexpense.com/blog/free-receipt-images-ocr-machine-learning-dataset/
