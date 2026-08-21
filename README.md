# sql-select-fundamentals

¿Por qué es mala práctica usar SELECT * en producción?

Es dificil encontrar algo especifico si buscas datos concretos de columnas concretas. No seria eficiente estar buscando entre tantos datos, ademas, si la tabla
tiene mucha data, tardarias mucho en cargar toda esa informacion cuando podrias ahorrar tiempo de carga buscando solo lo que necesitamos.

¿Por qué son importantes los alias para un stakeholder no técnico? Explicá con un ejemplo concreto cómo un alias transforma total_amount en algo que cualquier persona del área de finanzas puede interpretar directamente.

Son importantes los alias ya que son de facil entendimiento y acceso para todas las areas que necesiten visualizar la informacion en, por ejemplo,
futuros dashboards que podamos armar con los datos.
