List of Contents 

# 1. ECG and EDA Equipment Overview
### 1.1. Hardware 

1. LiveAmp amplifier <br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/amplifier.jpg" width="30%">
2. Wireless trigger transmitter <br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/trigger_transmitter.jpg" width="30%">
3. Trigger box and the wireless trigger receiver <br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/trigger_extension.jpg" width="30%">
4. Recording laptop with the bluetooth receiver and the Recorder dongle <br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/laptop_dongles.jpg" width="30%">
5. Bluetooth receiver<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/Dongle_bluetooth.jpg" width="30%">
6. USB stick with software and manuals<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/manuals_software.jpg" width="30%">
7. Dongle for the BrainVision Recorder<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/Dongle_recorder.jpg" width="30%">
8. Cable to connect the amplifier with the trigger extension<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/cable2.jpeg" width="30%">
9. Cable to connect the power bank with the amplifier<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/USBadapter.jpg" width="30%">
10. Power bank with charger<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/powerbank.jpeg" width="30%">
11. BIP2AUX adapter with electrodes for ECG<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/connection_electrodes_bip2aux.jpeg" width="30%">
12. ECG electrodes (single-use)<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/singleuse_electrodes_all.jpeg" width="30%">
13. ECG electrodes (reusable)<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/ECG_electrodes.jpg" width="30%">
14. EDA Electrodes<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/eda.jpeg" width="30%">

### 1.2. Consumables 
1. Disinfection for the skin under the ECG and EDA electrodes<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/desinfection.jpg" width="30%">
6. Cotton pads for the disinfectant<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/Cotton_tampons.jpg" width="30%">
7. Abrasive electrolyte gel for ECG electrodes (needed only if you use reusable electrodes)<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/ECG_abrasive_gel.jpg" width="30%">
5. Adhesive circles for the ECG electrodes (needed only if you use reusable electrodes)<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/adhesive_rings.jpg" width="30%">
3. Syringes for ECG gel (needed only if you use reusable electrodes)<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/syringe_ecg.png" width="30%">
8. Pre-filled electrode caps for ECG (needed only if you use single-use electrodes)<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/singleuse_electrode.jpeg" width="30%">
8. Conductive gel for the EDA electrodes<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/eda_gel.png" width="30%">
9. Plaster to fix the EDA electrodes<br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/plaster_eda.png" width="30%">

# 2. Software Requirements 
To visualize the ECG and EDA signals during setup, you'll need the BrainVision Recorder. This tool allows you to monitor the electrode resistance and visualize the data in real-time. I do not have any experience with visualising or recording ECG and EDA data using the lab streaming layer (LSL). Hence, I will not elaborate on this option. However, it should be possible, afaik. 

**BrainVision Recorder:** This software can be installed from the provided USB stick, which also contains manuals. Alternatively, you can download the software from the BrainVision website. Follow the installation instructions available on the USB stick or the website. To use the BrainVision Recorder, ensure the BrainVision Recorder Dongle is plugged into your laptop. 

To synchronize data with the driving simulator, you can use the TCP trigger receiver and transmitter. Alternatively, you can use LSL. For more information and installation instructions, visit the LSL website: https://labstreaminglayer.org/#/. However, I only used LSL for EEG data and can't provide guidance for EDA and ECG recordings.  

## 2.1. Setting Up Workspace for ECG and EDA Recording 
1. Insert the software dongle. 
2. Open the BrainVision Recorder.
3. Click "Search for the LiveAmp" in the popup window. The LiveAmp must be on and the blue light must be blinking. Moreover, the Bluetooth dongle must be plugged into the laptop.  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/1.png" width="50%">
4. A window like this should pop up. You can see the serial number of the amplifier.  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/2.png" width="50%">  
   If the name of the amplifier says "Simulation", your amplifier was not detected. Check if the Bluetooth dongle is plugged in and the amplifier is on, blinking blue. Alternatively, check the power of the power bank.  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/99.png" width="50%">
5. Create a new workspace  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/4.png" width="50%">
6. Add the electrodes.   
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/eegx.png" width="50%">
7. Choose the sampling rate and the accelerometer from the amplifier, if you wish.
8. If you are using only ECG and EDA electrodes, indicate "0" for "EEG only", and check "Use sensor and triger extension". To "Auxiliary", write the number of AUX channels you will plug into the trigger extension (2 for both EDA and ECG, 1 if only one channel will be used). Change the names, scale, and units of the recorded signals. For EDA, insert "µS" as Diff. unit and "25" as Gradient. For ECG, insert "µV" as Diff. unit and "0.1" as Gradient. <br /> <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/worskpace_setup_values.png" width="30%">
9. Click next, keep the settings as it is. Do not apply any filters, always save raw data.
10. Click next; no segmentation/averaging during recording.  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/8.png" width="50%">
11. Save your workspace.  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/9.png" width="50%">  
   Once your workspace is saved, you can see its name in the bottom right corner.  
   <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/10.png" width="50%">
12. To see the signal, click the button with the symbol of the eye.
13. To start recording the data, press the icon with the green triangle. Once the data starts saving, you will see a red icon under your signal, which says "SAVING HDD".  
    <img src="https://github.com/nikol-figalova/HuFa_Ulm_EEG/blob/main/images/12.png" width="50%">
14. To stop the recording, press the icon with the red square.

# 3. Equipment Set Up 

## 3.1. ECG Set Up 

## 3.2. EDA Set Up 



Tips and Good Practices 




<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">
<br /> <img src="" width="30%">


