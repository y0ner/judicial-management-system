# 🛠 Guía de Desarrollo (Mantenimiento para y0ner)

## 1. Actualizar Código
1. Entrar a: judicial-manager-source/
2. git add .
3. git commit -m "Descripción de cambios"
4. git push origin main

## 2. Actualizar Ejecutable (Binarios)
1. Reemplazar el .exe y la carpeta _internal en: judicial-manager-bin/
2. Entrar a esa carpeta.
3. git add .
4. git commit -m "Nueva versión ejecutable"
5. git push origin main

## 3. Sincronizar Repositorio Maestro
Desde la raíz del proyecto judicial-management-system:
1. git add .
2. git commit -m "Sync: Actualización de submódulos"
3. git push origin main

NOTA: Mantener historial.db en el .gitignore de la carpeta /bin.