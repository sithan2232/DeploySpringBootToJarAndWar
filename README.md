# DeploySpringBootToJarAndWar

Remind myself

1.เพิ่ม <packaging>war</packaging> เข้าไปใน pom.xml

รูป

2.เพิ่ม dependency เข้าไปตามรูป

รูป

3.ใน springbootapplication ทําการ extends SpringBootServletInitializer ตามภาพ

รูป

4.Override configure เพื่อ deploy ตามภาพ

รูป

5.สุดท้ายกด package ใน maven ตามรูป

รูป

6.จะได้ file ทั้งหมดอยู่ใน target (เสริมเราสามารถ copy file application.properties ออกมาจาก src>main>resources เอามาวางไว้ข้างๆ file jar,war เพื่อเขียนค่า config เเก้ทับลงfile application.properties อันเก่าได้)
