#นายพชรนันท์ จันทร์รักษ์ 57030198
#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้
![](https://github.com/Patcharanan/LAB-05/blob/master/img/1.PNG?raw=true)

 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้

![](https://github.com/Patcharanan/LAB-05/blob/master/img/2.PNG?raw=true)



###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร

 * เป็นการดึงข้อมูลที่อยู่หลัง เครื่องหมายคอมม่า(,) ออกมาแสดงในบรรทัดนั้นๆ โดยข้อมูลสามารถกำหนดได้ว่าจะเอาข้อมูลตัวไหนออกมาแสดงถ้าหลังเครื่องหมาย , มีข้อมูลอยู่ 


###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย

 * สามารถใช้งานได้ ถ้าเป็นกรณีตามโจทย์ จะต้องมีข้อมูลอยู่ทั้งหมด 4ตัว หมายถึง {0} ดึงข้อมูลตัวที่ 1 / {2} ดึงข้อมูลตัวที่ 3 / {3} ดึงข้อมูลตัวที่ 4  


2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้
![](https://raw.githubusercontent.com/Patcharanan/LAB-05/efbce563b2b5348bcd8fb789ded8de4c0c4ccf82/img/3.PNG)

 * เป็นการแสดงค่าออกมาโดยดึงข้อมูลตัวที่ 2 ,1 และ 2 ในข้อมูล 3, 6 จะได้ผล -> 6 ,3 and 6

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้
![](https://github.com/Patcharanan/LAB-05/blob/master/img/4.PNG?raw=true)

* เป็นการโชว์เลข 1 ตามตำแหน่งที่กำหนดไว้ตามตำแหน่ง {0,x},1 ; ปล. x คือตำแหน่งที่กำหนดไว้

###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร

 * หน้าเครื่องหมาย , ตัวแรกนั้นคือ ตำแหน่งของข้อมูลในบรรทัด ว่าจะเอาข้อมูลตัวที่เท่าไหร่ออกไปแสดง และเลขหลังเครื่องหมาย , คือ เอาตัวเลขด้านหน้าไปวางไว้ที่ตำแหน่ง 
 เท่าไหร่ นับไปตามแกน x 


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้
  
![](https://github.com/Patcharanan/LAB-05/blob/master/img/5.PNG?raw=true)


5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  ![](https://github.com/Patcharanan/LAB-05/blob/master/img/6.PNG?raw=true)

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้

![](https://github.com/Patcharanan/LAB-05/blob/master/img/7.PNG?raw=true)

## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```

![](https://github.com/Patcharanan/LAB-05/blob/master/img/8.PNG?raw=true)
#นายพชรนันท์ จันทร์รักษ์ 57030198
