# Computer-Architecture
## CLIP 1
<br>[Click here CLIP1](https://www.youtube.com/watch?v=4Xmycxsm4yo)
<br>![image](Instruction-formats-for-MIPS-architecture-1.png)
<br>คำสั่ง ADD ใน MIPS  จะอยู่ในคำสั่ง R-format จะประกอบด้วย 
<br>1.$rs(register rs) จะเก็บบิทขนาด 5 บิท
<br>2.$rd(register rd) จะเก็บบิทขนาด 5 บิท
<br>3.$rt(register rt) จะเก็บบิทขนาด 5 บิท
 
 ![image](IMG_0826.jpg)
 <br>โดยคำสั่งใน MIPs จะเก็บด้วยตัวเลยจำนวน 32 บิท โดย 6 บิทเเรกจะเป็น 000000 คือ opcode ตามด้วย rs rt rd shamt(ขนาด 5 บิท) เเละ func ขนาด 6 บิท หลังจากนั้นเราจะเเปลงเป็นเลขฐาน 16 โดยการเเปลงทีละ 4 บิท
 
 
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
## CLIP 2
<br>[Click here CLIP2](https://www.youtube.com/watch?v=0mXmTB-i86c&t=37s)

<br>โดยทั่วไปคอมพิวเตอร์ จะสามารถทำงานเเละเข้าใจคำสั่งโดย ใช้ภาษา Machine Language โดยภาษาที่เรามนุษย์ เขียนจะเป็นภาษาชั้นสูงเช่น JAVA,PYTHON,C,C+,C++,C#

<br>จากรูปเราใช้ถาษาจาวา
```
=====Java Language
Class Test {
    Public static void main(String[] args){
      int a = 10 ;
      int b = 20 ;
      int c = a+b ;
=====Machine Language in memory)
00000000:      j 01000000
00000004:      1A000000         //data
...
01000000:      lw $9, $0(4)
01000004:      lw $1, $9(0)     // $1,a = 10
01000008:      lw $2, $9(4)     // $2,b = 20
0100000C:      add $3, $1, $2
01000010:      sw $3, $9(8)
...
1A000000:      0000000A         //a
1A000004:      00000014         //b
1A000008:      00000000         //c
```
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
## CLIP 3
<br>[Click here CLIP3](https://www.youtube.com/watch?v=90x-axC5oNs&t=4s)
```
111111111111111111111111111111111111111111111111112222222222222222222222222222222222222222222222333333333333333333333333333333333333333333332222222222222222222222222222222222222222222222222222222222222222
```
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
## CLIP 4
<br>[Click here CLIP4](https://www.youtube.com/watch?v=WPbhgIni8XY&t=61s)
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
## CLIP 5
<br>[Click here CLIP5](https://www.youtube.com/watch?v=IW1H2A5DxqA&t=4s)
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
## CLIP 6
<br>[Click here CLIP6](https://www.youtube.com/watch?v=NIqQllKFryg&t=1s)
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
## CLIP 7
<br>[Click here CLIP7](https://www.youtube.com/watch?v=OmpTHug1bIA&t=2s)
*************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************
