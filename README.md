Assignment 2: Optical Character Recognition (OCR)

Objective  
The objective of this assignment is to implement and compare two Optical Character Recognition (OCR) pipelines on a common evaluation task. The assignment involves working with both a traditional OCR system and a neural network–based OCR system using transfer learning, followed by a comparative analysis of their performance.

Part A: OCR using PyTesseract  

In this part, an OCR pipeline is implemented using PyTesseract. PyTesseract is a ready-to-use OCR engine and does not require any training. The focus of this part is on preprocessing, configuration, and evaluation.

Tasks performed  
- Load the provided test image(s) and perform OCR using PyTesseract  
- Apply suitable image preprocessing techniques such as resizing, thresholding, noise removal, and morphological operations  
- Experiment with different Page Segmentation Modes (PSM) and document the chosen configuration  
- Report the recognized text output  
- Compute and report evaluation metrics such as Character Error Rate (CER) and/or Word Error Rate (WER) on the provided evaluation page  

Part B: OCR using Transfer Learning (EasyOCR)  

In this part, a neural network–based OCR system is implemented using transfer learning. EasyOCR is used as the recognition framework.

Tasks performed  
- Use the provided training dataset to fine-tune an EasyOCR recognition model  
- Clearly document the transfer learning strategy used, including freezing layers, partial fine-tuning, and learning rate selection  
- Train the model and report training metrics such as loss curves  
- Run inference on the same evaluation image(s) used in Part A  
- Compute and report CER and/or WER for the EasyOCR model  

Documentation details  
The implementation clearly documents:  
- Which components of the model were fine-tuned  
- What changes were made compared to the default pre-trained setup  
- The reasoning behind these changes  

Common Evaluation and Comparison  

To ensure a fair comparison, both OCR systems are evaluated on the same provided test page.

Tasks performed  
- Present the OCR outputs from both PyTesseract and EasyOCR  
- Compare the quantitative metrics (CER and/or WER)  
- Provide a brief qualitative discussion explaining which method performs better and why  

Deliverables  
- One Colab notebook for Part A (PyTesseract)  
- One Colab notebook for Part B (EasyOCR with transfer learning)  
- A short written report (1–2 pages) summarizing the results and comparison
