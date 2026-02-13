# minecraftserver


Puedes copiar y pegar todo esto en tu `README.md`:

---

```md
# 🎮 Servidor Minecraft Modded 1.20.1

¡Bienvenid@s al servidor! 👋  
Aquí tenéis todo lo necesario para poder conectaros sin problemas.

---

# 📦 Requisitos

Antes de entrar al servidor, necesitáis lo siguiente:

---

## ✅ 1. Minecraft Java Edition

Necesitáis tener instalada la versión oficial de **Minecraft Java Edition**.

---

## ✅ 2. Versión obligatoria

Es obligatorio usar exactamente:

```

Minecraft 1.20.1
Forge 47.3.0

```

En el launcher debéis seleccionar el perfil:

```

Forge 1.20.1 - 47.3.0

```

⚠️ Si usáis otra versión, no os dejará entrar.

Podéis descargar Forge desde:
https://files.minecraftforge.net/

---

## ✅ 3. Tailscale (VPN privada)

El servidor está protegido mediante una red privada usando **Tailscale**.

Es obligatorio tener Tailscale instalado para poder conectarse.

Descarga:
https://tailscale.com/download

Pasos:

1. Instalar Tailscale.
2. Iniciar sesión.
3. Pedirme acceso a la red (tengo que aprobaros manualmente).

Sin acceso a la red Tailscale no podréis entrar.

---

# 📦 Instalación de Mods

Todos debéis tener exactamente los mismos mods que el servidor.

Descarga del paquete de mods:
https://drive.google.com/file/d/1VoCfU1AaK5HAf7G53C4VwmpmLWdIgD3L/view?usp=sharing

---

## 📂 Cómo instalar los mods (Windows)

1. Pulsad `Win + R`
2. Escribid:

```

%AppData%

```

3. Entrad en la carpeta:

```

.minecraft

```

4. Dentro debe existir (o crear) la carpeta:

```

mods

```

5. Extraed el contenido del `.zip` dentro de la carpeta:

```

.minecraft/mods

```

⚠️ No pongáis el archivo `.zip` sin extraer. Hay que descomprimirlo.

---

# 🌐 Cómo conectarse

1. Abrís Minecraft.
2. Seleccionáis el perfil:

```

Forge 1.20.1 - 47.3.0

```

3. Vais a **Multijugador**.
4. Añadís servidor con esta IP:

```

100.78.144.125

```

5. ¡Entráis y listo! 🎉

---

# 🧪 Diagnóstico de conexión (si algo no funciona)

Si no podéis conectar, podéis hacer estas comprobaciones desde Windows (PowerShell):

---

## 🔹 Comprobar si la IP responde

```

ping 100.78.144.125

```

⚠️ Puede fallar aunque el servidor funcione si el ping está bloqueado.

---

## 🔹 Comprobar si el puerto de Minecraft está abierto

```

Test-NetConnection 100.78.144.125 -Port 25565

```

Si todo está correcto, debería aparecer:

```

TcpTestSucceeded : True

```

Si aparece `False`, puede ser porque:

- El servidor está apagado.
- Tailscale no está conectado.
- El firewall está bloqueando la conexión.

---

## 🔹 Verificar estado de Tailscale

```

tailscale status

```

Debéis ver vuestra IP 100.x.x.x y la del servidor en la lista.

---

# ⚠️ Problemas comunes

## ❌ No conecta

- Revisad que estéis usando:
```

Minecraft 1.20.1
Forge 47.3.0

```
- Revisad que el perfil seleccionado sea:
```

Forge 1.20.1 - 47.3.0

```
- Revisad que la IP sea:
```

100.78.144.125

```
- Comprobad que Tailscale esté activo.
- Reiniciad Minecraft.

---

## ❌ "Incompatible mods"

- Aseguraos de que la carpeta:
```

.minecraft/mods

```
contenga exactamente los mismos archivos que el zip descargado.
- Eliminad mods antiguos antes de copiar los nuevos.

---

# 🛠️ Información adicional del servidor

- Modo de juego por defecto: Survival
- Comandos habilitados
- Teletransporte con JourneyMap habilitado para OPs
- Máximo 10 jugadores simultáneos
- Puerto del servidor: 25565

---

# 📩 Contacto

Si algo no funciona, avisadme y lo solucionamos.

¡Nos vemos dentro! 🚀
```
