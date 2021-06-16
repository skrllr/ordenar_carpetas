<p align="center">
    <a href="https://github.com/skrllr/inicio" rel="skllr-github">
        <img alt="skrllr" href="https://github.com/skrllr/inicio" src="https://github.com/skrllr/inicio/blob/main/85305964_v%3D4.png" width="100" height="100">
    </a>
</p>

<h1 align="center">SKRLLR</h1>

<p>
    <p align="center">Proyectos de <a href="https://opensource.org/licenses/gpl-license">Código Abierto</a>.</p>
    <p align="center">Si desea modificar el código y subir el repositorio debera mencionarme o incluir el link del repositorio en el código del proyecto</p>
</p>

<h5 align="center">Lenguajes usados en los repositorios</h5>

<p align="center">
    <a href="https://www.python.org/downloads/release/python-2718/" rel="python2">
        <img src="https://warehouse-camo.ingress.cmh1.psfhosted.org/881cfcf3a7bb3768bcc2d9dca81bfd56b60b224e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d322d626c75652e7376673f763d31">
    </a>
    <a href="https://www.python.org/downloads/" rel="python3">
        <img src="https://warehouse-camo.ingress.cmh1.psfhosted.org/556b6e525e3481d6b0ea60137f79c803b1d61ce1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d332d626c75652e7376673f763d31">
    </a>
</p>

### ORDENADOR DE DESCARGAS

Código obtenido de `https://youtu.be/C-eyVKGsBXg` el código ha sido modificado para que organice los archivos cada cierta cantidad de segundos, también pondre los pasos para crearlo en un .exe que se ejecute en primer y segundo plano.

#### Convertir a .exe

Necesitaras `cx_freeze`
```cmd
pip install cx_Freeze
```

Crear .exe que se ejecute en primer plano
```
cxfreeze script.py --target-dir dist
```

<br>

Crear .exe que se ejecute en segundo plano
```
cxfreeze script.py --base-name=Win32GUI --target-dir dist
```
