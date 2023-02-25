Digital signal processing (DSP) is the computation of mathematical methods used to manipulate signal data [**[1]**](https://doi.org/10.1016/B978-0-08-097768-3.00011-8). One of the most important tools in digital signal processing is the Discrete Fourier Transform (DFT). It is usually used to produce a signal's frequency-domain (spectral) representation [**[2]**](https://doi.org/10.1016/B978-0-08-099388-1.00003-0).

## Understanding Discrete Fourier Transform (DFT) [**[Code]**](https://github.com/OmarAlkousa/Learn-Fourier-Transform/blob/c4fae6a65d3233d62b9e45d1c0cf730f3bea5753/Understanding%20Discrete%20Fourier%20Transform%20(DFT)/Learning_Discrete_Fourier_Transform_(DFT).ipynb) [**[Towards Data Science]**](https://medium.com/towards-data-science/learn-discrete-fourier-transform-dft-9f7a2df4bfe9)

In this notebook, we will discuss how DFT works and how to implement it to output the spectrum of the signals. The functions we've built in this notebook are under MIT License and all credits go to the authors of [this book](https://pythonnumericalmethods.berkeley.edu/notebooks/Index.html). The figures below are the signal we want to analyze its spectrum, which is represented on the right below. Also, we discussed the Inverse Discrete Fourier Transform in the notebook.

<p align="center">
  <img src="https://github.com/OmarAlkousa/Learn-Fourier-Transform/blob/0aa07f1f7a792f38418c2c637f07dce1ddfdbf81/Understanding%20Discrete%20Fourier%20Transform%20(DFT)/The%20studied%20signal.png", width="350">
  <img src="https://github.com/OmarAlkousa/Learn-Fourier-Transform/blob/0aa07f1f7a792f38418c2c637f07dce1ddfdbf81/Understanding%20Discrete%20Fourier%20Transform%20(DFT)/first%20side%20DFT.png", width="350">
</p>

## Fourier Transform, the Practical Python Implementation [**[Code]**](https://github.com/OmarAlkousa/Learn-Fourier-Transform/blob/10bf85f103dd71e86659ae6ac78f772289ea0ccd/Fourier%20Transform,%20the%20Practical%20Python%20Implementation/Fourier_Transform,_the_Practical_Python_Implementation.ipynb)

The **Fast Fourier Transform (FFT)** is the practical implementation of the Fourier Transform on Digital Signals. FFT is considered one of the top 10 algorithms with the greatest impact on science and engineering in the 20th century [**[8]**](https://doi.ieeecomputersociety.org/10.1109/MCISE.2000.814652). In this notebook, a practical approach to FFT has been discussed as how to use it to represent the frequency domain (spectrum) of the signal data and plot the spectrum using **Plotly** to give us more interactivity and a better understanding of the features in the spectrum. By the end of this notebook, we'll build a class to analyze the signal. **An ECG signal and its spectrum have been provided as a final example**.

The figure below is a glimpse of what we will learn in this notebook.

<p align="center">
  <img src="https://github.com/OmarAlkousa/Learn-Fourier-Transform/blob/10bf85f103dd71e86659ae6ac78f772289ea0ccd/Fourier%20Transform,%20the%20Practical%20Python%20Implementation/Spectrum%20for%20%20real-value%20signal%20data.png", width="400">
</p>

The image below represents the Fourier class we build in this notebook (An ECG signal and its Frequency Spectrum). The use of the Plotly package allows you to hover over the values of the plot and zoom in/out on the interesting parts so easily.

<p align="center">
  <img src="https://github.com/OmarAlkousa/Learn-Fourier-Transform/blob/ed0892eb876796ec51339b371c153a3ddd831499/Fourier%20Transform%2C%20the%20Practical%20Python%20Implementation/ECG%20Time-Frequency%20Domains.gif", width="800">
</p>

## Acknowledgment:
[**[1]**](https://doi.org/10.1016/B978-0-08-097768-3.00011-8) R. Toulson, R., & Wilmshurst, T. (2012). An Introduction to Digital Signal Processing. *Fast and Effective Embedded Systems Design* (pp. 219–242). Elsevier. https://doi.org/10.1016/B978-0-08-097768-3.00011-8

[**[2]**](https://doi.org/10.1016/B978-0-08-099388-1.00003-0) T. Giannakopoulos, T., & Pikrakis, A. (2014). Signal Transforms and Filtering Essentials. *Introduction to Audio Analysis* (pp. 33–57). Elsevier. https://doi.org/10.1016/B978-0-08-099388-1.00003-0

[**[3]**](https://biblioteca.unisced.edu.mz/bitstream/123456789/1667/1/thinkdsp.pdf) Downey, A. (2016). Sounds and Signals. *Think DSP: Digital signal processing in Python* (pp. 1-11). (First edition). O’Reilly Media, Inc.

[**[4]**](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=da18cc0dc47a2e9f829bf752e86a985d0dcc22f3) Thakur, B., & Mehra, R. (2016). Discrete Fourier Transform Analysis with Different Window Techniques Algorithm. International Journal of Computer Applications, 975, 8887.

[**[5]**](https://pythonnumericalmethods.berkeley.edu/notebooks/chapter24.02-Discrete-Fourier-Transform.html) Kong, Q., Siauw, T., & Bayen, A. (2020). Fourier Transform. *Python programming and numerical methods: A guide for engineers and scientists* (pp. 415-444). Academic Press.

[**[6]**](https://numpy.org/doc/stable/reference/generated/numpy.fft.fft.html) Numpy Documentation, API Reference, Discrete Fourier Transform (numpy.fft). [Accessed at 2/2/2023]

[**[7]**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.fftpack.fft.html) Scipy Documentation, API Reference, Legacy discrete Fourier transform (scipy.fftpack). [Accessed at 2/2/2023]

[**[8]**](https://doi.ieeecomputersociety.org/10.1109/MCISE.2000.814652) Dongarra, J., & Sullivan, F. (2000). Guest Editors Introduction to the top 10 algorithms. *Computing in Science & Engineering*, 2(01), 22-23.

[**[9]**](https://www.ams.org/journals/mcom/1965-19-090/S0025-5718-1965-0178586-1/) Cooley, J. W., & Tukey, J. W. (1965). An algorithm for the machine calculation of complex Fourier series. *Mathematics of computation*, 19(90), 297-301.

[**[10]**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.fft.fft.html#scipy.fft.fft) Scipy Documentation, API Reference, Discrete Fourier Transforms (scipy.fft.fft). [Accessed on 23/2/2023]

[**[11]**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.fft.fftfreq.html#scipy.fft.fftfreq) Scipy Documentation, API Reference, Discrete Fourier Transforms (scipy.fft.fftfreq). [Accessed on 23/2/2023]

[**[12]**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.fft.rfft.html#scipy.fft.rfft) Scipy Documentation, API Reference, Discrete Fourier Transforms (scipy.fft.rfft). [Accessed on 23/2/2023]

[**[13]**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.fft.rfftfreq.html#scipy.fft.rfftfreq) Scipy Documentation, API Reference, Discrete Fourier Transforms (scipy.fft.rfftfreq). [Accessed on 23/2/2023]

[**[14]**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.misc.electrocardiogram.html#scipy.misc.electrocardiogram) Scipy Documentation, API Reference, Miscellaneous routines (scipy.misc.electrocardiogram). [Accessed on 23/2/2023]


## Keep in touch: [LinkedIn](https://www.linkedin.com/in/omar-alkousa).
