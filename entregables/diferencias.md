# Diferencias entre mi servidor local y hapi.fhir.org (R4)

1. **Versión del software (`software.version`)**
   - **Local:** `8.10.0`
   - **Público:** `8.13.10-SNAPSHOT/6bd250944e/2026-09-25`
   - **¿Por qué difiere?** Mi servidor local usa la versión 8.10.0 de HAPI FHIR. El servidor público usa una compilación de desarrollo, identificada por `SNAPSHOT`.

2. **Dirección base del servidor (`implementation.url`)**
   - **Local:** `http://localhost:8080/fhir`
   - **Público:** `https://hapi.fhir.org/baseR4`
   - **¿Por qué difiere?** Mi servidor corre en mi computador y lo consulto mediante `localhost` en el puerto 8080. El servidor público está disponible por HTTPS en el dominio `hapi.fhir.org`.