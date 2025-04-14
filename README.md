**1.Experimental Verification Of Signal Sampling Using Various Types Such as i) Natural Sampling ii) Flat Top Sampling**

**AIM**

To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.

**APPARATUS REQUIRED**

Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)

**PROCEDURE**

**1.Natural Sampling**

1. Switch on the DCL-10 kit with correct power supply polarity.
2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT of buffer to IN of Flat Top Sampling block.
4. Set clock to Internal mode (INT clk) using switch Sw4.
5. Set sampling frequency to 8kHz using switch S1.
6. Set 50% duty cycle using switch Sw2.
7. Connect OUT of Flat Top Sampling block to IN1 of 2nd order Butterworth Low Pass Filter.
8. Observe output and repeat steps for 2kHz sine wave input.

**2. Sample and Hold**

1. Switch on the DCL-01 kit with correct power supply polarity.
2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT to IN of Sample and Hold block.
4. Set clock to Internal mode (INT clk) using switch Sw4.
5. Set sampling frequency to 8kHz using switch S1.
6. Set 50% duty cycle using switch Sw2.
7. Connect OUT of Sample and Hold block to IN1 of 2nd order Butterworth Low Pass Filter.
8. Observe output and repeat steps for 2kHz sine wave input.

**3. Flat Top Sampling**

1. Switch on the DCL-01 kit with correct power supply polarity.
2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT to IN of Flat Top Sampling block.
4. Set clock to Internal mode (INT clk) using switch Sw4.
5. Set sampling frequency to 8kHz using switch S1.
6. Set 50% duty cycle using switch Sw2.
7. Connect OUT of Flat Top Sampling block to IN1 of 2nd order Butterworth Low Pass Filter.
8. Observe output and repeat steps for 2kHz sine wave input.
   
**CIRCUIT DIAGRAM**

**NATURAL SAMPLING**

![image](https://github.com/user-attachments/assets/a8627b1d-4155-4703-9a77-faf3059508a3)

**SAMPLE AND HOLD**

![image](https://github.com/user-attachments/assets/08ca7bae-36a9-49a7-9fc2-d925e9647292)

**MODEL GRAPH**

**NATURAL SAMPLING**

![image](https://github.com/user-attachments/assets/93d3c9a9-94e5-4718-852a-a4a9c7b0e5c2)


**SAMPLE AND HOLD**

![image](https://github.com/user-attachments/assets/d383866c-826d-4aed-ae5f-7bf3e553c586)

**TABLE**

![WhatsApp Image 2025-04-14 at 14 52 33_d15be8a6](https://github.com/user-attachments/assets/b143d9ae-4054-4359-a8ec-4f5261f9d3e4)

**OUTPUT GRAPHS**

![WhatsApp Image 2025-04-14 at 14 53 17_122d6e52](https://github.com/user-attachments/assets/52280012-5657-4aca-846d-52e569aa820c)

![WhatsApp Image 2025-04-14 at 14 53 17_d83de3ff](https://github.com/user-attachments/assets/93c34cf1-805d-4ca2-9dd0-5aafa71d6fd1)


**RESULT**

Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
