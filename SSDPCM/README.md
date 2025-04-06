# SSDPCM Algorithm implementation

### **Bytebeat 44100Hz.**

- Released: July 2024

An audio compression algorithm created by [TheAlgorithm](https://www.youtube.com/@thealgorithm). It is an improvement over DPCM (which can only add or subtract 1 to the last sample). Here the ideal step size is chosen by the [encoder](https://github.com/Sychamis/Improved-dpcm) for each 128 samples, which makes music sound clearer than DPCM, but struggles to render noise and high-pitched sounds. Nevertheless, it is still a significant improvement in quality that only requires 3% more memory.

Also I did not write the info about the bytebeat files in my dollchan bytebeat library folder.
