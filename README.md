# famaf-cover

Paquete para la carátula de trabajos especiales de FAMAF.

Se trato de seguir el formato mencionado en [RHCD 572-2024](https://digesto.unc.edu.ar/bitstream/handle/123456789/555220/RHCD-2024-572-UNC-DEC%23FAMAF.pdf).

Por el momento solo se soporta el formato para [trabajo especial](https://digesto.unc.edu.ar/bitstream/handle/123456789/555220/ANEXO%20II%20EX-2024-00821156-%20-UNC-ME%23FAMAF.pdf).
Estaria bueno soportar también el de [trabajo final de prácticas](https://digesto.unc.edu.ar/bitstream/handle/123456789/555220/ANEXO%20I%20-%20%20EX-2024-00821156-%20-UNC-ME%23FAMAF.pdf).

Basado originalmente en [esta carátula](https://github.com/IvanRenison/Tesis-Licenciatura/blob/main/Car%C3%A1tula.tex).

## Uso

Hay 2 alternativas principales.

En artículos nuevos, se puede clonar/forkear el repositorio para uso offline, o descargar como zip para importarlo en overleaf directamente.

En artículos existentes lo más conveniente sería incorporar `famafCover.sty` junto con el directorio `logos` al proyecto, revisar el ejemplo de uso en `main.tex`.

### Pequeña nota si se quiere usar memoir

Si se quiere usar *memoir* en vez de *article*, se debe cambiar la `titlepage` en `famafCover.sty` por `titlingpage`

## Algunos links utiles

Los logos fueron obtenidos de:

- [UNC](https://www.unc.edu.ar/comunicaci%C3%B3n/versiones-descargables-del-escudo-de-la-unc)
- [FAMAF](https://www.famaf.unc.edu.ar/la-facultad/institucional/secretar%C3%ADas/prosecretar%C3%ADa-de-comunicaci%C3%B3n-y-divulgaci%C3%B3n-cient%C3%ADfica/)

[Ejemplos de Trabajos Especiales de Computación](https://rdu.unc.edu.ar/handle/11086/16727?type=dateissued).
