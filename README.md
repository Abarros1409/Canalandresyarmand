# Canal de Andrés y Armand

Hub del proyecto: plan de 90 días, banco de ideas, producción, marca, estadísticas, revisiones y bitácora.

- **Hub publicado:** https://claude.ai/artifact/T5RpSd4adVM2kvkF9hRDR2
- **Código del hub:** [`hub/index.html`](hub/index.html)
- **Contexto del proyecto:** [`CONTEXTO.md`](CONTEXTO.md)

## Cómo editamos los dos

Los datos se guardan en la base de datos del artifact en Claude (no en el navegador), así que lo que carga uno lo ve el otro al instante, en la compu o en el celular.

Para que Armand pueda editar (y no solo mirar):

1. Andrés (el dueño) abre el hub en claude.ai y toca **Compartir**.
2. En **Acceso general**, desactiva el enlace público ("cualquiera con el enlace"). Con el enlace público activado, los invitados de afuera solo pueden mirar.
3. Invita a Armand con el email de su cuenta de Claude y le da permiso de **Editor**.
4. Armand abre el hub con su sesión iniciada y elige "Armand" cuando se lo pregunte. Queda vinculado a su cuenta, en cualquier dispositivo.

Si alguien entra sin permiso de edición, el hub lo avisa con un cartel amarillo y no deja escribir.

## Cómo guarda

- Cada cambio escribe solo lo que tocó (un objetivo, un voto, una táctica), así dos personas editando a la vez no se pisan.
- Arriba a la derecha se ve el estado: *Guardando…*, *Guardado* o *Sin guardar*.
- Cada cambio queda firmado con quién lo hizo y cuándo, y aparece en **Inicio → Últimos cambios**.

## Actualizar el hub

Editar `hub/index.html` y republicarlo en el mismo enlace desde Claude Code (Artifact con la misma URL). Los datos no se tocan al republicar.
