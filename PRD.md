# PRD · Web Casa Rural El Rincón de Gredos

Documento de Requisitos del Producto · v1.0 · 2026-07-14
Identidad visual: ver `Brand_Book.md`

## 1. Objetivo

Crear la web pública de la Casa Rural El Rincón de Gredos: dar visibilidad y credibilidad al alojamiento, transmitir la esencia del entorno (Sierra de Gredos, piedra, calma) e invitar a contactar.

En una frase: que quien llegue sienta que ya conoce el lugar y quiera escribir directamente.

## 2. Alcance (S3 — esta sesión)

- Web estática de una sola página (one-page con navegación por anclas), en español.
- Camino A: `index.html` autocontenido, publicable arrastrando a Vercel.
- Responsive · móvil primero.
- Sin backend, sin pagos, sin sistema de reservas real (eso llega en S4 con Stripe).

## 3. Negocio

| Campo | Valor |
|---|---|
| Nombre | El Rincón de Gredos |
| Tipo | Casa rural |
| Ubicación | Navaluenga, Ávila (Sierra de Gredos) |
| Habitaciones | 6 |
| Propietaria | Laura Sánchez |
| Público objetivo | Amantes de la naturaleza / senderismo |
| Tono | Cercano, cálido, experimentado pero familiar |

## 4. Secciones

1. **Portada (hero)** — foto grande de la casa (`hotel.png`), frase de bienvenida, botón "Contactar" / "Ver habitaciones".
2. **Sobre Laura** — retrato breve y cálido de la propietaria: 18 años en hostelería, hace 4 años se lanzó en solitario, conoce cada rincón del valle, trato cercano y de tú a tú. Tono humano, no corporativo.
3. **Habitaciones** — 6 habitaciones con nombre, breve descripción y foto:
   - Ventana a Gredos (con balcón, vistas a la montaña) → `habitacion_01.png`
   - Suite del Fuego (chimenea + bañera de piedra) → `habitacion_02.png`
   - 4 habitaciones adicionales inventadas con nombres/temática coherente con la casa (piedra, bosque, río, olivo…), fotos de stock como placeholder.
4. **Galería** — mosaico de fotos (casa, entorno, interiores).
5. **Entorno / experiencias** — Sierra de Gredos, senderismo, naturaleza, rutas cercanas (`paisaje.png`, `entorno.png`).
6. **Contacto** — formulario de anfrage/disponibilidad: nombre, email, fechas deseadas, nº de personas, mensaje. Sin reserva ni pago — Laura responde personalmente. (En S4 se sustituye por reserva + pago real con Stripe.)

## 5. Contenido visual disponible

Ver listado de assets en `Brand_Book.md`. Placeholders de stock (vía Unsplash source o similar) para las 4 habitaciones sin foto propia.

## 6. Fuera de alcance (S3)

- Reservas reales / calendario de disponibilidad
- Pagos (Stripe)
- Agente de IA conversacional
- Multi-idioma

Todo esto llega en S4.
