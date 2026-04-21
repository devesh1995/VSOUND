
# VSOUND


# MAX9708 / MAX9708ETN / MAX9708ETN_D IC Based Audio Amplifier Board

This evaluation board features the MAX9708 IC, a high-efficiency Class D audio power amplifier from Analog Devices (formerly Maxim Integrated) that requires minimal components.

<img src="/images/3D_front.png" alt="Logo">

<img src="/images/3D_front 2.png" alt="Logo">

<img src="/images/3D_back.png" alt="Logo">



# Hardware
## Schematic

<img src="/images/schematic.png" >


## PCB Layout


<img src="/images/layout_front.png" >
<img src="/images/layout_back.png" >





## The MAX9708 Family of  Class D audio power amplifier IC

The MAX9708 is a high-efficiency, Class D audio power amplifier IC from Analog Devices/Maxim Integrated designed for stereo or mono applications, commonly used in flat-panel TVs, automotive systems, and portable audio systems. It delivers up to 2 x 21W into 8Ω (stereo) or 1 x 42W into 4Ω (mono) from a single 10V to 18V supply

### Key Features and Benefits

| Feature | Benefit |
| :--- | :--- |
| **High Efficiency & Performance** | Up to 87% efficiency with low 0.1% THD+N, providing Class AB performance with Class D benefits. |
| **Filterless Design** | Reduces component count and saves board space, crucial for compact designs. |
| **Spread-Spectrum Modulation** | Reduces EMI emissions, eliminating the need for bulky output filters. |
| **Operating Modes** | Switchable between stereo (2 x 21W) and mono (1 x 42W) modes. |
| **Flexible Gain Settings** | Four selectable-gain settings (22dB, 25dB, 29.5dB, and 36dB). |
| **Protection & Diagnostics** | Features thermal-overload and short-circuit protection, along with a programmable thermal flag. |
| **System Synchronization** | Includes a sync input/output (600kHz to 1.2MHz) to cascade multiple units. |


### Technical Specifications

| Specification | Details |
| :--- | :--- |
| **Output Power** | 2 x 21W (8Ω, 10% THD+N) / 1 x 42W (4Ω, 10% THD+N) |
| **Supply Voltage** | +10V to +18V (Single Supply) |
| **Package Type** | 56-pin TQFN (8mm x 8mm x 0.8mm) with exposed pad |
| **Operating Temperature** | -40°C to +85°C |




### Gain Control Configuration

| G1 | G2 | Gain (dB) |
| :--- | :--- | :--- |
| R12 | R14 | 22 |
| R11 | R14 | 25 |
| R11 | R13 | 29.5 |
| R12 | R13 | 36 |

**Note:** Populate the designated slots with **10kΩ 0402** resistors to set the desired gain. **See the back side of the board.**



