# Landing de prueba

Proyecto deliberadamente simple para aprender el flujo:

IA -> GitHub -> Vercel -> dominio

## Archivos

- `index.html`: toda la landing, estilos y lógica en un único archivo.

## Publicación en Vercel

No necesita instalar nada ni ejecutar compilaciones. Es una web estática.

## Captura real de emails

La interfaz está terminada, pero para almacenar emails hay que conectar un destino.

En `index.html`, busca:

    const FORM_ENDPOINT = "";

y sustituye la cadena vacía por el endpoint del servicio que vaya a recibir los leads.
