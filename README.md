# Portal de Formularios - RIO YELCHO SPA

Portal web estático para centralizar el acceso a formularios corporativos de:

- Prevención de Riesgos
- Recursos Humanos
- Faenas

Los formularios son gestionados mediante Microsoft Forms y están organizados por categorías para facilitar su acceso desde dispositivos móviles y computadores.

---

## Estructura del Proyecto

```text
portal-forms/
│
├── index.html
│
├── css/
│   └── styles.css
│
├── js/
│   └── forms.js
│
├── img/
│   └── Logo_Yelcho.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Requisitos

No requiere instalación de dependencias.

Solo se necesita:

- Navegador web moderno
- Acceso a Internet
- Formularios Microsoft Forms publicados

---

## Configuración de Formularios

Los formularios se definen en:

```text
js/forms.js
```

Ejemplo:

```javascript
{
  categoria: "RRHH",
  nombre: "Solicitud de Vacaciones",
  descripcion: "Gestión de vacaciones",
  url: "https://forms.office.com/r/XXXXXXXX"
}
```

---

## Agregar un Nuevo Formulario

1. Abrir:

```text
js/forms.js
```

2. Agregar un nuevo objeto al arreglo `forms`.

Ejemplo:

```javascript
{
  categoria: "Faenas",
  nombre: "Check List Camión",
  descripcion: "Inspección diaria de equipo",
  url: "https://forms.office.com/r/XXXXXXXX"
}
```

3. Guardar cambios.

4. Publicar nuevamente el sitio.

---

## Categorías Disponibles

Actualmente el portal contempla:

- Prevención de Riesgos
- RRHH
- Faenas

Las categorías se generan automáticamente según el contenido de `forms.js`.

---

## Publicación

### GitHub Pages

El sitio puede ser publicado directamente desde GitHub Pages.

### Dominio Corporativo

Puede asociarse un dominio personalizado:

```text
https://forms.rioyelcho.cl
```

o

```text
https://formularios.rioyelcho.cl
```

---

## Compatibilidad

- Google Chrome
- Microsoft Edge
- Firefox
- Safari
- Android
- iOS

---

## Autor

RIO YELCHO SPA

Portal interno de acceso a formularios corporativos.