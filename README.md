# sistema-control-inventario
Sistema para registrar productos, controlar stock y gestionar el inventario de un supermercado.

Historia 1: Registrar productos

Como empleado del supermercado, quiero registrar nuevos productos en el sistema ingresando su nombre, código único, categoría y cantidad inicial, para incorporar la mercadería al sistema informático y mantener actualizada la base de datos de inventario desde el inicio de las operaciones, asegurando que el software valide que no se dupliquen códigos y que el producto quede disponible inmediatamente para su consulta y cobro en la caja.

Historia 2: Consultar stock

Como empleado del supermercado, quiero consultar de forma rápida la cantidad disponible de un producto específico ingresando su nombre o código de barras, para verificar su existencia física antes de confirmar una operación de venta al cliente y evitar transacciones erróneas, logrando que el sistema arroje resultados ágiles en pocos segundos y muestre claramente el stock actual, el código y el sector de depósito asignado o una advertencia en caso de que el ítem no exista.

Historia 3: Actualizar stock

Como responsable del inventario, quiero registrar de manera automática o manual los movimientos de entrada y salida de productos originados por ventas confirmadas, mermas o reposiciones de proveedores, para mantener actualizadas las cantidades exactas en la base de datos y detectar de forma temprana cuándo los niveles de mercadería perforan el stock mínimo establecido, permitiendo que el sistema descuente unidades por cada venta concretada, sume los nuevos ingresos de mercadería y emita alertas visuales cuando sea necesario reponer stock.

#INDICADORES DE CONTROL 
Indicador: Productos bajo stock mínimo	                                          
Forma de cálculo:  Productos bajo el mínimo ÷ productos registrados × 100    
Para qué sirve:   Identificar necesidades de reposición
                     	                                 
Indicador: Diferencias de stock	  
Forma de cálculo: Productos cuya cantidad real no coincide con la registrada ÷ productos verificados × 100	             
Para qué sirve: Detectar errores en el inventario

Indicador: Tiempo de reposición	                             
Forma de cálculo: Fecha de reposición − fecha del aviso	                                                 
Para qué sirve: Medir cuánto se tarda en reponer

Indicador: Operaciones correctas	                           
Forma de cálculo: Operaciones correctas ÷ operaciones probadas × 100	                                    
Para qué sirve: Evaluar el funcionamiento del sistema
