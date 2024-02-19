# Meme_Dict
diccionario de memes
meme_dict = {
    "doxear":"sacar la toda información personal y datos de una persona",
    "hater":"persona que hiere o insulta a otras personas por redes sociales",
    "random":"frase utilizada para referirse a una persona desconocida o para burla",
    "cancelar":"se refiere a dejar de apoyar a una persona por redes sociales por algún comentario o acción grave que hizo"
    }

word = input("Por favor escribir una palabra moderna que no entiendes:")
if word in meme_dict.keys():
   print(meme_dict[word])
else:
    print("No no está en el diccionario")
