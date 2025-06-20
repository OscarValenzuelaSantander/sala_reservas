1. ¿En qué se diferencia Agile Testing del enfoque tradicional?
Agile Testing se integra desde el inicio del desarrollo y es continuo, mientras que el enfoque tradicional prueba al final del ciclo.

2. ¿Qué ventajas viste al usar TDD? ¿Qué te costó más?
Ventajas: código más limpio, menos errores, diseño más claro.
Lo más difícil: pensar primero en la prueba antes del código funcional.

3. ¿Qué tipo de prueba crees que más valor aportó hoy?
Las pruebas funcionales (como test_reserva_exitosa) aportaron más valor porque verifican el comportamiento real de la API y garantizan que las reservas se manejen correctamente desde el cliente.

4. ¿Cómo mantendrías esta suite de pruebas con el tiempo?
Agregaría más casos conforme se agregan funcionalidades, separaría pruebas unitarias y de integración, y automatizaría su ejecución en GitHub Actions para detectar errores en cada cambio.