<h1 align="center">
<p> Fourier and Wavelet Transforms :memo:</p>
<p align="center">
<img alt="ubuntu" src="https://img.shields.io/badge/ubuntu-%3E%3D18.04-blueviolet?style=for-the-badge&logo=ubuntu">
<img alt="python" src="https://img.shields.io/badge/python-%3E%3D3.6-blue?style=for-the-badge&logo=python">
<img alt="numpy" src="https://img.shields.io/badge/numpy-%3E%3D1.19-skyblue?style=for-the-badge&logo=numpy">
</p>
</h1>
<h1 align="left">
<p> Table of Contents </p>
</h1>

- [Introduction](#introduction)
- [Fourier series and Fourier transforms](#fourier-series-and-fourier-transforms)
- [Discrete Fourier transform (DFT) and fast Fourier Transform (FFT)](#discrete-fourier-transform-dft-and-fast-fourier-transform-fft)
- [Transforming partial differential equations](#transforming-partial-differential-equations)
- [Gabor transform and the spectrogram](#gabor-transform-and-the-spectrogram)
- [Wavelet and multi-resolution analysis](#wavelet-and-multi-resolution-analysis)
- [2D transforms and image processing](#2d-transforms-and-image-processing)
- [References](#references)

## Introduction
The most foundational and ubiquitous coordinate transformation was introduced by J,-B. Joseph Fourier in the early 1800s in investigate the theory of heat [[1](#jean-baptiste-joseph-fourier-the-analytical-theory-of-heat-the-university-press-1878)]. Fourier introduced the concept that sine and cosine functions of increasing frequency provide an orthogonal basis for the space of solution functions. Indeed, the Fourier transform basis of sines and cosines serve as eigenfunctions of the heat equation, with the specific frequncies serving as the eigenvalues, determined by the geometry, and amplitudes determined by the boundary conditions.

Fourier's seminal work provided the mathematical foundation for Hilbert spaces, operator theory, approximation theory, and the subsequent revolution in analytical and computational mathematics. Fast forward two hundred years, and the fast Fourier transform has become the cornerstone of computational  mathematics, enabling real-time image and audio compression, global communication networks, mordern devices and hardware, numerical physics and enineering at scale, and advanced data analysis. Simply put, the fast Fourier transform has had a more significant and profound role in shaping the modern world than any other algorithm to date.

With increasingly complex problems, data sets, and computational geometries, simple Fourier sine and cosine bases have given way to tailored bases, such as the data-driven SVD. In fact, the SVD basis can be used as a direct analogue of the Fourier basis for solving PDEs with complex geometries. In addition, related functions, called wavelets, have been developed for advanced signal processing and compression efforts,

## Fourier series and Fourier transforms

## Discrete Fourier transform (DFT) and fast Fourier Transform (FFT)

## Transforming partial differential equations

## Gabor transform and the spectrogram

## Wavelet and multi-resolution analysis

## 2D transforms and image processing

## References

- #### [Jean Baptiste Joseph Fourier. The analytical theory of heat. The University Press, 1878](https://www.cambridge.org/core/books/analytical-theory-of-heat/F6D4802336FABD1116DDA4AA3FE6EFAA).
    