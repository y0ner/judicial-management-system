# 📦 Guía de Instalación Selectiva (Solo Binarios)

Para descargar solo la aplicación sin el código fuente, siga estos pasos:

## Paso 1: Clonado inicial (Modo Filtro)
git clone --filter=blob:none --no-checkout https://github.com/y0ner/judicial-management-system.git
cd judicial-management-system

## Paso 2: Configurar Sparse Checkout (Descarga Selectiva)
git sparse-checkout init --cone
git sparse-checkout set judicial-manager-bin

## Paso 3: Descargar el contenido final
git checkout main

## Paso 4: Cómo actualizar la App
Para recibir nuevas versiones del ejecutable en el futuro, solo ejecute:
git pull origin main