# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:

![WhatsApp Image 2025-11-06 at 21 25 21_5748e7cc](https://github.com/user-attachments/assets/477c28e9-2ac2-4613-bea6-05c878c0b0ad)
![WhatsApp Image 2025-11-06 at 21 25 20_bf246f08](https://github.com/user-attachments/assets/399907b3-e381-47cd-8752-9dfd459e9527)



## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 

```
num=[1];
den=[1 15 50 0];
sys=tf(num,den);
rlocus(sys);
[k,poles]=rlocfind(sys)
```

## Output:

<img width="689" height="621" alt="image" src="https://github.com/user-attachments/assets/972c3aae-aef5-4eb6-854e-85d2d7472016" />
<img width="1064" height="328" alt="image" src="https://github.com/user-attachments/assets/412359d8-0c2b-4a7c-b74c-34dac16ae9a7" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.5551
