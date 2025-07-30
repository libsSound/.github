# iScillator

[![GitHub](https://img.shields.io/badge/GitHub-iScillator-blue.svg)](https://github.com/iScillator)

iScillator is a comprehensive hardware-software device for generating broadband therapeutic oscillations based on the principles of Georges Lakhovsky's Multi-Wave Oscillator (MWO).

## 📋 Description

The device consists of two main components:
- **Hardware**: High-voltage pulse generator based on modified Tesla coil and resonant antenna system (Lakhovsky antenna)
- **Software**: Cross-platform Flutter application SoundHealer for frequency and waveform control

## 🔬 Operating Principle

iScillator generates alternating high-voltage fields with a broad frequency spectrum through:
- Tesla transformer providing high alternating voltage (tens to hundreds of kilovolts)
- Concentric resonant rings of various diameters (Lakhovsky antenna)
- Creation of broadband harmonic fields to activate natural cellular oscillations

## ⚡ Technical Features

### Hardware
- **Generator**: Modified solid-state Tesla Coil (SSTC)
- **Antenna**: System of concentric metallic rings of different diameters
- **Power Supply**: Exclusively battery-powered (12-30V with step-up to tens of kV)
- **Safety**: Automatic disconnection from mains power during operation
- **Spark Gaps**: Special solid mercury spark gaps
- **Coil**: Modified with separate circuits (unlike standard automotive ignition coils)

### Software
- **Platforms**: Android, iOS (Flutter)
- **Audio Engine**: AudioKit for iOS
- **Features**:
  - Tone generation with smooth frequency changes (glissando)
  - Wide range of waveforms (sine, sawtooth, square, triangle)
  - Frequency preset system (Solfeggio, chakra frequencies)
  - User settings storage

## 🛠️ Installation and Assembly

### Application Requirements
- Flutter SDK
- Xcode (for iOS)
- Android Studio (for Android)

### Application Installation
```bash
git clone https://github.com/iScillator/iScillator-app.git
cd iScillator-app/app
flutter pub get
```

### Running the Application
```bash
# Android
flutter run -d <android-device-id>

# iOS
flutter run -d <ios-device-id>
```

### Hardware Assembly

#### Components
- Solid State Tesla Coil (SSTC) - x1
- Lakhovsky Antenna (concentric rings) - x1
- Battery pack (12-30V)
- Solid mercury spark gaps
- Insulation materials

#### Step-by-Step Assembly
1. **Generator**: Assemble or acquire SSTC with modified separate circuits
2. **Antenna**: Prepare metallic rings of different diameters and connect into unified radiating structure
3. **Connection**: Connect Tesla Coil output to antenna, observing polarity
4. **Power**: Use battery power only with automatic mains disconnection
5. **Safety**: Install shock-resistant insulators and spark gaps

## 🔌 Connecting to Application

### Connection Methods

#### 1. Audio Channel (Simple)
- Connect smartphone audio output to device input via 3.5mm jack
- Application generates sound oscillations at required frequency

#### 2. Wireless Connection (Advanced)
- Use Bluetooth/Wi-Fi module based on ESP32
- Application transmits commands wirelessly
- Microcontroller controls frequency and signal shape

## 📱 Usage

1. Launch iScillator application on smartphone
2. Select desired frequency or preset (e.g., "174 Hz – Muladhara")
3. Press play button ▶
4. Position radiator a few centimeters from subject
5. Conduct session for 5-30 minutes

### Example with Presets
```
iScillator App: Menu → Presets → 528 Hz (Solfeggio) → ▶
```

## ⚠️ Safety Measures

- **WARNING**: Device operates with high voltages (tens of kV)
- Use battery power only
- Avoid touching device during operation
- Ensure reliable insulation of all components
- Recommended to bring your own discharged battery to sessions
- Device automatically disconnects from mains power during operation

## 🔋 Power Supply Features

- **Batteries Only**: Device operates exclusively on battery power
- **Automatic Disconnection**: Switch disconnects device from mains during operation
- **Charging**: Mains power used only for battery charging in standby mode
- **Recommendation**: Use your own discharged battery to avoid influence of electronic entities

## 📚 Theoretical Foundations

### Lakhovsky Technologies
- **Multi-Wave Oscillator (MWO)**: Classic "frequency spiral"
- **Cellular Oscillation**: Hypothesis of bioresonance under RF field exposure
- **Resonant Oscillations**: Activation of natural healthy cell oscillations

### Frequency Presets
- **Solfeggio**: 174 Hz, 285 Hz, 396 Hz, 417 Hz, 528 Hz, 639 Hz, 741 Hz, 852 Hz, 963 Hz
- **Chakra Frequencies**: Muladhara, Svadhisthana, Manipura, etc.
- **Custom**: Ability to create personal frequency programs

## 🔧 Technical Documentation

### Connection Diagram
```
Battery → Inverter → Tesla Coil → Lakhovsky Antenna
              ↑
    Control signal from application
```

### Specifications
- **Input Voltage**: 12-30V DC (battery)
- **Output Voltage**: 10-100 kV AC
- **Frequency Range**: 1 Hz - 100 kHz
- **Waveforms**: sine, square, sawtooth, triangle
- **Modulation**: AM, FM, glissando

## 📖 Additional Resources

- [Lakhovsky Historical Materials](https://github.com/iScillator)
- [Modern MWO DIY Projects](https://github.com/iScillator)
- [Scientific Reviews of Bioresonance Therapy](https://github.com/iScillator)

## ⚖️ Legal Information

**IMPORTANT**: All described technologies are experimental. iScillator makes no medical claims and implements Lakhovsky's historical ideas in amateur form. The device is intended exclusively for research and educational purposes.

## 🤝 Contributing

We welcome contributions to the project:
- Bug reports and improvement suggestions
- Documentation and translations
- New frequency presets and algorithms
- Hardware improvements

## 📄 License

This project is distributed under the MIT License. See LICENSE file for details.

---

*Georges Lakhovsky (1869-1942) - Russian-French scientist, inventor of the Multi-Wave Oscillator, pioneer in bioresonance therapy.*
