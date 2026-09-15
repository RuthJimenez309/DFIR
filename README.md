Este proyecto simula una investigaci�n forense correlacionada frente a una intrusi�n real de ransomware, abordando tres capas cr�ticas de an�lisis.

## ?? Estructura del Proyecto
* Network_PCAP/: An�lisis de flujos de tr�fico sospechosos e identificaci�n de IoCs de red (Simulado).
* Memory_Dumps/: Procesamiento de volcados de memoria RAM para la detecci�n de inyecciones de c�digo (Simulado).
* OS_Artifacts/: Parsing profundo del Registro de Windows, Prefetch y logs de eventos EVTX (Simulado).
* Consolidated_Report/: Informes t�cnicos y cronolog�a unificada de los hallazgos.

## ?? Hallazgos Clave
1. **Red:** Exfiltraci�n de credenciales en texto plano mediante HTTP y descarga del binario malicioso.
2. **Memoria:** Inyecci�n de c�digo detectada en el proceso leg�timo svchost.exe (PID 1044).
3. **Host:** Persistencia mediante llaves de registro y correlaci�n horaria mediante an�lisis de Prefetch.

