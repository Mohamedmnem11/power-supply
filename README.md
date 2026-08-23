# Linear Power Supply

A simple **12V regulated linear power supply** designed, simulated using **Proteus**, and implemented as a practical circuit.

## Project Overview

The project is designed to convert an AC input into a stable **12V DC output**.

The circuit consists of several stages:

**AC Input → Transformer → Bridge Rectifier → Filter Capacitor → Voltage Regulator → 12V DC Output**

The circuit was first tested and verified using **Proteus simulation**, then implemented practically to verify the actual circuit operation.

## Components Used

* Transformer (XFMR)
* Bridge Rectifier
* 7812 Voltage Regulator
* Polarized Capacitor (CAP_POL)
* 1000µF Capacitor
* LED
* 100kΩ Resistor
* 460MΩ Resistor
* Connection Pins

## How It Works

### 1. Transformer

The transformer steps down the AC input voltage to a lower AC voltage suitable for the circuit.

### 2. Bridge Rectifier

The bridge rectifier converts the AC voltage into pulsating DC voltage.

### 3. Filtering

The capacitors are used to smooth the rectified voltage and reduce the voltage ripple.

### 4. Voltage Regulation

The **7812 voltage regulator** provides a regulated output of approximately **12V DC**.

### 5. LED Indicator

The LED is used to indicate that the power supply is operating and voltage is available at the output.

## Simulation

The complete circuit was designed and tested using **Proteus Design Suite** before the practical implementation.

The Proteus project files are included in this repository.

## Practical Implementation

After verifying the circuit in Proteus, the power supply was built and tested practically.

The practical implementation was used to verify the circuit behavior and ensure that the expected regulated DC output was obtained.

## Tools

* Proteus Design Suite
* Electronic Components & Practical Circuit Assembly
* Git & GitHub

## Repository Files

The repository contains the Proteus project files and related simulation files:

```text
Linear Power Supply.pdsprj
Linear Power Supply.DO
Linear Power Supply.EDF
Linear Power Supply.log
Linear Power Supply.sts
Backup Of Linear Power Supply.pdsbak
Last Loaded Linear Power Supply.pdsbak
```

## Main Concepts

* AC to DC conversion
* Transformer
* Bridge rectification
* Capacitive filtering
* Voltage regulation
* 12V DC power supply
* Proteus circuit simulation
* Practical electronics implementation

## Author

**Mohamed Abdelmonem**

GitHub: [Mohamedmnem11](https://github.com/Mohamedmnem11)
