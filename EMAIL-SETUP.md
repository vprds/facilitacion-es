# Email — hola@facilitacion.es

Patrón usado en [[Projects/Evolve/Overview|Evolve]] y [[Professional/victor-paredes.com|victor-paredes.com]]: **GoDaddy forwarding €0** → Gmail existente.

## GoDaddy (5 min)

1. [GoDaddy](https://dcc.godaddy.com/) → `facilitacion.es` → **Email** → **Forwarders**
2. Crear: `hola` → `tu-email@gmail.com` (inbox principal de Victor)
3. Guardar · propagación ~15 min

**Importante:** no tocar registros MX existentes si el dominio solo usa forwarding (GoDaddy añade el forwarder sin buzón propio).

## Verificar

Enviar test desde otro email a `hola@facilitacion.es` — debe llegar al inbox de destino.

Probar también un mailto desde [facilitacion.es](https://facilitacion.es) (situación 01 o formato Mapa de avance).

## Alternativa futura

Migadu o Zoho cuando quieras buzón propio con múltiples alias o respuesta desde `@facilitacion.es`.
