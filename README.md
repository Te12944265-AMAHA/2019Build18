# 2019Build18
(Feel free to add discriptions:)

At first, character recognition and storing

Input text, output stored characters in order

Remove word from full-alphabet sentence, learn from sentence, predict word


Network structure: GAN


OCR: pytesseract
Handwriting datasets: need characters stratified by writer (whole alphabet for multiple writers)

Generator network
Discriminator network
(these both extend Module class)

Trainer script, saves network to pth file

Class/function to display sequence of character images given text

Script to takes in an image drawn using some drawing software, identify characters, feed characters to generator network, outputs the full alphabet (or missing word)



## About the slides
Chapters 2.0 - 4.1 are useful for understanding image filtering and convolution. Chapters 10.0 - 13.1 help understand how neural networks work. Btw the first slide in chapter 10.3 is fun lol
