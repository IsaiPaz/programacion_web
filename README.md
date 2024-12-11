# Titulos

## subtitulos

texto `codigo`

##Codigo css

```css
.calculadora {
    background-color: #FFFBDA;
    color: white;
    width: 420px;
    height: 550px;;
    max-width: 100%;
    padding: 1rem;
    border-radius: 1rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 1rem;
}
```
## Codigo python
``` python
    def plotly_plot(self):
        import plotly.graph_objects as go
        import numpy as np

        ys = self.for_plot['shap'].round(2)
        ms = list(np.repeat('relative',len(ys)))
        xs = list(self.for_plot['label'].values)
        texts = self.for_plot['shap'].round(2)

        fig = go.Figure(go.Waterfall(
            name = "20", orientation = "v",
            measure = ms,
            x = xs,
            textposition = "outside",
            text = texts,
            y = ys,
            connector = {"line":{"color":"rgb(63, 63, 63)"} },
           ) )
```

## Imagen
<img src="https://akamai.sscdn.co/tb/letras-blog/wp-content/uploads/2023/07/9681c39-natanael-cano-1024x683.jpg">

## Tabla

| Comando de git | Descripcion                                      | Ejemplo  |
|----------------|--------------------------------------------------|----------|
| git init       | Creacion de un repositorio                       | git init |
| git pull       | Obtencion de la ultima version de un repositorio | git pull |
