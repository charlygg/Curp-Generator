# Curp-Generator
Generador Curp basado en http://consultas.curp.gob.mx/CurpSP/

Carlos García - Integrar validador para generar los dígitos verificadores

Se valida la CURP de acuerdo al [Diario Oficial de la Federación](https://www.dof.gob.mx/nota_detalle.php?codigo=5526717&fecha=18/06/2018)

La CURP se forma de acuerdo a las siguientes características:

- Inicial de primer apellido
- Primera vocal interna del apellido
- Iniciales del segundo apellido y el nombre
- Dos dígitos del año
- Dos dígitos del mes
- Dos dígitos del dia
- Sexo (H/M)
- La entidad federativa en la que nació
- Las primeras consonantes internas de apellidos y nombre 
- Homoclave
- Dígito Verificador

![S](https://i.stack.imgur.com/1P3J9.gif)

En el [siguiente enlace](https://361253.playcode.io/) puedes validar la CURP generada incluyendo el dígito verificador