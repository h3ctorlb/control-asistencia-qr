# control-asistencia-qr
# 📲 Control de Asistencia - Escáner QR

Una aplicación web para registrar la asistencia del personal mediante escaneo de códigos QR, con integración directa a Google Sheets. Ideal para controlar entradas, salidas y descansos en tiempo real desde cualquier navegador.

---

## 🚀 Características

- ✅ Registro de entradas, salidas y descansos (desayuno y comida)
- 📷 Escaneo de QR usando la cámara del dispositivo
- 🧠 Reconocimiento de tipo de registro según historial del empleado
- 📊 Integración con Google Sheets vía Google Apps Script
- 🧪 Modo de prueba con botones simulados
- ⏰ Visualización de fecha y hora en tiempo real
- 🔒 Interfaz de configuración para visualizar empleados y últimos registros
- 📤 Exportación de registros a CSV

---

## 🛠️ Tecnologías utilizadas

- HTML5 + JavaScript (vanilla)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- Google Apps Script (API externa para Google Sheets)

---

## 📦 Cómo usar

1. **Clona este repositorio:**

   ```bash
   git clone https://github.com/h3ctorlb/control-asistencia-qr.git

   	2.	Abre index.html en tu navegador.
No se requiere servidor backend.
	3.	Configura tu script de Google Apps Script:
	•	Crea un nuevo script en Google Apps Script
	•	Pega el siguiente ejemplo de código (te lo puedo dar si lo necesitas)
	•	Publica el script como aplicación web y copia el URL
	•	Sustituye GOOGLE_SCRIPT_URL en el código con ese URL
	4.	Escanea códigos QR de tus empleados
(puedes usar cualquier generador QR con IDs como EMP001, EMP002, etc.)

⸻
🧪 Pruebas y demostraciones

Puedes simular registros sin escanear códigos QR usando los botones de prueba disponibles en la interfaz.

⸻

⚠️ Consideraciones
	•	La app requiere permisos de cámara en el navegador.
	•	La conexión con Google Sheets puede fallar si el script no está correctamente publicado o si el navegador bloquea la solicitud no-cors.

    📄 Licencia

Este proyecto está bajo la licencia MIT, puedes modificarlo y usarlo libremente.

👨‍💻 Autor
🧪 Proyecto en constante evolución, alimentado por curiosidad.
Creado y mantenido por Héctor Legorreta.
