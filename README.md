# -robot_trading-
        #aluraChallengeRobotTrading
![challenge_4](https://github.com/wilferalexander/-robot_trading-/assets/16104315/ad5e07ea-a36b-4da2-bf41-f2c1936ecac5)

![image](https://github.com/wilferalexander/-robot_trading-/assets/16104315/6f1e016f-58d6-43c5-9f86-bc944ede3c47)


        https://discord.com/channels/@me/1166083152293412905/1167542608084598854

       ![challenge_1](https://github.com/wilferalexander/-robot_trading-/assets/16104315/e61e3664-4fe2-4398-b97c-947957973407)

Este proyecto se trabajo con Python , Numpy , Matplotlib, Web Scraping para detrminar el comportamiento del Bitcoin 
# - Descripcion del proyecto 
este proyecto se trabajo como parte del bootcamp de alura latam donde se trabajo de la siguiente en 6 etapas el cual consiste 
Vamos a contruir un Robot Trading en Python capaz de tomar decisiones de compra y venta de Bitcoin en tiempo real, ¿interesante verdad?, aqui te proporciono el paso a paso que deberás realizar:
# 1. Configuracion del ambiente:
        Para empezar, puedes utilizar un entorno virtual como Google Colaboratory, o si deseas, puedes usar el editor Python de tu preferencia,
        sólo asegúrate de tener Python 3.x instalado en tu computadora. También necesitarás instalar algunas librerías de Python que son esenciales
        para este proyecto, como Pandas, Numpy, Matplotlib, etc.
# 2.  Obtención de datos:
     Para empezar, puedes utilizar un entorno virtual como Google Colaboratory, o si deseas, puedes usar el editor Python de tu preferencia,
     sólo asegúrate de tener Python 3.x instalado en tu computadora. También necesitarás instalar algunas librerías de Python que son esenciales para este proyecto, como Pandas, Numpy, Matplotlib, etc.
# 3. Limpieza de datos:
     Una vez que tengas los datos históricos deberás cargarlos en un DataFrame de Pandas para poder manipularlos y analizarlos, deberás identificar y eliminar los outliers,
     además de tratar cualquier valor nulo o duplicados en la base. Finalmente, con la base limpia, calcula el precio promedio del Bitcoin.
# 4. Tomar decisiones: 
     Una vez que tengas el precio promedio, compáralo con el precio actual y tendencia del Bitcoin, que previamente obtuviste con Web Scraping.
     Si el precio actual es mayor/igual que la media y la tendencia es de baja, entonces se debe vender, pero si el precio actual es menor que la media y la tendencia es de alta,
     entonces se debe comprar.
# 5. Visualización:
     Utiliza la librería Matplotlib para crear un gráfico donde se muestre la evolución del precio del Bitcoin durante el periodo seleccionado,
     y una línea recta que pase sobre el precio medio. Por último, muestra un mensaje en el gráfico que indique “Vender”, “Comprar” o “” según sea la decisión del algoritmo.
# 6. Automatización:
      Finalmente, ahora que tienes el algoritmo de decisión, es hora de automatizar el proceso. Utiliza la librería de Python "time" para ejecutar el algoritmo de decisión cada 5 minutos y actualizar el gráfico.
      
