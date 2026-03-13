## A-color-recognition-system-for-the-blind-and-robots

#Mobile Color Recognition System (CNN + Embedded)

This project involves the design and implementation of a low-cost, portable color recognition system dedicated to the visually impaired and robotic platforms (M2M). The system performs real-time classification to assist in daily activities and autonomous data exchange.

#Key Features
-Real-time Processing: Inference time of 230–320 ms with 90% classification accuracy.

Edge AI: Custom Convolutional Neural Network (CNN) trained on a proprietary dataset.

Optimization: Model quantized to INT8 and converted to TensorFlow Lite for efficient embedded performance.

M2M Readiness: Provides a digital UART interface transmitting data in JSON format for integration with master systems and robots.

Hardware Stack
Computing: Raspberry Pi Zero 2 W

Vision: Raspberry Pi Camera Module 3

Power: Waveshare UPS HAT (Lithium battery management)

Audio: MAX98357A I2S Amplifier + 40mm Speaker for voice feedback

Software & Tools
Frameworks: TensorFlow / TensorFlow Lite

Language: Python

Communication: UART (JSON-based protocol)
