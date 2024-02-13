# Copiar archivos de cierta extensión
Por ejemplo, si se necesitan copiar todos los archivos de extensión .pdf  del directorio "Downloads" al directorio copia_pdf

```PowerShell
Get-ChildItem C:\Users\TU_USUARIO\Downloads\ -Filter *.pdf |  Copy-Item -Destination C:\Users\TU_USUARIO\Downloads\copia_pdf\ -Force -PassThru
```

**OUTPUT**
```PowerShell
PS C:\Users\DaRk452> Get-ChildItem C:\Users\DaRk452\Downloads\ -Filter *.pdf | Copy-Item -Destination C:\Users\DaRk452\Downloads\copia_pdf\ -Force -PassThru


    Directory: C:\Users\DaRk452\Downloads\copia_pdf

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          03-04-2023    23:47          67513 000000326987478.pdf
-a---          17-05-2023     9:25          69423 000000330609270.pdf
-a---          07-08-2023    13:59          59140 1578.pdf
-a---          07-08-2023    14:10          59284 2096.pdf
```
