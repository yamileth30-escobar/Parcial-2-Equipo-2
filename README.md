# Parcial-2-Equipo-2

--Integrantes

David Alexander Aguilar Barrientos,
Gabriela de los Angeles Chacón Guevara,
María Guadalupe Canjura Díaz,
Mallerli Yamileth Ventura Escobar,
Milagro Stefany Tejada Jiménez,
Noe Steve Mejia Hernandez,
Jose Angel Gutierrez Cortez.

--Rutas Implementadas

# producto
path('', ProductoListView.as_view(), name="producto-list"),
http://127.0.0.1:8000/productos/
# nuevo producto
path('nuevo', ProductoCreateView.as_view(), name="producto-create"),
http://127.0.0.1:8000/productos/nuevo

--Descripción 

El proyecto permite gestionar productos mediante vistas basadas en clases (CBV) con Django y plantillas Bootstrap.
