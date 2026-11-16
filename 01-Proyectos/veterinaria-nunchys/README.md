---
tipo: proyecto
estado: activo
---

# Veterinaria Nunchys

## Objetivo
App de gestión interna (solo personal) para la veterinaria. Primer módulo: inventario y ventas.

## Estado
- Fase actual: módulo de inventario y ventas
- Última actualización: 2026-11-16

## Repositorio
- URL: https://github.com/DiegoAle2390/VeterinariaNunchys
- Ruta local: `D:\Sistemas\AI-Projects\VeterinariaNunchys`
- Rama principal: main

## Stack
Next.js 16, React 19, TypeScript, Tailwind 4, Supabase, Vitest.

## Próximos pasos
Basado en `odd/plans/sales-overhaul.md` y las tareas abiertas en `odd/tasks/`. Hechos: slice A (medios de pago y pagos divididos), slice C (cancelación de ventas) y roles/permisos.

- [ ] Cerrar T0e de `roles-permissions`: verificación independiente (seguridad + datos), chequeo en vivo y PR
- [ ] Cerrar T4a de `inventory-overhaul`: registrar el diseño y la rama `feat/inventory-lots`
- [ ] Slice B: descuentos manuales y promociones (incluye descuento por lotes próximos a vencer)
- [ ] Slice D: caja por turnos (apertura, movimientos, arqueo) y reporte diario
- [ ] Slice E: clientes y mascotas, ticket imprimible o por WhatsApp
- [ ] Resolver las decisiones marcadas **[decidir]** del plan antes de implementar B (precedencia de promociones, umbral de descuento por rol)

## Notas y decisiones
- Las specs y tareas del código viven en `odd/` dentro del repo.
- Decisiones de arquitectura: [[04-Decisiones/]]
