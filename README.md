# HelloServo


REF: Using a PCA9685 module with Raspberry Pi

https://www.aranacorp.com/en/using-a-pca9685-module-with-raspberry-pi/

pip3 install adafruit-circuitpython-servokit

sudo python3 HelloServo.py 

# Next 
1. Use Li Battery
> 3cell的電池無法用在power board上面, charge IC跟電路沒有找到Input電壓過低無法使用的限制
3. Servo code
> 把兩種code(web-server跟servo control)合起來
> 寫註解
>>MIN/MAX_IMP PWM domain
>>MIN/MAX_ANG Angle domain
>>以上兩個要互相對應到
3. moving mechanism
> pan-tilt 
> snake
> robot cat
> 自動平衡bicycle
4. mission
    1. live streaming(using flask)
    2. cat face tracking
