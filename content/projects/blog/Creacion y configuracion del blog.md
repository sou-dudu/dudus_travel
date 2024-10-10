Para la creación del blog se han seguido los pasos indicados en el github del creador de la herramienta Quartz.

# Configuracion

En la configuracion se han realizado una serie de cambios
``` typescript
export const defaultContentPageLayout: PageLayout = {

beforeBody: [

Component.Breadcrumbs(),

Component.ArticleTitle(),

Component.ContentMeta(),

],

left: [],

right: [

Component.Graph(),

Component.TableOfContents(),

Component.Backlinks(),

],

}
```