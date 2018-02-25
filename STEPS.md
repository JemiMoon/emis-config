# Development Steps

#### Create a keystore

```
keytool -genkeypair -alias jemi-test-key -keyalg RSA \
-dname "CN=Jemi Config Server, OU=Jemi, O=Jemi, L=QC, C=PH" \
-keypass 0face_local -keystore jemi-config-dev.jks -storepass 0face_local \
-validity 365
```

### 

#### Encrypt and Decrypt







##### Reference

[Encrypting and  Decrypting Configuration Property Values in Spring Cloud]: https://patrickgrimard.io/2016/03/04/encrypting-and-decrypting-configuration-property-values-in-spring-cloud/	" ENCRYPTING AND DECRYPTING CONFIGURATION PROPERTY VALUES IN SPRING CLOUD"

