# Prototipo Funcional de Gestión de Riesgos Informáticos - TRL 5
### Universidad Nacional Abierta y a Distancia (UNAD)
**Curso:** Proyecto de Grado (Código: 202016907)  
**Caso de Estudio:** Plan de Ciberseguridad y Continuidad de Negocio para Granados y Arismendi S.A.S. (Bogotá D.C.)

---

## 📑 Información General del Componente Práctico
* **Estrategia Metodológica:** Aprendizaje Basado en Proyectos (Scrum)
* **Nivel de Maduración Tecnológica:** TRL 5 (Tecnología validada en entorno relevante/simulado)
* **Periodo Académico:** Noviembre 2026

## 👥 Integrantes (Equipo de Desarrollo Scrum)
* **Carlos Adolfo Granados Camargo** (Ingenieria de Sistemas)
* **Luisa Fernanda Pérez Meza** (Ingenieria de Sistemas)
* **Tutor del Curso:** Daniel Andrés Guzmán Arevalo

---

## 💻 Características del Prototipo Ejecutable
Este software fue diseñado de forma nativa en **Python** empleando una arquitectura lógica de tres capas para automatizar la gestión de la seguridad de la información bajo los dominios del estándar **GTC-ISO/IEC 27002**:
1. **Autenticación (RF-01):** Control de acceso seguro para el rol de administración de infraestructura.
2. **Cálculo de Riesgo Automatizado (RF-04):** Mapeo de variables ordinales ejecutando el modelo matemático de matriz de probabilidad e impacto ($R = P \times I$).
3. **Alertas Condicionales Críticas (RF-05):** Filtrado descendente automatizado que resalta en color rojo los vectores críticos de ataque (ej. Ransomware).
4. **Despliegue del Plan de Contingencia (RF-06):** Vinculación de salvaguardas técnicas y manuales de respuesta rápida en interfaces visuales ligeras (`Tkinter`).
5. **Persistencia Local (RNF-06):** Almacenamiento seguro relacional embebido mediante el motor **SQLite**.

---

## 🛠️ Requisitos e Instrucciones de Ejecución
Para ejecutar este software en cualquier estación de trabajo convencional (Windows/Linux/MacOS) de la organización, siga los siguientes pasos:

### 1. Prerrequisitos
Asegúrese de contar con Python instalado en su sistema operativo. Adicionalmente, instale las librerías necesarias mediante la consola de comandos corporativa:
```bash
pip install pandas openpyxl
```

### 2. Despliegue del Sistema
1. Descargue el archivo ejecutable del script `app.py` de este repositorio.
2. Ejecute el programa desde la terminal del sistema:
   ```bash
   python app.py
   ```
3. Ingrese con las credenciales por defecto del sistema de auditoría:
   * **Usuario:** `admin`
   * **Contraseña:** `unad2026`
