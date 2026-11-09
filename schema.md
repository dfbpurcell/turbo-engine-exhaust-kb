# JSON Schema Guidance for Engine Entries

```json
{
  "engine": "string (canonical name)",
  "variants": ["string"],
  "configuration": "string",
  "displacement_cc": number or string,
  "block": "string",
  "popular_for": "string",
  "exhaust": {
    "ports": number,
    "port_shape": "string",
    "approx_port_dimensions_mm": "string or object",
    "stud_or_bolt_count": number or string,
    "stud_thread": "string",
    "stud_notes": "string",
    "flange_style": "string",
    "common_aftermarket_turbo_flanges": ["string"],
    "useful_checks": ["string"]
  },
  "sources_notes": "string"
}
```

Add measured center-to-center port spacing, overall flange length/width, and bolt hole coordinates when available for precise geometric matching.
