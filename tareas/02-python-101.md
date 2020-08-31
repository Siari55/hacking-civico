### Densidad poblacional y gasto público

De acuerdo a la información proporcionada por el INEGI en el año 2015

Número de habitantes:
* México: 119,530,753
* Guanajuato: 5,853,677
* León: 1,578,626

Superficie total:
* México: 1,973,000 km²
* Guanajuato: 30,607 km²
* León: 1,220 km²

Código para obtener la densidad poblacional
```python
def densidad_poblacional(poblacion, area_ciudad, caso):
  den = "La densidad poblacional de " + caso + " es igual a " + str(poblacion / area_ciudad) + " habitantes por km²"
  return den
  
print(densidad_poblacional(119530753, 1973000, "México"))
print(densidad_poblacional(5853677, 30607, "Guanajuato"))
print(densidad_poblacional(1578626, 1220, "León"))
```

Densidad poblacional:
* México: 60.58325038013178 habitantes por km²
* Guanajuato: 191.25288332734343 habitantes por km²
* León: 1293.955737704918 habitantes por km²

¿Qué pasa comparar varios estados o ciudades?
Se puede ver como las cantidades son proporcionales, a menos superficie mayor cantidad de habitantes por km²

---

El presupuesto por año en Guanajuato en el sector de "Ciencia, Tecnología e Innovación" fue:

* 2018: 56,477,300,000 pesos
* 2019: 49,733,200,000 pesos

Código para obtener el gasto per cápita
```python
def percapita(presupuesto, poblacion):
  div = presupuesto/poblacion
  return div
  
print(percapita(56477300000, 5853677))
print(percapita(49733200000, 5853677))
```

El gasto per cápita por año fue de:
* 2018: 9648.174984714735 pesos
* 2019: 8496.06153533924 pesos

¿En qué porcentaje aumentó o disminuyó?
Disminuyo en un 11.95%

¿A qué crees que se deba?
Otros sectores tomaron mayor importancia o el presupuesto en general es menor

---

¿Para qué crees que nos pueda ser útil esta información?

Para la toma de decisiones al momento de generar soluciones o interés hacia este sector. Determinar planes de acción/desarrollos que entren en estos presupuestos. Generar gráficos con estimaciones.

¿Qué decisiones podría tomar el gobierno basado en ésta?

Determinar si los gastos se están dirigiendo a los sectores adecuados o no.
