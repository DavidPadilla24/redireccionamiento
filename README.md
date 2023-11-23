# Redireccionamiento

### Enunciado: Genera un archivo llamado informe.txt que contenga la siguiente informacion : 

  La fecha del sistema formateada dia mes y año.

  Espacio en disco (df -h)
  
  Usuarios conectados (who)
  
  Memoria libre del sistema (free -h)
  
  Subir imagen ejecucion del script ejecutado con exito.
  

```
#!/bin/bash 
echo "Fecha: $(date +%d-%m-%Y)"

echo "Espacio en Disco:"
df -h   

echo "Usuarios conectados:"
who

echo "Memoria libre del sistema:"
free -h

```
