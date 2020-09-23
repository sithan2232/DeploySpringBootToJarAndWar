# DeploySpringBootToJarAndWar

Remind myself

1.เพิ่ม <packaging>war</packaging> เข้าไปใน pom.xml

![](https://github.com/sithan2232/DeploySpringBootToJarAndWar/blob/master/image/Screen%20Shot%202563-09-23%20at%2021.45.01.png)

2.เพิ่ม dependency เข้าไปตามรูป

![](https://github.com/sithan2232/DeploySpringBootToJarAndWar/blob/master/image/Screen%20Shot%202563-09-23%20at%2021.46.17.png)

3.ใน springbootapplication ทําการ extends SpringBootServletInitializer ตามภาพ

![](https://github.com/sithan2232/DeploySpringBootToJarAndWar/blob/master/image/Screen%20Shot%202563-09-23%20at%2021.47.57.png)

4.Override configure เพื่อ deploy ตามภาพ

![](https://github.com/sithan2232/DeploySpringBootToJarAndWar/blob/master/image/Screen%20Shot%202563-09-23%20at%2021.49.19.png)

5.สุดท้ายกด package ใน maven ตามรูป

![](https://github.com/sithan2232/DeploySpringBootToJarAndWar/blob/master/image/Screen%20Shot%202563-09-23%20at%2021.50.32.png)

6.จะได้ file ทั้งหมดอยู่ใน target (เสริมเราสามารถ copy file application.properties ออกมาจาก src>main>resources เอามาวางไว้ข้างๆ file jar,war เพื่อเขียนค่า config เเก้ทับลงfile application.properties อันเก่าในโค้ดได้)
