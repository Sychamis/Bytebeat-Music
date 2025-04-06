# Karplus-Strong Algorithm implementation

### **Floatbeat 48000Hz.**

- Released: July 2024

A dead simple way to generate string noises:
- Generate a noise array of length (sampleRate / noteFrequency),
- Loop on it and filter it as it's played (like setting the value of the current sample as the average of that sample and the previous one),
- That's it!
