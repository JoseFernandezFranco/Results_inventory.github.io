# README de ejecución

Descarga `reproducir_estudios_8_archivos.zip`, descomprímelo en una carpeta local y ejecuta `ejecutame.ps1`.

El ZIP incluye exactamente 5 scripts, 2 CSV y 1 PowerShell. El propio `ps1` prepara el runtime interno, instala dependencias la primera vez y genera todos los resultados en `results/`.

## Comando

```powershell
.\ejecutame.ps1
```

## Reinstalar dependencias

```powershell
.\ejecutame.ps1 -ReinstalarDependencias
```
