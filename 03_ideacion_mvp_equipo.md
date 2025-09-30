Sesión 4
Resumen breve del problema y criterios de éxito (sesión 2).
La falta de hábitos financieros saludables entre estudiantes universitarios contribuye a una mala gestión del dinero, provocando inestabilidad económica, estrés financiero y vulnerabilidad ante situaciones imprevistas. Y los criterios de éxito son que el prototipo debe registrar datos básicos del usuario sin errores (≥90% de pruebas exitosas). El prototipo debe mostrar al menos una visualización gráfica con datos reales de su presupuesto. El prototipo debe poder guardar y recuperar información (ingresos, gastos, metas de ahorro). El prototipo tiene que poder dejar al usuario registrarse y visualizar correctamente sus ingresos y egresos en el sistema.
Listado de ideas generadas en la lluvia de ideas.
App de Presupuesto Simple con Registro Rápido, App con gráfico de barras por semana, Sistema de Alertas por gastos, Metas de Ahorro y Tablero con logros por semana/mes. 
Idea elegida y justificación de la selección.
App con gráfico de barras por semana: Con gastos e ingresos, muestra Ingresos por semana = suma de todas las transacciones de tipo ingreso, gastos por semana = suma de todas las transacciones de tipo gasto y posiblemente un balance general = Ingreso - gasto. Esto ayudaría al usuario para administrar mejor su dinero y llevar un registro que les permita ver si van arriba o abajo de lo que es conveniente, y el balance semanal agiliza decisiones (ahorrar, recortar en una categoría) sin analizar tablas ni reportes complejos.


Clasificación MoSCoW de funcionalidades.
Aplicación Financiera Universitaria – MVP (MoSCoW)
MUST
SHOULD
COULD
WON’T
Registro usuario
Metas de ahorro
Tablero de logros
Exportar a PDF/Excel
Registro ingresos y egresos
Sistema de alertas por sobre presupuesto
Historial de semanas/meses


Visualización gráfica (gráfico de barras semanal)

Guardar y recuperar información

Wireflow o diagrama simple del flujo de la app.

Arquitectura mínima (módulos y descripción de su función).
app/
Contendrá todas las pantallas y navegación entre ellas.
Maneja los eventos de botones y formularios.
	core/
Funciones para registrar transacciones (ingreso/gasto).
Cálculo de balance semanal.
Cálculo de progreso de metas de ahorro.
	api/
Obtener tipo de cambio de divisas, noticias financieras, inflaciones.
	viz/
Función que recibe datos y devuelve un gráfico de barras
	data/
Guardar y recuperar información de usuarios, transacciones y metas.


Link para ver gráficas y diagramas de flujo 
https://docs.google.com/document/d/1jiYj1TT4gN8WXfW_6iZ4jvKGtNJz-kIHCpMY1hHXk5A/edit?usp=sharing
