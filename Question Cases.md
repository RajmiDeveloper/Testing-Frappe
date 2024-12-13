-----------------------------------------------------------------------------
	Caso 1:
Asociado a doctype, doctype practicas, contexto admision
checkbox
-- funciona

-----------------------------------------------------------------------------
	Caso 2:
Asociado a doctype, doctype practicas, contexto admision
texto
-funciona

-----------------------------------------------------------------------------
	Caso 3:
Asociado a doctype, doctype practicas, contexto admision
texto
dependiente de la respuesta de caso 1
-- funciona

-----------------------------------------------------------------------------
	Caso 4:
Asociado a doctype, doctype practicas, contexto admision
Checkbox
dependiente de que se escriba un texto particular en Caso 3
-- funciona

-----------------------------------------------------------------------------
	Caso 5:
Asociado a documento, doctype practicas, contexto admision
texto
La practica asociada tenia el valor de la “related question”
-- no funciona

-----------------------------------------------------------------------------
	Caso 6:
Asociado a doctype, doctype ---, contexto admision
Cualquier tipo
--no funciona

-----------------------------------------------------------------------------
	Caso 7:
Asociado a un doctype, doctype ---, contexto admision
texto
dependiente del Caso 1
-- no funciona

-----------------------------------------------------------------------------
	Caso 8:
No se puede asociar una pregunta a un cliente y/o sus datos

-----------------------------------------------------------------------------

-----------------------------------------------------------------------------
	Caso 9:
Asociado a un doctype, Doctype practicas, contexto admision
texto
Tanto el label como el “texto ayuda” tienen un maximo de 140 y no se rompe nada
-- funciona
