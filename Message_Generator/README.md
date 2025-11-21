
# 📨 Message Generator

Generador de mensajes personalizados en Python.  
Este proyecto solicita datos al usuario (nombre y pasatiempo) y construye un mensaje de bienvenida utilizando una arquitectura modular y profesional.

---

## 🚀 Características

- Entrada interactiva mediante `input()`
- Validación de datos del usuario
- Limpieza y formateo del texto
- Generación automática de un mensaje personalizado
- Arquitectura modular usando:
  - `main.py` → punto de entrada del programa
  - `builder.py` → lógica principal
  - `utils.py` → utilidades (validación y formateo)

---

## 📂 Estructura del Proyecto

message_generator/
├── src/
│ ├── main.py
│ └── generator/
│ ├── init.py
│ ├── builder.py
│ └── utils.py
└── README.md


---

## 🛠️ Instalación

Clonar el repositorio:

    git clone https://github.com/csodcaceres/Proyectos_Python.git

Ingresar al proyecto:

    cd Proyectos_Python/message_generator


---

## ▶️ Ejecución

Ejecutar el programa:

    python src/main.py

## 💬 Ejemplo de Uso

=== Message Generator ===
Enter your name: Oscar
Enter your favorite hobby: programar

---- Welcome Message -----
Hello Oscar!
Welcome to the world of programming.
It's great to know that you enjoy Programar.
Get ready to explore and create amazing things!

## 🧱 Módulos principales

### **builder.py**
Contiene la clase `MessageBuilder`, encargada de generar el mensaje final.

### **utils.py**
Incluye funciones auxiliares:
- `validate_input()`
- `format_text()`

### **main.py**
Controla el flujo del programa y gestiona la interacción con el usuario.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Podés usarlo y modificarlo libremente.

---

## 👤 Autor

**Oscar Caceres**  
Desarrollador Python & Data Science  
GitHub: https://github.com/csodcaceres  
LinkedIn: (https://www.linkedin.com/in/oscardanielcaceres/)  