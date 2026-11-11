---
name: noticias-linkedin-visualtrans
description: Briefing diario de noticias del sector aduanero, transitario, logístico y marítimo para publicar en LinkedIn desde Visual Trans. Busca lo publicado en las últimas 24-48 h, filtra y devuelve en el chat las 3 noticias más publicables con su ángulo para LinkedIn. Usa esta skill siempre que el usuario pida las noticias del día, el briefing, "noticias para LinkedIn", "noticias del sector", "qué publico hoy", o cuando una tarea programada la invoque por su nombre, aunque no diga "skill".
---

# Noticias diarias para LinkedIn · Visual Trans

Objetivo: que Adrián (marketing de Visual Trans) sepa en 2 minutos qué noticia del sector merece un post hoy. Es una **selección para publicar**, no una revista de prensa. Respuesta en el chat, en español.

## Reglas fijas (léelas antes de empezar)

1. **Máx. 8 búsquedas** y **máx. 4 artículos abiertos**. Cuenta cada llamada. Al llegar al límite, para y redacta con lo que tengas.
2. **Respuesta de máx. 350 palabras.**
3. **Nunca inventes** un enlace, una fecha, un medio ni un dato. Copia el enlace exactamente como aparece en el resultado de búsqueda. Si no tienes fecha confirmada, descarta la noticia.
4. **Parafrasea siempre.** Como mucho una cita literal de menos de 15 palabras por fuente.
5. Mejor 2 noticias buenas que 5 flojas. Nunca rellenes.

## Contexto: a quién le escribe Visual Trans (ICP)

- **Clientes:** transitarios, agentes de aduanas, operadores logísticos, consignatarios de buques y cargadores (importadores/exportadores).
- **Mercado:** España (sede en O Porriño, Galicia) y +25 países. Lo que no afecte a España o la UE no interesa.
- **Productos:** software de gestión para el sector y IA: V-Extract (digitalización de documentos), asistente virtual aduanero y atención al cliente automatizada.

## Proceso

### Paso 1 · Fecha y ventana
- Usa la fecha de hoy del contexto (o ejecuta `date` si no la tienes). Escríbela: día de la semana + fecha.
- Ventana = **últimas 24 h**. Si hoy es **lunes**, ventana = desde el **viernes por la mañana**.

### Paso 2 · Búsquedas (máx. 8)
Usa la búsqueda web en modo estándar. Haz las 4 primeras en este orden; añade "hoy" o el mes y año actuales a cada consulta:

1. `noticias aduanas España`
2. `transitarios logística noticias`
3. `transporte marítimo puertos España noticias`
4. `Unión Europea aduanas normativa` (reforma aduanera, ICS2, CBAM, aranceles, DUA, AEAT)

Con las 4 restantes, como mucho:
- Profundiza en el tema más fuerte que haya salido (otra fuente, la fecha exacta, la reacción del sector).
- O cubre un hueco: tecnología/IA en logística, empresas del sector, huelgas o congestión en puertos españoles, fletes.
- No repitas una consulta con sinónimos.

**Para en cuanto tengas 3 candidatas fuertes**, aunque no hayas gastado las 8.

Fuentes habituales útiles (no obligatorias): Diario del Puerto, Cadena de Suministro, Logística Profesional, El Mercantil, Transporte XXI, Veintepies, AEAT, Comisión Europea.

### Paso 3 · Descarta sin abrir
Decide solo con titular y resumen. Descarta:
- Fuera de la ventana de fechas o sin fecha clara.
- Sucesos (incautaciones, accidentes, detenciones).
- Otros países sin efecto en España/UE.
- Notas de prensa autopromocionales sin interés para el ICP.
- Duplicados: de varios medios con la misma noticia, quédate con el más completo.

### Paso 4 · Abre solo finalistas (máx. 4)
Abre un artículo **solo** si el resumen no deja clara la fecha o el contenido. Lee el titular, la entradilla y los primeros párrafos; no hace falta más.

### Paso 5 · Puntúa (interno, no lo muestres)
Da 0, 1 o 2 puntos en cada criterio (máx. 8):

| Criterio | 2 puntos si… |
|---|---|
| Impacto en el ICP | Cambia el trabajo diario de un transitario, agente, operador o consignatario. |
| Actualidad | Es de hoy/ayer o un plazo que entra en vigor ya. |
| Encaje con Visual Trans | Conecta con papeleo, documentos, trámites aduaneros, atención al cliente o digitalización. |
| Conversación | Tiene un dato llamativo, polémica o una voz relevante del sector. |

- Publica las de **5 puntos o más**, ordenadas de mayor a menor.
- 3 por defecto; 4-5 solo si empatan en puntuación alta.
- Si ninguna llega a 5: usa la salida "sin noticias" (abajo).

### Paso 6 · Radar de competencia
Si algún resultado menciona a un proveedor de software del sector (p. ej. Bytemaster u otros ERP aduaneros o logísticos), anótalo aunque no entre en el top.

## Formato de salida

Copia esta plantilla exacta. Sustituye lo que va entre corchetes.

```
📰 Briefing del [día de la semana] [fecha] · [N] noticias revisadas

---

### 1. [Titular reescrito, máx. 10 palabras]
**[Medio] · [fecha]** · [enlace]

- **Qué pasa:** [1-2 frases con tus palabras]
- **Por qué le importa al ICP:** [1 frase: a quién afecta y cómo]
- **Ángulo para LinkedIn:** [gancho en 1 frase] · *Tipo: opinión / dato / explicación práctica / debate*

---

### 2. ...

---

### ✅ Recomendación del día
[Cuál publicar primero y por qué, en 1-2 frases]

### 🔍 Radar de competencia
[Solo si hay menciones a competidores; si no, borra esta sección entera]
```

- `[N] noticias revisadas` = número de resultados distintos que has valorado.
- Elige **un solo** tipo de ángulo por noticia.

**Salida "sin noticias":** una línea diciendo que hoy nada supera el filtro + un tema evergreen del sector como alternativa (p. ej. errores frecuentes en el DUA, cómo la IA reduce el tecleo de documentos).

### Ejemplo de formato (noticia ficticia: no la uses ni la cites)

```
### 1. La UE adelanta la ventanilla única aduanera
**Diario del Puerto · 10/11/2026** · https://...

- **Qué pasa:** Bruselas fija un calendario más corto para que los operadores declaren a través del nuevo centro de datos aduanero de la UE.
- **Por qué le importa al ICP:** Agentes de aduanas y transitarios tendrán que adaptar sistemas y procesos antes de lo previsto.
- **Ángulo para LinkedIn:** ¿Está tu despacho preparado para declarar con menos margen? · *Tipo: explicación práctica*
```

## Antes de enviar, comprueba

- [ ] Cada noticia tiene medio, fecha dentro de la ventana y enlace copiado del resultado.
- [ ] Nada copiado literalmente salvo, como mucho, una cita corta.
- [ ] Máx. 350 palabras. Sin introducción ni despedida fuera de la plantilla.
- [ ] Radar de competencia borrado si está vacío.

## Después

No redactes el post completo salvo que el usuario lo pida. Si lo pide y existe la skill `linkedin-content-system`, úsala para redactarlo con el estilo del perfil correspondiente.
