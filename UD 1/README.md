# Documentación Unidad 1 Lenguaje de Marcas

## Introducción a Lenguaje de marcas

### Definición

Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas.

## Clasificación de Lenguajes de marcas

|Tipo|Uso|Ejemplos|
|----|----|-------|
|Presentación|Far formato a documentos de texto|HTML, CSS|
|Intercambio de  información|Almacenar información de  forma ordenada|XML, RSS|
|Documentación|Documentar poryectos|Markdonw, WikiText|

## Instalación y configuración del entorno

1.  Instalamos [VS Code](https://code.visualstudio.com/)
2.  Instalamos plugins
    - [Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
    - [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
    - [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
3. Instalamos git
```bash
sudo apt install git
```
4. Configurar repositorio git (en la carpeta principal de proyecto)
```bash
git init
git add .
git commit -m ""
```

5. Conectar con github
```ash
git remote add original url-repositorio
git branch -M main
git push -u origin main
```

## Descripción de plugins

|Nombre|Imagen|Uso|
|------|------|---|
|Markdown all in one|![Markdown all in one](img/MarkDown.png)|Conversión del texto a como se observa en navegador.|
|Live Preview|![Live Preview](img/LivePreview.png)|Visualizar css según escribes codigo.|
|XML|![HTML CSS Support](img/XML.png)|Facilitar la escritura con autocompletados en xml.|
|HTML CSS Suport|![HTML CSS Support](img/HTMLCSSSupport.png)|Facilitar la escritura con autocompletados en CSS y HTML.|