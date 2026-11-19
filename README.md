Validación de Documentos XML con DTD (Hospital)
Proyecto de Lenguajes de Marcas que consiste en la creación de un documento XML y su correspondiente Document Type Definition (DTD) para validar la estructura de los datos.

Tecnologías y Herramientas
Lenguaje: XML (eXtensible Markup Language)
Validación: DTD (Document Type Definition)
Editor: Apache NetBeans

Funcionalidades y Conceptos Aplicados
Estructura jerárquica (XML): Creación de un documento XML que representa los pedidos de un hospital, con elementos anidados como pedidos, pedido, cliente y productos.
Atributos: Uso de atributos para categorizar y añadir metadatos (ej. cod, familia, pagado).
Definición de reglas (DTD): Creación de un archivo DTD para definir los elementos obligatorios, opcionales y el tipo de contenido (PCDATA), asegurando que el XML sea válido.

Cómo validar el proyecto
Abre el archivo hospital.xml en NetBeans o en cualquier editor de texto.
Asegúrate de que el archivo ALUMNO.dtd está en la misma carpeta.
Haz clic derecho sobre el XML y selecciona "Validate XML" (o similar, depende del editor) para comprobar que cumple las reglas del DTD.
