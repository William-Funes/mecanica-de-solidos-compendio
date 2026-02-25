# mecanica-de-solidos-compendio
Formulas
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Compendio: Mecánica de Sólidos I</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/sakura.css/css/sakura.css" type="text/css">
    <style>
        :root { --main-color: #2c3e50; --accent-color: #2980b9; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; }
        .card { border-left: 5px solid var(--accent-color); background: #f4f7f6; padding: 20px; margin: 20px 0; border-radius: 8px; box-shadow: 2px 2px 5px rgba(0,0,0,0.05); }
        h1, h2, h3 { color: var(--main-color); border-bottom: 2px solid #eee; padding-bottom: 5px; }
        .formula { background: #2c3e50; color: #ecf0f1; padding: 12px; border-radius: 6px; font-family: "Courier New", monospace; font-weight: bold; display: block; margin: 15px 0; text-align: center; }
        .variable-list { font-size: 0.9em; color: #555; }
        .badge { background: var(--accent-color); color: white; padding: 3px 10px; border-radius: 15px; font-size: 0.8em; text-transform: uppercase; }
    </style>
</head>
<body>
    <header>
        <h1>Compendio de Fórmulas: Mecánica de Sólidos</h1>
        <p><strong>Estudiante:</strong> [Tu Nombre] | <span class="badge">Unidad 1: Equilibrio y Vectores</span></p>
        <hr>
    </header>

    <section>
        <h2>I. Herramientas de Análisis Vectorial</h2>
        <p>Fundamentos para la descomposición de cargas en cuerpos sólidos.</p>
        
        <div class="card">
            <h3>Producto Escalar (Punto)</h3>
            <span class="formula">A · B = |A| |B| cos(θ) = AxBx + AyBy + AzBz</span>
            <p><strong>Aplicación en Sólidos:</strong> Se utiliza para calcular el ángulo entre fuerzas aplicadas o determinar la componente de una fuerza que actúa a lo largo de un elemento estructural.</p>
            <div class="variable-list">
                <strong>Variables:</strong> A, B (Magnitudes de fuerza), θ (Ángulo entre vectores), Ax, Ay, Az (Componentes rectangulares).
            </div>
        </div>

        <div class="card">
            <h3>Producto Vectorial (Cruz)</h3>
            <span class="formula">M = r × F = det | i j k ; rx ry rz ; Fx Fy Fz |</span>
            <p><strong>Aplicación en Sólidos:</strong> Fundamental para el cálculo de <strong>Momentos de Fuerza</strong> (Torque), los cuales generan flexión o torsión en los elementos sólidos.</p>
            <div class="variable-list">
                <strong>Variables:</strong> r (Vector posición), F (Vector fuerza), i, j, k (Vectores unitarios).
            </div>
        </div>
    </section>

    <section>
        <h2>II. Equilibrio Estático del Sólido</h2>
        <p>Condición necesaria antes de analizar deformaciones internas.</p>
        
        <div class="card">
            <h3>Ecuaciones de Equilibrio (2D y 3D)</h3>
            <span class="formula">ΣFx = 0 | ΣFy = 0 | ΣFz = 0 | ΣM = 0</span>
            <p><strong>Definición:</strong> Establece que para que un sólido sea estático, la suma de todas las fuerzas y momentos externos debe ser nula.</p>
        </div>
    </section>

    <section>
        <h2>III. Caracterización de Cargas Externas</h2>
        <div class="card">
            <ul>
                <li><strong>Peso (W = m·g):</strong> Carga gravitacional distribuida que actúa en el centro de gravedad.</li>
                <li><strong>Tensión (T):</strong> Carga axial que actúa hacia afuera del nodo o elemento.</li>
                <li><strong>Normal (N):</strong> Fuerza de contacto perpendicular a la sección transversal.</li>
                <li><strong>Fricción (f):</strong> Fuerza tangencial opuesta al movimiento relativo entre superficies.</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>IV. Metodología: El Diagrama de Cuerpo Libre (DCL)</h2>
        <div class="card">
            <ol>
                <li><strong>Aislamiento:</strong> Se separa el sólido o el nodo de su entorno.</li>
                <li><strong>Identificación:</strong> Se dibujan todas las fuerzas externas y reacciones de apoyo.</li>
                <li><strong>Orientación:</strong> Se define un sistema de coordenadas (x, y, z) alineado con los soportes.</li>
                <li><strong>Resolución:</strong> Se aplican las ecuaciones de equilibrio para hallar las incógnitas.</li>
            </ol>
        </div>
    </section>

    <footer>
        <p><em>Este compendio refleja la comprensión técnica de las leyes de la estática aplicadas a la mecánica de materiales. No se permite la transcripción mecánica sin análisis previo.</em></p>
    </footer>
</body>
</html>
