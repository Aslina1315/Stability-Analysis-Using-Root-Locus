# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 22 29 04_1f5cbbe8](https://github.com/user-attachments/assets/b777bcff-4dcd-4494-94ca-925c0b70e06a)
![WhatsApp Image 2025-11-27 at 22 29 17_0b5076cc](https://github.com/user-attachments/assets/fae0fef6-73e6-46b6-91d3-f26e4e2b3256)
![WhatsApp Image 2025-11-27 at 22 29 31_8d4ccdd3](https://github.com/user-attachments/assets/9b085bac-9827-4c22-812b-ab0e30a42f10)
<img width="967" height="1280" alt="image" src="https://github.com/user-attachments/assets/8834c11e-8d04-415c-bb06-e4a236120c6e" />


## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
num=[1]<br>
den=[1 15 50 0]<br>
sys=tf(num,den)<br>
rlocus(sys)<br>
[k poles]=rlocfind(sys)<br>

## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/01dff336-c54c-4a1e-82b7-8508b099f72b" />


## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 750
