# HALF_ADDER
# AIM:
To simulate and synthesis half adder using Vivado software.
# APPARATUS REQUIRED:
Vivado 2023.1 software.
# Truth Table:
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram:
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)
# Program:
     module halfadder( a, b, s, c) ;
     input a, b;
     output s, c;
     xor gl (s, a,b);
     and g2 (c, a,b);
     endmodule
# Elaborated Design:
![Screenshot (53)](https://github.com/DeepanAnbazhagan/HALF_ADDER/assets/164902865/9e65143e-e220-413b-9db7-5c8f51567bda)
# Output: 
![Screenshot (55)](https://github.com/DeepanAnbazhagan/HALF_ADDER/assets/164902865/2ecd6c3e-a67d-4055-97b3-18b46ca392b7)
# RESULT:
Thus the simulate and synthesis half adder verified successfully by using Vivado software.

