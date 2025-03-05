# TryHackmeWriteUpEviction

# Eviction - Análisis de APT28 en E-corp



## 📌 Descripción
Este proyecto documenta el análisis de la amenaza APT28 en la infraestructura de E-corp utilizando MITRE ATT&CK Navigator. Se identifican tácticas, técnicas y procedimientos (TTPs), así como medidas de detección y mitigación para prevenir el compromiso de la red.

![image](https://github.com/user-attachments/assets/d204a64f-b268-4c69-8377-47d733d78c74)

## 🔍 Análisis de la amenaza

![image](https://github.com/user-attachments/assets/b7442008-08ab-4432-84f5-d7cce89734cb)

### 🛠️ **Tácticas y técnicas identificadas**

![image](https://github.com/user-attachments/assets/d87c01ce-75eb-4be2-be6f-7505cfeee5de)


1. **Reconocimiento y acceso inicial**  
   - 🎯 *Técnica utilizada:* Spearphishing link
   - 📧 *Cuentas comprometidas:* Email accounts

2. **Ejecución de código malicioso**  
   - 📌 *Técnicas observadas:* Malicious file y Malicious link
   - 💻 *Interpretes de comandos utilizados:* Powershell y Windows Command Shell

3. **Persistencia y evasión de defensas**  
   - 🛑 *Claves de registro modificadas:* Registry run keys
   - 🚀 *Binario del sistema utilizado para evasión:* Rundll32

4. **Descubrimiento y movimiento lateral**  
   - 🕵️ *Técnica de descubrimiento:* Network sniffing
   - 🔄 *Servicios explotados:* SMB/Windows Admin shares

5. **Exfiltración de datos**  
   - 🎯 *Objetivo del ataque:* SharePoint
   - 🚧 *Técnicas de exfiltración frustradas:* External proxy y Multi-hop proxy

## 🚀 Conclusión
Gracias a la detección temprana y una respuesta efectiva, se impidió que APT28 lograra su objetivo de robar información crítica de E-corp. La correlación de eventos y la identificación de TTPs permitieron mitigar la amenaza y fortalecer la seguridad de la organización.

## 📎 Recursos
- [MITRE ATT&CK Navigator](https://mitre-attack.github.io/)
- [APT28 - MITRE ATT&CK](https://attack.mitre.org/groups/G0007/)

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar este análisis o agregar información adicional, no dudes en enviar un pull request o abrir un issue.

## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT.
