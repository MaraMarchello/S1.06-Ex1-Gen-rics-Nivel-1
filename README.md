# S1.06-Ex1-Gen-rics-Nivel-1
# Ejercicio de Métodos No Genéricos

## 📄 Descripción
Este ejercicio implementa una clase `NoGenericMethods` que maneja tres argumentos de tipo Object. La clase está diseñada para garantizar que todos los argumentos sean del mismo tipo en tiempo de ejecución, lanzando una excepción si se intenta utilizar tipos diferentes.

## 💻 Tecnologías Utilizadas
- Java 8+
- JUnit 5 (para pruebas unitarias)
- Maven (gestor de dependencias)

## 📋 Requisitos
- JDK 8 o superior instalado
- Maven 3.6 o superior
- IDE compatible con Java (recomendado: IntelliJ IDEA o Eclipse)

## 🛠️ Instalación
1. Clonar el repositorio
2. Navegar al directorio del proyecto
3. Compilar el proyecto


## 🌐 Despliegue
Este proyecto es una biblioteca de clases y no requiere despliegue en servidor. Puede ser incluido como dependencia en otros proyectos Java.

## 🤝 Contribución
1. Hacer un fork del repositorio
2. Crear una rama para tu funcionalidad (`git checkout -b feature/NuevaFuncionalidad`)
3. Hacer commit de tus cambios (`git commit -m 'Añadir nueva funcionalidad'`)
4. Hacer push a la rama (`git push origin feature/NuevaFuncionalidad`)
5. Crear un Pull Request

## ⚠️ Notas Importantes
- La clase valida que todos los argumentos sean del mismo tipo en tiempo de ejecución
- Se lanzará `IllegalArgumentException` si se intentan mezclar tipos diferentes
- Los métodos getter devuelven Object y requieren casting al tipo específico
