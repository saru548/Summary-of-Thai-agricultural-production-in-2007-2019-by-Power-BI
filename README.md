# Summary-of-Thai-agricultural-production-in-2007-2019-2550-2562-
แสดงข้อมูลผลผลิตทางการเกษตรของประเทศไทย ปี พ.ศ. 2550 ถึง 2562 (Summary of Thai agricultural production in 2007-2019) โดยนำเสนอแบบ visualization report 

- นำเสนอผ่านโปรแกรม Power BI

- ใช้ข้อมูล(Datasource) จากเว็บไซต์ www.data.go.th โดยข้อมูล Open Gevernment dataนี้ อนุญาตให้ประชาชนทั่วไปสามารถเข้าถึงข้อมูลภาครัฐได้

- ขอบคุณเว็บไซต์สำหรับดาวน์โหลด free icon  (Special Thanks for free icons) : <div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>

--------------------------------------------------
วิธีการทำงาน

1.ให้ดาวน์โหลดข้อมูล Datasource จากเว็บไซต์นี้  https://data.go.th/dataset/oae0001 .
![image](https://user-images.githubusercontent.com/61858648/129433806-207e12c5-07fe-4a0d-84f7-551472d8c8f9.png)


  ตัวอย่างข้อมูลชุดนี้เป็นไฟล์ xlsx เป็นดังนี้ค่ะ
  ![image](https://user-images.githubusercontent.com/61858648/129433958-ac7d1dbc-7135-4d68-b772-9d8c24f8cb80.png)
  
  
 2.เปิดโปรแกรม Power BI และ Import data csv ไฟล์ที่ดาวน์โหลดไว้ ในPower BI นี้เราสามารถจัดการเตรียมข้อมูล ทั้งการ Clean transform เพิ่มสูตรต่างๆ ได้ตามต้องการ ซึ่งนับว่าท่านใดที่มีความคุ้นเคยกับการใช้Excel ก็สามารถใช้งานโปรแกรมนี้ได้ไม่ยากเลยค่ะ
 
 3.ตัวอย่างหน้า Overview 
 
![image](https://user-images.githubusercontent.com/61858648/129445957-fdddfb05-0231-4e1e-a335-c7a5e19dfa21.png)


เราสามารถใช้ความสามารถของPower BI ในการแสดงผล 3 อันดับแรกของผลผลิตทางการเกษตรที่มีปริมาณสูงสุดแบ่งตามภูมิภาคได้ง่ายๆ โดยใช้คุณสมบัติของ Filters เข้ามาช่วยจัดการ ดังนี้ค่ะ

![image](https://user-images.githubusercontent.com/61858648/129445971-aff74d87-54da-45b0-9643-451d24b581ed.png)
![image](https://user-images.githubusercontent.com/61858648/129445977-d242dff1-ec7d-4bef-9ae3-1b2c9ca32e13.png)

 
4.ในแต่ละการแสดงข้อมูล เราสามารถคลิกขวาในรูปใดๆ และเลือกเมนู "Show data point as table" หลังจากนั้นจะมองเห็นข้อมูลraw data ดังเช่น

![image](https://user-images.githubusercontent.com/61858648/129446025-c99ad5a4-e79d-4497-9f90-a6a731fe5040.png)

![image](https://user-images.githubusercontent.com/61858648/129446064-ad400e8b-42bb-43fd-952a-d81d8d3c7ed3.png)


 
5.เราสามารถเลือกเงื่อนไขการแสดงข้อมูลได้ตามต้องการ  เช่น หากต้องการแสดงข้อมูลเฉพาะผลผลิตทางการเกษตรกลุ่มไม้ยืนต้น ก็เลือกได้เช่นกันค่ะ

จากรูปด้านล่าง กลุ่มไม้ยืนต้นนั้น ภาคใต้มีปริมาณผลผลิตมากถึง 86.54% และมาจากปาล์มน้ำมันมากสุดเป็นอันดับหนึ่ง
รองลงมาคือยางพารา และกาแฟ มาเป็นอันดับสาม

และผลผลิตมากที่สุดในปี 2561 ถึง 75ล้านตันเลยทีเดียว

![image](https://user-images.githubusercontent.com/61858648/129446101-22d2e4ae-c1ec-47f8-9fec-ac1533dbdf50.png)


6.หรืออยากให้แสดงเฉพาะข้อมูลกล่ม ไม้ผล ในระหว่างปี 2555 - 2562 ก็เลือกได้เช่นกันค่ะ

จากรูปด้านล่าง เราจะเห็นว่า ในช่วงปี 2555-2562 กลุ่มไม้ยืนผลนั้น 

ภาคเหนือมีปริมาณผลผลิตมากที่สุดเป็นอันดับหนึ่ง  โดย52.71% มาจากลำไย นั่นเอง

![image](https://user-images.githubusercontent.com/61858648/129446125-c217c473-3fe4-4807-bf9d-5e13fbf2963d.png)

----------------------------------------------------





