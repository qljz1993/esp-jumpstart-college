# esp-jumpstart-college

## 课后作业&小项目

1. 端口配置
    红灯： GPIO21
    绿灯： GPIO22
    蓝灯： GPIO23
    ADC1： ADC_CHANNEL_6 GPIO34
    TCP/IP PORT：6666

2. LED 状态显示
    - 等待配网 红色闪烁
    - 正在配网 蓝色闪烁
    - 配网成功 绿色
    - 配网失败 红色
    - AD采集&数据传输 红色绿色交替

3. Button 重置设备
    - 单击 开/关 灯
    - 长按 重置设备
    


## 提交代码

1. 下载工程

```
git clone https://github.com/zhanzhaocheng/esp-jumpstart-college.git
```

2. 创建分支

```
git checkout -b <name>
```

3. 添加代码
将自己的代码复制到这工程中

4. 提交工程
```
git add .
git commint -m <commint>
git push origin <name>
```
