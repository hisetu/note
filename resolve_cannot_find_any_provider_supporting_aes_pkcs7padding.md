# 解決Cannot find any provider supporting AES/CBC/PKCS7Padding #

https://www.bouncycastle.org/java.html

## download UnlimitedJCEPolicyJDK8 ##
http://www.oracle.com/technetwork/java/javase/downloads/jce8-download-2133166.html

## unzip to ##
C:\Program Files\Java\jdk1.8.0_112\jre\lib\security

## edit java.security ##
add
security.provider.11=org.bouncycastle.jce.provider.BouncyCastleProvider

Done!
