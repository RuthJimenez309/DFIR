Este proyecto simula una investigación forense correlacionada frente a una intrusión real de ransomware, abordando tres capas críticas de análisis.

## Estructura del Proyecto
* Network_PCAP/: Los flujos de trafico sospechosos e identificación de IoCs de red (Simulado).
* Memory_Dumps/: Procesamiento de volcados de memoria RAM para la detección de inyecciones de código (Simulado).
* OS_Artifacts/: Parsing profundo del Registro de Windows, Prefetch y logs de eventos EVTX (Simulado).
* Consolidated_Report/: Informes tecnicos y cronología unificada de los hallazgos.

## Hallazgos Clave
1. **Red:** Exfiltración de credenciales en texto plano mediante HTTP y descarga del binario malicioso.
2. **Memoria:** Inyección de código detectada en el proceso legítimo svchost.exe (PID 1044).
3. **Host:** Persistencia mediante llaves de registro y correlación horaria mediante análisis.

