# Turbo Engine Exhaust Knowledge Base

Knowledge base for improving autodetection and measurement checking in the application.

The app should compare measured exhaust flange geometry (port count/shape/size, stud/bolt count & pattern, overall flange dimensions) against these known-good references.

## Structure
- `engines/` – one JSON (and optional notes) per engine family/variant
- `lists/top-engines.md` – curated priority list of popular turbo / high-boost-capable engines
- Data is approximate/community-sourced where OEM drawings are not public. Always cross-check with physical parts or official service data for production use.

## Key Fields for Autodetection
- `cylinder_count`
- `exhaust_ports` (count, shape, approx dimensions)
- `stud_or_bolt_count`
- `stud_thread` / size
- `port_spacing` / center-to-center where known
- `flange_notes` (split manifold, integrated, etc.)
- Common aftermarket turbo flange standards (T3, T4, V-band sizes)

## Priority Engines (initial set)
See `lists/top-engines.md` and individual files under `engines/`.

Contributions / corrections welcome – especially measured CAD or precise OEM dimensions.
