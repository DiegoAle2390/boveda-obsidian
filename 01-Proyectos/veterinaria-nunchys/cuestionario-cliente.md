---
tipo: nota
estado: activo
creada: 2026-11-19
tags: [veterinaria-nunchys, cuestionario]
---

# Cuestionario para la veterinaria (a completar con la clienta)

Documento vivo: se agregan preguntas a medida que aparecen dudas durante el desarrollo. Copia de `odd/cuestionario-cliente.md` del repositorio; si cambia uno, actualizar el otro. Índice del proyecto: [[README]].
Cada pregunta dice de qué parte del sistema sale y qué decisión destraba.
Estado: ⬜ sin preguntar · ✅ respondida (anotar la respuesta debajo).

## Ventas y caja
- ⬜ **Cuenta corriente / abonos y saldos.** ¿Hay clientes que se llevan productos y pagan después? ¿Con qué frecuencia y por cuánto? ¿Quién autoriza y hay un tope por cliente?
  *Destraba:* si se arma una cuenta corriente (toca caja y reportes) o se resuelve por fuera del sistema.
- ⬜ **Medios de pago.** ¿Qué tarjetas y cuotas se aceptan hoy y con qué recargo real? ¿Se acepta Mercado Pago, QR u otra billetera?
  *Destraba:* la lista de medios de pago y sus recargos, que hoy es un ejemplo.
- ⬜ **Cajas.** ¿Hay una sola caja o más de un puesto de cobro (por ejemplo, mostrador y peluquería)?
  *Destraba:* si se crea una segunda caja.
- ⬜ **Cierre de caja.** ¿Quién cuenta el efectivo y quién controla? ¿Se retira dinero del cajón durante el día (a banco, a proveedores)?
  *Destraba:* permisos de cierre y qué motivos de retiro y gasto ofrece el sistema.

## Descuentos y promociones
- ⬜ **Límites de descuento por rol.** Hoy: Encargado 20 %, Vendedor 10 %, Veterinario 10 %. ¿Coincide con la práctica?
- ⬜ **Promociones habituales.** ¿Cuáles usan hoy (por temporada, por rubro, por vencimiento cercano)?

## Clientes y mascotas
- ⬜ **Datos del cliente.** Además de nombre, teléfono, email, DNI y dirección, ¿qué más hace falta (por ejemplo, otro teléfono de contacto)?
- ⬜ **Tratamientos o cuidados especiales por mascota** (alergias, alimento indicado, temperamento, cuidados para la peluquería). ¿Se anotan hoy? ¿Dónde?
  *Destraba:* un campo de notas por mascota.
- ⬜ **Mascotas con más de un dueño** (familia, hogar de tránsito). ¿Se da el caso?
- ⬜ **Especies y razas que atienden.** Para dejar cargado el catálogo inicial.

## Comprobante de venta
- ⬜ **Comprobante.** ¿Entregan factura electrónica (ARCA) hoy? ¿Con qué sistema? El ticket del sistema es un comprobante no fiscal; si necesitan factura hay que integrarla aparte.
  *Destraba:* si hay que facturar desde este sistema o sigue como está.
- ⬜ **Cómo se entrega.** ¿Impreso, por WhatsApp, por mail?

## Turnos (próxima etapa)
- ⬜ **Turnos de peluquería/baño y de clínica.** ¿Cómo se agendan hoy y qué se hace cuando el cliente no aparece o se demora?
- ⬜ **Duración y precio por servicio**, y quién atiende cada uno.
- ⬜ **Recordatorios.** ¿Se avisa al cliente por WhatsApp? ¿Con cuánta anticipación?

## Historial clínico
- ✅ Queda fuera de este sistema: el veterinario ya usa su propio sistema para todo lo clínico.
  *A confirmar con la clienta:* que el sistema no necesita mostrar vacunas ni tratamientos.
