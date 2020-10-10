# Guia-13-EJ1

Desarrollar una página web en HTML con JavaScript para el ingreso de los datos
relativos a los vehículos que utiliza una empresa.

Los vehículos se identifican por un número de unidad comprendido entre 1 y 100.
De cada uno de ellos, se conoce el año de fabricación (ninguno menor al 2018), marca,
modelo, motor (con 8 caracteres como mínimo), patente, si se trata de un vehículo
propio o alquilado, los accesorios que contiene (Airbag, Aire Acondicionado, MP3,
Vidrios Polarizados) y los depósitos con los cuales opera habitualmente. Para los
vehículos propios, se ingresa el precio de compra y porcentaje de depreciación anual;
mientras que en los alquilados el precio del alquiler.

También se registra el nombre y apellido del responsable del uso y su dirección de
correo electrónico. La página debe revisar que se trate de un dato válido (contenga un
símbolo “@” y al menos un “.” en el dominio), implementando expresiones regulares. E
informar la antigüedad del vehículo y, si corresponde, el precio de compra actualizado
según la depreciación, ambos en la misma página.

Tanto la marca como el modelo del mismo deben ser seleccionada mediante el uso de
una lista desplegable.

Se debe incluir un botón para confirmar los datos, otro para limpiarlos con confirmación
del usuario, y un tercero para enviar un correo electrónico indicando que el ingreso fue
correcto. En el primer caso, se mostrarán los datos ingresados en la misma página (en
otro sector) o en otra página y procesados por el programa fuente ingresoVehiculos.jsp
mediante el uso de formulario.

Todos los componentes están distribuidos haciendo uso de tablas HTML.