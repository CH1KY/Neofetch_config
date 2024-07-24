
```markdown
# Configuración de Neofetch

Este repositorio contiene una configuración personalizada para Neofetch.

## Instalación de Neofetch

Para instalar Neofetch, sigue estas instrucciones según tu sistema operativo:

### En Debian/Ubuntu

Abre una terminal y ejecuta estos comandos uno por uno:

```sh
sudo apt update
sudo apt install neofetch
```

### En Arch Linux

Abre una terminal y ejecuta este comando:

```sh
sudo pacman -S neofetch
```

### En Fedora

Abre una terminal y ejecuta este comando:

```sh
sudo dnf install neofetch
```

### En macOS (usando Homebrew)

Abre una terminal y ejecuta este comando:

```sh
brew install neofetch
```

## Usar esta configuración

Para usar esta configuración de Neofetch, sigue estos pasos:

1. **Clona este repositorio:**

   Abre una terminal y ejecuta:

   ```sh
   git clone https://github.com/CH1KY/Neofetch_config.git
   cd Neofetch_config
   ```

2. **Copia el archivo de configuración:**

   Ejecuta este comando en la terminal:

   ```sh
   mkdir -p ~/.config/neofetch
   cp config.conf ~/.config/neofetch/config.conf
   ```

   Esto crea un directorio de configuración para Neofetch y copia el archivo de configuración personalizado a ese directorio.

## Cambiar la imagen en la configuración

Para cambiar la imagen que se muestra en Neofetch:

1. Abre el archivo `config.conf` en un editor de texto (puedes usar `nano`, `vim`, `gedit` o cualquier otro editor).

2. Busca la línea que contiene `image_source`.

3. Cambia el valor de `image_source` por la ruta de tu nueva imagen. Por ejemplo:

   ```sh
   # Cambia esta línea a la ruta de tu imagen
   image_source="/ruta/a/tu/imagen.png"
   ```

## Añadir una imagen de fondo

Para incluir una imagen de fondo en esta sección del `README.md`:

1. Sube la imagen al repositorio.

2. Añade la siguiente línea al final de este archivo, reemplazando `fondo.png` con el nombre de tu archivo de imagen:

   ```markdown
   ![Fondo](/home/ch1ky/Pictures/image.jpg)
   ```
