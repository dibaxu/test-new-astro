ASTRO
VIEW-TRANSITIONS
agregar propiedad transition:name="{id}" al componente y en Layout importar ClientRouter from astro:transitions y agregarlo en el head.

ISLAND SERVER COMPONENT

- SERVER:DEFER -> para componentes especificos que son dinámicos y son renderizados en el SERVIDOR y no en el cliente. Se puede agregar un fallback con la propiedad slot="fallback" para que haya un contenido pre-cargado.

ENV SCHEMA CONFIG

CONTENT CONFIG TS

ASTRO CONFIG
output: "server" -> indica que el output necesita un servidor para componentes dinámicos que son renderizados en cada ocasión. Implica tambien indicar con "export const prerender= true"

DEPLOY
probar Deno deploy, que solo levanta el servidor cuando un componente lo necesita.
