### JudgerServer 部署
```c++
sudo apt-get install libmysqlclient-dev

pip install mysqlclient

sudo python main.py
```
### Judger 部署

```c++

setting.json 修改配置文件

pip install mysqlclient
sudo apt-get install libseccomp-dev
mkdir build && cd build && cmake .. && make && sudo make install
cd ..
cd JudgerCore
sudo python setup.py install
cd ..
pip install paramiko
sudo apt install time
sudo apt install openjdk-8-jdk
sudo python main.py
```
#### notice
` 注意需要python3 pip3