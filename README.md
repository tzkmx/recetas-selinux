# Recetas de SELinux

Esto es de momento, una colección de políticas propias
desarrolladas con el objetivo de mantener los mínimos
privilegios necesarios para que una aplicación funcione,
sin exponernos a riesgos no deseados.

En específico, se desarrollan contra un sistema CentOS7
la webapp principal es WordPress, fail2ban protege
algunos puertos.

Estaré subiendo notas de implementación, como desarrollar
políticas a medida, y básicamente todo lo que implique
entender SELinux y proteger el sistema para el día a día,
sin necesidad de activar todos los booleanos ni usar
para todo `audit2allow`, que IMNSHO, equivale a no usar
SELinux en absoluto, o peor aún.

