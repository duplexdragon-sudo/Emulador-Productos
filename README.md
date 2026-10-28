# Simulador de productos

Una sociedad sintética de consumidores colombianos decide si compra tu producto.

Pones precio, costo, flete, contraentrega, presupuesto de anuncios y calificas el atractivo del producto (1–10). Miles de agentes con edad, estrato, ingreso, intereses y red social ven tus anuncios día a día, compran, recomiendan o dejan malas reseñas. La simulación se repite muchas veces (Monte Carlo) y te da:

- Probabilidad de ganar plata y un puntaje de 0 a 100 (Ganador / Prometedor / Riesgoso / No viable)
- CPA esperado vs. CPA de equilibrio, ROAS, pedidos, ventas por voz a voz
- Curva de utilidad (pesimista / típica / optimista) y mapa animado de la sociedad
- Quién compra (edad y estrato), "voces" de los agentes y diagnóstico
- Precio óptimo, cuánto invertir en publicidad (prueba, presupuesto recomendado, capital necesario y reglas para escalar o apagar) y comparativa de productos guardados
- Buscador de productos ganadores con IA (al abrirlo en claude.ai), con búsqueda web real si conectas Parallel Search o Exa en claude.ai; prueba varios precios y combo y solo muestra los ganadores
- Ofertas: precio por 2 y 3 unidades y producto adicional (upsell), con ticket promedio y margen por pedido
- Aprende de tus ventas reales: anotas los resultados de tus pruebas y corrige sus predicciones para los siguientes productos

Es una página única (`index.html`), sin servidor ni librerías; funciona sin internet y se puede instalar en el celular.

**Es una aproximación para filtrar y comparar ideas, no una garantía.** Valida los mejores productos con una prueba real pequeña y vuelve a simular con tu CTR y conversión reales (sección "Avanzado").

## Publicarlo

Settings → Pages → Branch: `main`, carpeta `/ (root)` → Save. Queda en `https://<tu-usuario>.github.io/Emulador-Productos/`.
