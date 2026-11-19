---
tipo: proyecto
estado: activo
---

# Veterinaria Nunchys

## Objetivo
App de gestión interna (solo personal) para la veterinaria. Primer módulo: inventario y ventas.

## Estado
- Fase actual: módulo de inventario y ventas; clientes y mascotas en revisión (PR #13 a #15)
- Última actualización: 2026-11-19

## Repositorio
- URL: https://github.com/DiegoAle2390/VeterinariaNunchys
- Ruta local: `D:\Sistemas\AI-Projects\VeterinariaNunchys`
- Rama principal: master

## Stack
Next.js 16, React 19, TypeScript, Tailwind 4, Supabase, Vitest.

## Próximos pasos
Basado en `odd/plans/sales-overhaul.md` y las tareas abiertas en `odd/tasks/`. Hechos y en `master`: medios de pago y pagos divididos, anulación de ventas, roles/permisos, descuentos y promociones (PR #11), caja por turnos y reportes (PR #12). Cuestionario para la clienta: [[cuestionario-cliente]].

- [ ] Cerrar T0e de `roles-permissions`: verificación independiente (seguridad + datos), chequeo en vivo y PR
- [ ] Cerrar T4a de `inventory-overhaul`: registrar el diseño y la rama `feat/inventory-lots`
- [x] Slice B: descuentos manuales y promociones (incluye descuento por lotes próximos a vencer), PR #11 mergeado
- [x] Caja por turnos (apertura, movimientos, cierre a ciegas) y reporte del período, PR #12 mergeado
- [ ] Clientes, mascotas y comprobante imprimible o por WhatsApp: tres PR encadenados (#13, #14, #15), migraciones 0016 y 0017 aplicadas y probadas en vivo con Vendedor y Encargado; falta mergear en orden
- [ ] Completar el cuestionario con la clienta (cuenta corriente, facturación, turnos, entre otros)
- [ ] Turnos de peluquería, baño y clínica (etapa siguiente, depende de clientes y mascotas)
- [x] Decisiones **[decidir]** del plan resueltas con el dueño (precedencia de promociones, umbral de descuento por rol)

## Notas y decisiones
- Las specs y tareas del código viven en `odd/` dentro del repo.
- Decisiones de arquitectura: `04-Decisiones/`
