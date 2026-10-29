# Cuadre — prototipo de pagos para terapeutas

Prototipo clickeable (HTML + CSS + JS en un solo archivo, sin dependencias ni compilación) para mostrar a las terapeutas cómo funcionaría la app:

- Inicio de sesión con Google (simulado) y conexión de calendario
- Agenda semanal con marcado rápido de pago: Efectivo, Tarjeta, Transferencia, SINPE Móvil o Paquete
- Por cobrar, pacientes, paquetes (incluye paquetes compartidos entre terapeutas)
- Ingresos por semana, mes y año en colones o dólares
- Vista de superadmin con todas las terapeutas y cuota fija o comisión

Todos los datos son ficticios y se guardan solo en el navegador de quien lo abre (botón **Reiniciar datos** para volver al inicio).

## Ver localmente

```
python3 -m http.server 8000
```

y abrir http://localhost:8000

## Publicación

GitHub Pages: *Deploy from a branch* → `main` / raíz.
