## Thông tin Sinh viên
- Họ và tên : **Nguyễn Minh Nhật**
- MSSV : **25127446**

## Hướng dẫn biên dịch
``` Bash
$ g++ main.cpp -o  app
```
## Hướng dẫn chạy 
```Bash 
$ ./out/app
```


```mermaid 
classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }