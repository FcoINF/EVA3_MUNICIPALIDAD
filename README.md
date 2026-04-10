--Explicación para ejecutar este sistema--

Es necesario instalar lo siguiente:

pip install openai
pip install python-dotenv

una vez listo, en las variables base_url ingresamos la URL de GitHub base ("https://models.inference.ai.azure.com")
y en api_key ingresamos nuestro token de GitHub.

Dentro de nuestro menú están las opciones que se pueden elegir para preguntar dentro del sitio web,
hay 4 opciones y cada una le da el contexto a la IA sobre lo que el usuario le va a preguntar, 
menos la de chat general que es una conversación directa con la IA, y con una opción para salir.

Las opciones se eligen mediante un numero del 1 al 6 que elija el usuario, dependiendo de la opción,
se informa a la IA el tema sobre lo que el usuario esta preguntando, si la opción ingresada no es un
numero entero o es una opción que no existe, avisara al usuario que es una opción inválida .

La problematica a solucionar en base a este proyecto es facilitar a los usuarios realizar consultas o tener un acesso
directo a lo que buscan apenas entrar a la página de la municipalidad, en base a esto podemos optimizar muchos procesos gracias al
ChatBOT.
