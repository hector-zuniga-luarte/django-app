# django-app
Proyecto académico en Django realizado en DuocUC el semestre 2022.01

Sitio web de una ONG de mascotas. Con API's y un módulo de administración.

Se puede entrar por:

Sitio web clientes:
http://localhost:8000/

Sitio web administración:
http://localhost:8000/administracion

Recursos de API's:
    path('productos/lista/', ListaProductos.as_view()),
    path('productos/categoria/<int:codCategoria>/', ListaProductosCategoria.as_view()),
    path('productos/', CrearProducto.as_view()),
    path('productos/<int:idProducto>/', Productos.as_view()),
    path('contactos/lista/', ListaContactos.as_view()),
    path('contactos/', CrearContacto.as_view()),
    path('contactos/<int:idContacto>/', Contactos.as_view()),
    path('fundaciones/lista/', ListaFundaciones.as_view()),
    path('fundaciones/', CrearFundacion.as_view()),
    path('fundaciones/<int:idFundacion>/', Fundaciones.as_view()),
    path('categorias/lista/', ListaCategorias.as_view()),
    path('categorias/', CrearCategoria.as_view()),
    path('categorias/<int:codCategoria>/', Categorias.as_view()),
