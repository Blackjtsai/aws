18_部署一個DB應用 - 還不行，還差一步設置
======================================

## 知識點

* 在公開網路中建立NAT網關
* 建立DB私有網路路由表，設置NAT網關
* 建立DB私有網路安全組，開放3306-Mssql端口

## 實戰演習

> 看圖說話

### NAT網關

+ Name : blackjtsaiaws-web-nat
+ Subnet : blackjtsaiaws-web-1a
+ ELastic IP (收費的 要刪掉喔~)

## 路由表

+ Name : blackjlearnaws-db-rtb
+ Target : blackjlearnaws-web-nat -> 0.0.0.0/0


### 安全組

+ Name : blackjlearnaws-db-sg
+ Port : 3306