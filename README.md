# ABCchallenge 🔤

Página web interactiva para enseñar el abecedario a niños. Proyecto grupal desarrollado como sprint de rescate en el laboratorio de **Generation Colombia**.

## Tecnologías

HTML · CSS · JavaScript vanilla

## Estructura del proyecto

```
abcchallenge/
├── index.html   # Estructura de la página
├── style.css    # Estilos y efecto flip
└── script.js    # Lógica interactiva
```

## Funcionalidades

- **26 cards** — una por cada letra del abecedario, con imagen y palabra al voltear
- **Efecto flip** — animación CSS al hacer clic en cada card
- **Contador de progreso** — registra cuántas letras nuevas ha descubierto el usuario
- **Filtro de contenido** — botones para ver solo vocales o todas las letras
- **Sección del equipo** — créditos del equipo de rescate al final de la página

## Cómo correr el proyecto

1. Clonar el repositorio:
   ```bash
   git clone <URL-del-repo>
   ```
2. Abrir `index.html` en el navegador — no requiere servidor ni dependencias.

## Flujo de trabajo en Git

Cada integrante trabaja en su propia rama según el bloque de letras asignado:

```bash
git checkout -b letras-A-E
# ... trabajar y hacer commits frecuentes ...
git push origin letras-A-E
```

El líder hace merge de cada rama a `main` al finalizar.

**Distribución sugerida (5 personas):** A–E · F–J · K–O · P–T · U–Z

## Equipo

| Integrante | Letras |
|------------|--------|
| Nombre 1   | A – E  |
| Nombre 2   | F – J  |
| Nombre 3   | K – O  |
| Nombre 4   | P – T  |
| Nombre 5   | U – Z  |

---

*Laboratorio grupal · Generation Colombia · 2026*