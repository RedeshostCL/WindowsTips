# Buscar Archivos de cierta extensión

Por ejemplo si requiren buscar todos los archivos de extensión .pdf en el directorio "Descargas"

```PowerShell
Get-ChildItem C:\Users\TU_USUARIO\Descargas -Filter *.pdf 
```

**OUTPUT**
```PowerShell
PS C:\Users\DaRk452> Get-ChildItem C:\Users\DaRk452\Downloads\ -Filter *.pdf

    Directory: C:\Users\DaRk452\Downloads

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          03-04-2023    23:47          67513 000000326987478.pdf
-a---          17-05-2023     9:25          69423 000000330609270.pdf
-a---          07-08-2023    13:59          59140 1578.pdf
-a---          07-08-2023    14:10          59284 2096.pdf
```
