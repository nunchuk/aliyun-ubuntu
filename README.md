<!--![image](./logo.png =60)-->
<img src="https://raw.githubusercontent.com/nunchuk/aliyun-ubuntu/master/logo.png" width="60" />

# Ubuntu Docker Image 

This Docker image is based on the Docker official Ubuntu image with chinese localization.

* `14.04`,`trusty`

## Modified list

* `SOURCES REPOSITORY`
	Specifies the *[Aliyun open source mirror](http://mirrors.aliyun.com/)* instead of a given repository.

* `NETWORK TIME PROTOCAL`
	Specifies the *Aliyun public NTP server*.
	
* `SECURITY UPDATE`
	Update packages: *bash, glibc, openssl, wget, ntp*.
	
* `TIMEZONE`
	Set Timezone and synchronize system clock to *Asia/Shanghai*.	
	
* `DNS`
	Configure network settings to use *[Aliyun public DNS servers](http://alidns.com/)*.

Contributors
-------------------
* XinYe (nunchuk@live.com)