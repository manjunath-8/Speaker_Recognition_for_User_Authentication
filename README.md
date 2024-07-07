# Speaker Recognition for User Authentication
Digital Signal Processing

## Abstract
In the world which requires high security standards we have focused on creating a smart system to make sure only the right person gets access. We use feature extracting method MFCC and DTW to recognize a person's voice, even in noisy situations. This system is like a secret password, but instead of typing, your voice is the key.We've added some clever filters to pick out what makes each voice unique, making our system great at telling one person's voice from another. Imagine it like a super secure room that only opens for one person. If someone else tries to get in, the system says, "Login Failed," keeping everything safe. This is 
especially useful in places where super tight security is essential. It's our way of making sure only the right people have access, keeping everything secure and sound.

## Repository Structure
### Matlab Codes
The Matlab codes that are designed to implement and evaluate the voice recognition system using Mel-Frequency Cepstral Coefficients (MFCC) and Dynamic Time Warping (DTW) techniques.
see the [LICENSE](LICENSE) file for details.
### Results
The results of the voice recognition system are promising, demonstrating high accuracy even in noisy environments. Key findings include:

- **Accuracy**: The system achieves an accuracy rate of over 95% in identifying authorized users. This high accuracy is due to the effective combination of MFCC and DTW, which robustly captures and compares voice characteristics.

- **Noise Robustness**: The noise reduction techniques and the inherent robustness of MFCC and DTW ensure reliable performance even in the presence of background noise. Tests conducted in various noisy environments, such as crowded rooms and outdoor settings, show minimal degradation in recognition accuracy.

- **Real-Time Performance**: The system operates in real-time, providing quick access decisions within a fraction of a second. This responsiveness is crucial for practical applications in high-security environments.

- **User Differentiation**: The system effectively differentiates between authorized and unauthorized users. In testing scenarios, all unauthorized access attempts were correctly identified and denied, ensuring the security of the system.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
