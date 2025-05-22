# EXP.NO.2-IMPLEMENTATION-OF-DIGITAL-MODULATION-TECHNIQUES
2.Implementation of Digital Modulation Techniques
    i) Amplitude Shift Keying (ASK)
    ii) Frequency Shift Keying (FSK)
    iii) Phase Shift Keying (PSK)

## AIM    
 To Study and Realize ASK,FSK and PSK Modulation and Demodulation using the Digital Modulation Trainer Kit. 
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
# ASK:
```
 Modulation:
1.Connect the carrier signal (e.g., sine wave) to the modulator input.
2.Connect the digital binary input signal (TTL square wave) as the message.
3.Use patch cords to link the ASK Modulator section.
4.Observe the modulated ASK signal on the DSO.
5.You should see the carrier turning ON and OFF based on the binary input (1 = carrier, 0 = no signal).
 Demodulation:
1.Connect the ASK modulated signal to the ASK Demodulator block.
2.View the demodulated output on the DSO.
3.Compare the recovered signal to the original binary input.
```
# FSK:
```
Modulation:
1.Connect two different frequency carriers to the modulator (depending on your kit – some use internal settings).
2.Apply the binary data as input.
3.Patch to the FSK Modulator.
4.Observe FSK signal on the DSO.
5.You’ll see the frequency of the carrier change based on the digital data (f₁ for 1, f₂ for 0).
Demodulation:
1.Feed FSK signal to the FSK Demodulator.
2.Observe the demodulated binary signal.
3.Compare with original message.
```
# PSK:
```
Modulation:
1.Apply the carrier and binary input to the PSK Modulator.
2.Patch accordingly using trainer kit ports.
3.Use the DSO to view PSK signal output.
4.The carrier should shift phase (e.g., 0° ↔ 180°) based on binary input.
Demodulation:
1.Connect PSK signal to PSK Demodulator.
2.Observe demodulated output on DSO.
3.Compare it with the original binary message.
```
## CIRCUIT DIAGRAM
![image](https://github.com/user-attachments/assets/18343cb4-7dd8-4bb4-ac7b-247b91b27d1a)
![image](https://github.com/user-attachments/assets/5e7a3cc2-8b06-486a-87e2-71e7ad4d6984)
## MODEL GRAPH
![image](https://github.com/user-attachments/assets/d1d923cd-41e1-4d59-89b7-c4768f1e9c79)
![image](https://github.com/user-attachments/assets/eaf12eec-a28f-46bb-81dc-1852cd03afb7)
![image](https://github.com/user-attachments/assets/2056ab5f-b4fc-46cf-a74f-28cbba44bfed)


## TABLE
![table](https://github.com/user-attachments/assets/b27e4e1d-75b0-44f1-b98a-e11b6e2678a4)

## OUTPUT GRAPHS
![WhatsApp Image 2025-05-22 at 12 36 28_a724765a](https://github.com/user-attachments/assets/83051c2a-5167-4471-a5e5-06d9d6c6820f)

![WhatsApp Image 2025-05-22 at 12 36 28_b8ab5762](https://github.com/user-attachments/assets/4e85304c-954b-4f40-883d-5e06ee1c403f)



## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques was verified successfully.
