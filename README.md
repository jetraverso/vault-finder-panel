# Panel de licencias de Vault Finder

Pantalla de administración de [Vault Finder](https://github.com/jetraverso).
Una sola página, sin dependencias ni compilación.

Solo contiene la interfaz. Los datos viven en Supabase, protegidos por
Row Level Security: hace falta entrar con un usuario que esté en la lista de
administradores para ver o modificar cualquier cosa. La clave que aparece en el
código es la clave pública del proyecto, que por diseño no habilita nada por sí sola.
