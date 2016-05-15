![image](./logo.png =60x60)

# Ubuntu Docker Image With Chinese Localization

This Docker image is based on the Docker official Ubuntu image, and adapt to the network environment of China.

* `14.04`,`trusty`

## Modified list

* `SOURCES REPOSITORY`
	Specifies the [Aliyun open source mirror](http://mirrors.aliyun.com/) instead of a given repository.

* `NETWORK TIME PROTOCAL`
	Specifies the Aliyun public NTP server.
	
* `SECURITY UPDATE`
	Update packages: bash, glibc, openssl, wget, ntp.
	
* `TIMEZONE`
	Set Timezone and synchronize system clock to Asia/Shanghai.	
	
* `DNS`
	Configure network settings to use Aliyun public DNS servers.

Contributors
-------------------
* XinYe (nunchuk@live.com)