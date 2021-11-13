
# ISO/IEC 9126

&nbsp;

## CONCEPTOS

### **ISO**  
<div style="text-align: justify"> La Organización Internacional de Normalización o ISO, nacida tras la Segunda Guerra Mundial (23 de febrero de 1947), es el organismo encargado de promover el desarrollo de normas internacionales de fabricación (tanto de productos como de servicios), comercio y comunicación para todas las ramas industriales. Su función principal es la de buscar la estandarización de normas de productos y seguridad para las empresas u organizaciones (públicas o privadas) a nivel internacional.  </div>

&nbsp;

### **IEC** 

<div style= "text-align: justify">
Fundada en 1906, la IEC (Comisión Electrotécnica Internacional) es la organización líder en el mundo para la elaboración y publicación de las Normas internacionales para todas las tecnologías eléctricas, electrónicas y relacionadas. Éstos se conocen colectivamente como "electrotécnica".
IEC proporciona una plataforma para las empresas, las industrias y los gobiernos para hacer frente, la discusión y el desarrollo de las normas internacionales que requieren.
</div>

&nbsp; 

### **ISO/IEC 9126**
<div style= "text-align: justify">
La ISO 9126, publicada en 1992, es un estándar internacional para evaluar la calidad del software en base a un conjunto de características y sub-características de la calidad. Cada sub-característica consta de un conjunto de atributos que son medidos por una serie de métricas. 
A la fecha, el modelo ISO 9216 no ha sido aplicado extensamente al ambiente de aprendizaje virtual, sin embargo, los autores creen que el modelo tiene el potencial para proporcionar una herramienta útil de evaluación: esta creencia se deriva de los muchos años de experiencia en la industria que uno de los investigadores ha tenido en la garantía de calidad de software.

El estándar 9126 permite a cada organización establecer su
propio modelo de calidad en función de las características del
software que se quiera evaluar. Para evaluar el estándar 9126 se utiliza el estándar ISO-IEC 14598.
La ISO-IEC 14598 proporciona un marco de trabajo para
evaluar la calidad de todos los tipos de productos de software
e indica los requisitos para los métodos de medición y para
el proceso de evaluación.
</div>

&nbsp;

## VENTAJAS & DESVENTAJAS


&nbsp;


## CARACTERÍSTICAS


&nbsp;

## OBJETIVOS

&nbsp;

## Métricas

<div style= "text-align: justify">
Las métricas de calidad de producto se aplican a los diversos atributos del producto y que permiten determinar posteriormente los niveles de calidad del producto.  Las métricas que se pueden aplicar de acuerdo a los atributos están definidos en las normas ISO/IEC 9126-2 para el caso de la calidad externa, la ISO/IEC 9126-3 para el caso de la calidad interna y la ISO/IEC 9126-4 para el caso de la calidad en uso. En todos los casos, las normas señalan que las métricas presentadas no pretenden ser exhaustivas (ser completas), ni limita la posibilidad de usar otras métricas de acuerdo a las necesidades del usuario.
</div>

&nbsp;

**9126-2**
Las **métricas externas** pueden ser aplicadas durante la prueba y operación del producto software ejecutable (se evalúa el comportamiento) y proporciona a todos los involucrados el beneficio de conocer la calidad del producto software durante las pruebas u operación y saber si cumple con la calidad esperada.

**9126-3**
Las **métricas internas** pueden ser aplicadas durante el diseño y la codificación del producto software no ejecutable (por ejemplo código fuente) y proporciona a todos los involucrados el beneficio de conocer la calidad del producto durante su construcción y tomar decisiones sobre esa base para conseguir el producto con la calidad esperada.

**9126-4**
Las **métricas de calidad en uso** miden el nivel en que un producto software cumple con las necesidades específicas de los usuarios en un contexto de uso determinado y son el resultado del uso del software, en lugar de las propiedades de éste.  El contexto de uso está determinado por los escenarios en los que el usuario realiza sus tareas.

<div style= "text-align: justify">
La calidad en uso depende de la calidad externa, de la misma forma esta calidad depende de la interna, asimismo la calidad interna influye en la externa e indiscutiblemente en la calidad de uso.  
</div>
![Relación entre calidades](/archivos/expo/calidades.jpeg) 



**Tipos de Métricas**

- Funcionabilidad
- Fiabilidad
- Usabilidad
- Eficiencia
- Mantenibilidad


Ejemplo de Métrica externa de **Exactitud de cálculo** (*Eficiencia*): 

| Nombre de la métrica | Exactitud de cálculo |
| --- | --- |
|Próposito de la Métrica | ¿Cuán frecuente los usuarios finales encuentran resultados inexactos? |
| Método de aplicación: | Registrar el número de cálculos inexactos basado en especificaciones.  |
| Medición, fórmula y cálculo de elementos de datos: | X = A/T |
| Interpretación del valor medido: | 0 <= X , (lo más cercano a 0.0 es lo mejor)| 
| Tipo de escala Métrica: | Ratio |
| Entrada para la medición: |Especificación de requerimientos / Reporte de pruebas|
| Tipo de medida: | X = Cantidad/Tiempo, A = Cantidad,T = Tiempo (segundos)|
| Referencia PCVS ISO/IEC 12207: | 6.5 Validación / 6.3 Aseguramiento de calidad |
| Audiencia objetivo: | Desarrollador y Usuario | 

*(A= Número de cálculos inexactos, T  = Tiempo de operación)*