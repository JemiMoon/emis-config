1. Create a keystore

keytool -genkeypair -alias jemi-test-key -keyalg RSA \
-dname "CN=Jemi Config Server, OU=Jemi, O=Jemi, L=QC, C=PH" \
-keypass 0face_local -keystore jemi-config-dev.jks -storepass 0face_local \
-validity 365