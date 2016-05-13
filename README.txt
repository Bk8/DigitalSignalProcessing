README

School Project convolving an audio file with an impulse response file.
This was kept under version control at my school so this is the final refactored version of my code using FFT.

The output file sounds like the audio file was recorded at the location of the ImpulseResponse(IR) file.
That is, with the given example files, it sounds like the tibetan chant is recording at the Taj_Mahal.
By listening to the initial audio file(TibetanChant.wav) and then listening to the output file (output.wav) you will observe the difference in sounds.

CPSC 501: Advanced Programming Techniques Assignment 4
Adam Maidens - 10044293

To compile my program type:

	> g++ convolve.cpp -o convolve

To run my program type:

	> ./convolve inputFile IRfile outputFile

I have included the two files I used for testing so to run with such files type:

	> ./convolve TibetanChant.wav l960taj_mahal_deep6.wav output.wav