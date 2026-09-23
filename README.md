# Refugio — Lista para El Niño

SPA ligera para organizar misiones familiares de preparación ante lluvias e inundaciones en Guayaquil. React, Vite y Tailwind CSS; datos locales de prueba en localStorage.

## Desarrollo

```bash
npm install
npm run dev
```

El catálogo inicial se basa en el listado compartido: reservas de agua y alimentos, energía, comunicaciones, botiquín, control de mosquitos, kit anti inundación, mochila, documentos, herramientas, mascotas y plan familiar. El plan ofrece un máximo de cinco misiones diarias; cada misión queda reservada al jugador que la toma. Al acabar las diarias puede adelantar una misión recomendada.

El HP se presenta como energía lúdica, no como medida de salud o seguridad. Al pasar al día siguiente vuelve a abrirse el plan. Para una fase en la nube, sustituir la persistencia local por un repositorio/API y agregar familyId a los registros.
