# Lo-aprendido-en-tic-s
with open("README.md", "r", encoding="utf-8") as f:
    contenido = f.read()

with open("INFORME_GENERAL.md", "w", encoding="utf-8") as f:
    f.write(contenido)
