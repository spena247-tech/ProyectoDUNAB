DUNAB - Prototipo Java Swing

INICIO
- En NetBeans, abre el proyecto y ejecuta (F6).
- La clase de entrada configurada es Main.MainMenu.

FUNCIONALIDADES
1. Consultar el saldo calculado de DUNAB.
2. Registrar movimientos de ingreso.
3. Registrar gastos con validación de saldo suficiente.
4. Consultar historial con saldo acumulado.
5. Buscar movimientos por descripción y volver a ver todo.
6. Registrar encuentros.
7. Eliminar un encuentro seleccionado.
8. Crear metas con objetivo y fecha límite.
9. Registrar avance de una meta y ver porcentaje.
10. Consultar estadísticas de ingresos, gastos, metas y encuentros.
11. Actualizar perfil académico.
12. Guardar preferencia de tema claro/oscuro.

ESTRUCTURA Y PERSISTENCIA
- Model: Perfil, Movimiento, Meta y DatosDunab.
- ArrayList almacena movimientos, metas y encuentros.
- Los datos se serializan en: %USERPROFILE%\.dunab\datos.ser
- La aplicación guarda automáticamente cada cambio.

NOTA
Los datos son locales a este usuario de Windows y equipo. Para una demo inicial, registra primero un ingreso para probar los gastos.
El formulario MenuPrincipal.form corresponde al menú visual previo; la nueva interfaz funcional se construye directamente desde MenuPrincipal.java.
