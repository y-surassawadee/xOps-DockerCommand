# xOps-DockerCommand

## ```docker-compose -f docker-compose.yml up -d```
-  docker-compose เอาไว้ RUN compose ไฟล์
 
## ```docker-compose up -d``` 
-  เป็นคำสั่งให้ container ทำงาน 
-  "-d" = option ที่ใช้กำหนดว่า ให้รันแบบ background process
    
## ```docker-compose down```
-  เป็นคำสั่งลบ containers, networks, volumes, และ images ที่ถูกสร้างโดยคำสั่ง up ทั้งหมด

## ```docker ps```
-  เป็นคำสั่งแสดง container ที่ทำงานอยู่ เอาไว้เช็คว่า container ทำงานหรือไม่

## ``` docker rm db -f ```
-  docker rm เป็นคำสั่งลบ container
-  db -f เป็นการระบุชื่อ container เพื่อลบ

## ```docker exec -it <container_name> <command>```
-  เป็นคำสั่ง SSH เข้าไปใน container เช่น docker exec -it db mysql -u root -p
