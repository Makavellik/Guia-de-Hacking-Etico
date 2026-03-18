# 🧠🛡️ Hacking Ético para Iniciados: Fundamentos de Redes

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=Ethical%20Hacking%20%7C%20Networking%20Foundations&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FFC6&center=true&vCenter=true&width=600&lines=Aprende+Redes+como+un+Hacker+%C3%89tico;Piensa+en+Sistemas%2C+no+en+Respuestas;De+la+Curiosidad+a+la+Estrategia" />
</p>

> "No se trata de romper sistemas… se trata de entenderlos mejor que nadie."

---

## 🎯 Objetivo

Aprender las bases de redes necesarias para empezar en ciberseguridad y pentesting de forma **ética, profesional y estratégica**.

---

# 🌐⚡ REDES DESDE CERO A NIVEL MAESTRO

> "No uses internet… entiéndelo." 🧠

---

# 🧠✨ ¿QUÉ ES UNA RED?

Una red no es solo dispositivos conectados.

## 💡 Definición:

Una red es un sistema dinámico donde múltiples entidades intercambian información utilizando reglas (protocolos), permitiendo comunicación, procesamiento y respuesta eficiente de datos.

---

# 🧩 🔥 ARQUITECTURA FUNDAMENTAL DE UNA RED

```
┌──────────────┐
│ DISPOSITIVOS │  → generan / reciben datos
└──────┬───────┘
       ↓
┌──────────────┐
│    DATOS     │  → paquetes de información
└──────┬───────┘
       ↓
┌──────────────┐
│ DIRECCIONES  │  → IP / MAC
└──────┬───────┘
       ↓
┌──────────────┐
│ PROTOCOLOS   │  → reglas de comunicación
└──────────────┘
```

---

# 🖥️📱🌍 1. DISPOSITIVOS (LOS ACTORES)

Ejemplos:

* 💻 Computadora
* 📱 Teléfono
* 🌍 Servidor
* 📡 Router
* 🔌 Switch

💡 Función:

> Generar, procesar o redirigir información.

---

# 📦⚡ 2. DATOS (LO QUE REALMENTE VIAJA)

Todo en internet se convierte en:

* Texto
* Imágenes
* Video
* Audio

Pero en red →

```
DATA → PAQUETES → TRANSMISIÓN
```

## 🧠 Ejemplo:

Una imagen NO viaja completa.

Se divide así:

```
[Parte1] [Parte2] [Parte3] [Parte4]
```

Y luego se reconstruye en tu dispositivo.

---

# 🧭🌍 3. DIRECCIONAMIENTO (A DÓNDE VA TODO)

Cada dispositivo tiene identidad:

* IP → dirección lógica (como tu casa)
* MAC → identidad física (como huella única)

## 💡 Ejemplo:

```
Origen: 192.168.1.10
Destino: 142.250.190.78
```

Sin esto → el internet sería caos total.

---

# 📜🔗 4. PROTOCOLOS (LAS REGLAS DEL JUEGO)

Los protocolos definen:

* Cómo enviar datos
* Cómo recibirlos
* Cómo verificar errores

## 🔥 Ejemplos clave:

* HTTP → páginas web
* HTTPS → seguro
* TCP → confiable
* UDP → rápido pero sin garantía

---

# ⚙️🚀 FLUJO REAL (LO QUE PASA AL ENTRAR A UNA WEB)

```
[1] Escribes URL
[2] DNS → traduce a IP
[3] Se establece conexión
[4] Se envían paquetes
[5] Servidor responde
[6] Navegador reconstruye
```

## 🧠 CLAVE:

No viaja una web…

👉 viajan MUCHOS paquetes
👉 llegan en distinto orden
👉 se reconstruyen

---

# 📦🧠 ANALOGÍA PRO (ESTILO AMAZON)

Imagina que pides algo:

* Se divide en paquetes
* Toman rutas distintas
* Llegan desordenados
* Tú los armas

💥 Eso es internet.

---

# 🌍📡 TIPOS DE REDES

## 🏠 LAN

* Casa / oficina
* Rápida

## 🌆 MAN

* Ciudad

## 🌍 WAN

* Internet completo

💡 Internet = red de redes

---

# 🧠⚡ MENTALIDAD DE MAESTRO

Un principiante ve:

> "conexión"

Un profesional ve:

* 🔁 flujo de datos
* 📍 rutas
* ⚠ fallos
* 🔓 riesgos
* ⚡ eficiencia

---

# 🧪🔥 EJEMPLO TÉCNICO REAL

Cuando envías un mensaje:

```
Mensaje → dividido en paquetes

Cada paquete contiene:
- origen
- destino
- datos
```

Luego:

```
viajan → llegan → se ordenan → se reconstruyen
```

---

# ⚡🧠 NIVEL AVANZADO

Una red no solo conecta…

👉 coordina comportamiento

Ejemplo:

* Click → respuesta
* Mensaje → confirmación
* Error → reintento

---

# 🎯 RETO 

Responde:

👉 ¿Qué pasa si un paquete se pierde?

Pistas:

* ¿Se reenvía?
* ¿Quién lo detecta?
* ¿Cómo sabe?

---
---

# 🧠⚡ FRASE FINAL

> "El que entiende la red… controla el flujo de la información." 🔥

---


---

# 🔥⚡ TCP vs UDP — NIVEL DIOS

> "Velocidad vs Confiabilidad… tú decides." 🧠⚡

---

# 🧠✨ ¿QUÉ SON TCP Y UDP?

Son protocolos de transporte que definen **cómo viajan los datos en la red**.

* TCP → confiable 🛡️
* UDP → rápido ⚡

---

# ⚔️ COMPARACIÓN DIRECTA

```
TCP                        UDP
--------------------      --------------------
Confiable ✔               No confiable ❌
Lento 🐢                  Rápido ⚡
Ordenado 📦               Desordenado 🔀
Conexión previa 🤝        Sin conexión 🚫
Reenvío de datos 🔁       Sin reenvío ❌
```

---

# 🧠 📦 TCP — EXPLICACIÓN PRO

TCP asegura que los datos:

* lleguen completos
* lleguen en orden
* se reenvíen si fallan

## 🔄 Flujo TCP:

```
1. Handshake (conexión)
2. Envío de datos
3. Confirmación (ACK)
4. Reenvío si falla
```

## 💡 Ejemplo:

* Navegar en una web
* Descargar archivos
* Enviar correos

💥 Porque necesitas que TODO llegue bien.

---

# ⚡ 🚀 UDP — EXPLICACIÓN PRO

UDP envía datos:

* sin verificar
* sin confirmar
* sin esperar

## 🔄 Flujo UDP:

```
Enviar → listo
```

## 💡 Ejemplo:

* videojuegos online 🎮
* streaming 🎥
* llamadas VoIP 📞

💥 Porque importa más la velocidad que la perfección.

---

# 🧠🔥 DIFERENCIA FILOSÓFICA

TCP dice:

> "Prefiero que llegue bien aunque tarde"

UDP dice:

> "Prefiero llegar rápido aunque falle"

---

# 🧪 ⚡ EJEMPLO REAL

## 🎮 Juego online

* Si usas TCP → lag 😵
* Si usas UDP → fluido 😎

## 📥 Descargar archivo

* Si usas UDP → corrupto 💀
* Si usas TCP → perfecto ✅

---

# 🛠️⚡ HERRAMIENTAS PROFESIONALES

## 🔍 Análisis de tráfico

* Wireshark
* tcpdump

## 🌐 Pruebas de red

* netcat (nc)
* iperf

## 🧠 Diagnóstico

* ping
* traceroute

---

# 🧪 🔥 PRUEBAS PRÁCTICAS

## 📡 TCP con netcat

```
nc -lvp 4444
```

## 📡 UDP con netcat

```
nc -u -lvp 4444
```

---

# 🧠⚠️ PUNTOS CLAVE PRO

* TCP usa control de flujo
* TCP usa control de congestión
* UDP no controla nada
* TCP es más pesado
* UDP es más ligero

---

# ⚡ 🧠 MENTALIDAD MAESTRO

No preguntes:

> "¿Cuál es mejor?"

Pregunta:

> "¿Cuál necesito según el problema?"

---

# 🎯 RETO PRO

👉 Si estás haciendo una app de videollamadas...

¿usarías TCP o UDP?

¿por qué?

---

# 🧠⚡ FRASE FINAL

> "El verdadero poder no está en enviar datos… está en elegir cómo enviarlos." 🔥

---


---

# 📡 3. Conceptos Clave

## 🔹 Dirección IP

Identificador único de un dispositivo en la red.

Ejemplo:

```
192.168.1.1
```

## 🔹 DNS

Traduce nombres a IP.

```
google.com → 142.250.x.x
```

## 🔹 Protocolo

Reglas de comunicación.

Ejemplos:

* HTTP
* HTTPS
* TCP
* UDP

---

# 🚪 4. Puertos (LA CLAVE 🔥)

Un puerto es como una "puerta" dentro de un sistema.

Cada servicio usa uno.

### Ejemplos importantes:

| Puerto | Servicio | Uso                       |
| ------ | -------- | ------------------------- |
| 80     | HTTP     | Web sin cifrado           |
| 443    | HTTPS    | Web segura                |
| 22     | SSH      | Acceso remoto seguro      |
| 21     | FTP      | Transferencia de archivos |

## 🧠 Visualización

```
[ IP: 192.168.1.1 ]
   ├── Puerto 80  → Web
   ├── Puerto 22  → SSH
   └── Puerto 443 → HTTPS
```

👉 IP = casa
👉 Puerto = puerta específica

---

# 🔍 5. ¿Por qué importan los puertos?

Porque indican:

* qué servicios están activos
* posibles puntos de entrada
* configuraciones débiles

⚠️ IMPORTANTE:
Siempre analizar con permiso.

---

# ⚙️ 6. Ejemplos Reales (Modo Ético)

## 🔹 Escenario 1: Verificar si un servidor responde

```
ping ejemplo.com
```

## 🔹 Escenario 2: Ver conexiones activas en tu equipo

```
netstat -an
```

## 🔹 Escenario 3: Identificar IP de un dominio

```
nslookup ejemplo.com
```

💡 Esto NO es hackear… es entender la red.

---

# 💻 7. Comandos Básicos Explicados

## 🔹 ping

Envía paquetes para verificar si un host está activo.

## 🔹 netstat

Muestra conexiones abiertas y puertos en uso.

## 🔹 nslookup

Consulta el DNS.

## 🔹 tracert / traceroute

Muestra el camino que siguen los datos.

---

# 🧠 8. Diagrama de Flujo (Nivel Pro)

```
Solicitud → DNS → IP → Puerto → Servicio → Respuesta
```

💥 Aquí está TODO el flujo de internet simplificado.

---

# 🛡️ 9. Mentalidad de Hacker Ético

* Pensar en sistemas
* Entender comunicación
* Detectar patrones
* Actuar con responsabilidad

---

# ⚖️ 10. Ética

Siempre:

* Tener permiso
* No causar daño
* Reportar vulnerabilidades

---

# 🚀 11. Siguiente Nivel

Aprender:

* Modelo OSI
* TCP vs UDP
* Escaneo de red avanzado
* Seguridad en redes

---

# 🌌 Frase Final (Modo Legendario)

> "El verdadero poder no está en explotar… sino en comprender." 🔥

---

## ✨ Autor

Guía creada para mentes curiosas que quieren ir más allá 🚀


<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=Wireshark%20Lab%20%7C%20Network%20Analysis&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FFC6&center=true&vCenter=true&width=700&lines=Analiza+paquetes+como+un+pro;Entiende+TCP+%26+UDP+en+tiempo+real;De+la+captura+al+diagn%C3%B3stico" />
</p>

# 🧪⚡ LABORATORIO PRÁCTICO — WIRESHARK (NIVEL PRO)

> "Si puedes ver los paquetes… puedes entender la red." 🧠🔥

---

# 🎯 OBJETIVO

Aprender a **capturar, filtrar y analizar tráfico real** para:

* identificar protocolos
* detectar problemas
* entender el flujo de datos

---

# 🛠️ HERRAMIENTAS

* Wireshark (principal)
* ping (generar tráfico)
* navegador web (HTTP/HTTPS)

---

# ⚙️ PREPARACIÓN

## 🧠 Paso 1 — Abrir Wireshark

1. Ejecuta Wireshark
2. Selecciona tu interfaz:

   * WiFi
   * Ethernet
3. Presiona **Start Capture**

---

# 🔍 CAPTURA BÁSICA

## ⚡ Paso 2 — Generar tráfico

Mientras capturas:

```
ping google.com
```

y abre cualquier página web.

💡 Esto genera tráfico real para analizar.

---

# 🧠 ENTENDIENDO LA INTERFAZ

Wireshark tiene 3 zonas clave:

## 📦 1. Lista de paquetes

* cada línea = un paquete
* verás protocolo, origen, destino

---

## 🔬 2. Detalles del paquete

Aquí puedes ver:

* capas (Ethernet, IP, TCP/UDP)
* flags
* tamaño

---

## 🧾 3. Datos en bruto

* contenido hexadecimal
* nivel más bajo

---

# 🎯 FILTROS (LO MÁS IMPORTANTE)

## 🔥 Filtros básicos:

```
ip

tcp

udp

http

```

---

## 🎯 Filtros PRO:

### Ver tráfico hacia una IP

```
ip.addr == 8.8.8.8
```

### Solo TCP

```
tcp
```

### Solo UDP

```
udp
```

### HTTP

```
http
```

💥 Aquí es donde empieza el verdadero poder.

---

# 🧪 LABORATORIO 1 — ANALIZAR PING (ICMP)

## 🧠 Objetivo

Ver cómo funciona un ping internamente.

## ⚙️ Pasos:

1. Inicia captura
2. Ejecuta:

```
ping google.com
```

3. Filtra:

```
icmp
```

## 🔍 Qué observar:

* request (ida)
* reply (respuesta)
* tiempo (latencia)

💡 Esto mide la velocidad de tu red.

---

# 🧪 LABORATORIO 2 — TCP EN ACCIÓN

## 🧠 Objetivo

Ver cómo funciona la comunicación confiable.

## ⚙️ Pasos:

1. Abre una web
2. Filtra:

```
tcp
```

## 🔍 Qué observar:

* SYN
* SYN-ACK
* ACK

💥 Esto es el famoso **3-way handshake**.

---

# 🧪 LABORATORIO 3 — HTTP / HTTPS

## 🧠 Objetivo

Ver tráfico web real.

## ⚙️ Pasos:

1. Abre una página
2. Filtra:

```
http
```

## 🔍 Qué observar:

* GET
* respuesta del servidor

💡 En HTTPS no verás contenido (está cifrado 🔐)

---

# 🧠 DETECCIÓN DE PROBLEMAS

## ⚠️ Latencia alta

* paquetes tardan mucho

## ⚠️ Retransmisiones TCP

* indica pérdida de paquetes

## ⚠️ Tráfico sospechoso

* conexiones extrañas

---

# ⚡ TRUCOS PRO

* usa filtros siempre
* sigue una conversación TCP (clic derecho)
* analiza tiempos entre paquetes

---

# 🧪 MISIÓN FINAL

Haz esto:

1. Captura tráfico
2. Abre una web
3. Encuentra:

   * IP origen
   * IP destino
   * protocolo
   * handshake TCP

---

# 🧠⚡ NIVEL MAESTRO

Cuando domines esto podrás:

* leer tráfico real
* detectar fallos
* entender ataques
* optimizar redes

---

# 🔥 FRASE FINAL

> "Wireshark no muestra datos… muestra la realidad de la red." ⚡

---
