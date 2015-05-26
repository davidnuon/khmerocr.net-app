# khmerocr.net-app
KhmerOCR using .NET, only the sample .EXE demo product

First of all, don't expect that this application is a full working application for KhmerOCR, I am publishing here the demo I made using SVM methodology for Khmer letter recognition only.
You might find a very few resources on this topic and we don't have exactly someone publish their result as well.

The training data is using with Khmer OS Content, font size from 24pt up, of course you can try lower but the best result only from 24pt or 28pt up.

I will manage to release the source code soon for people to keep improving the method.

Nowadays, people are working on TeseractOCR which can be more accuracy which is required a lot of training data as well.
If you want to try the TeseractOCR, go to http://khmerocr.org which is not mine.
But you can follow me via: 

* OCR topic: http://khmerocr.com
* My blog: http://osify.com and http://ask.osify.com
* You can find some SVM topic in my blog: http://ask.osify.com
* The paper topic: "Support Vector Machine (SVM) Based Classifier For Khmer Printed Character-set Recognition"
  Published on a conference: APSIPA 2014, SiemReap
* Twitter: http://twitter.com/pongsametrey
* Facebook: https://facebook.com/osify

# How to Use
* Open KhmerOCRNET.exe

*Training Phase*
* First Tab: On Menu, Click on File > Open
* Choosing: Gaussian Kernel and click: Estimate
* Click on Training button
* Wait a moment until the Voting button is available
* Click on Voting button

*Testing with data*
* Third Tab: Browse the data
* You can use data sample which is in this repo or you can use the data written on MS Paint for corresponding font.
* Click on button: Analyse

* Remark: You need to have font: Limon S1 and Khmer Unicode in your system to view the result


# Release

*2013, 2014 : Demo for SVM*
	Demo made in 2013, slightly updated on 2014 for the conference