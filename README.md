# 🫀 CARDIO Dashboard — Instrucciones de despliegue

## Qué hace esta app

El usuario sube su Excel → elige una contraseña → descarga el dashboard HTML listo para compartir.  
El HTML resultante funciona **sin internet**, se abre en cualquier browser.

---

## Despliegue en Streamlit Cloud (gratis, 5 minutos)

### 1. Subir archivos a GitHub

En tu repo `JA-Sotelo` (o uno nuevo), crear una carpeta `cardio-dashboard` con estos 3 archivos:
- `app.py`
- `requirements.txt`
- `README.md`

### 2. Crear app en Streamlit Cloud

1. Entrar a [share.streamlit.io](https://share.streamlit.io)
2. **New app**
3. Seleccionar tu repo y el archivo `app.py`
4. Click **Deploy**

En 2 minutos tenés una URL del tipo:  
`https://ja-sotelo-cardio-dashboard.streamlit.app`

### 3. Compartir con el usuario

Le mandás la URL por WhatsApp o email.  
El usuario:
1. Entra a la URL
2. Sube su Excel
3. Elige su contraseña
4. Descarga el HTML
5. Lo comparte por email/Drive con quien quiera

---

## Seguridad

- La contraseña protege el acceso al dashboard HTML
- El HTML viaja encriptado si se comparte por Drive/email con TLS
- Para datos médicos sensibles, recomendamos contraseñas fuertes (ej: `Cardio@Junin2026`)

---

## Actualizar el dashboard

Si necesitás actualizar el diseño del dashboard, reemplazá `app.py` en GitHub  
y Streamlit Cloud se actualiza automáticamente.
