# SpringBoot-HTTPS
An HTTPS endpoint example using Spring Boot

#### Reference: [Tech Primers](https://www.youtube.com/watch?v=rm9OKTSm-4A)

#### Command to generate the certificate
```aidl
keytool -genkey -alias https-springboot -storetype JKS -keyalg RSA -keysize 2048 -validity 365 -keystore https-springboot.jks
```

#### Demo
 - Accessing the endpoint without HTTPS
  ![Without HTTPS](demo/Without%20HTTPS.png)

 - Accessing with HTTPS along with certificate details
 ![With HTTPS](demo/With%20HTTPS%20Certificate.png)