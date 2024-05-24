# Analisis de bebidas de starbucks

Se tomó el dataset de Kaggle: https://www.kaggle.com/datasets/ashishpatel26/starbucks-menu-nutrition-drinks

# Descripción del dataset

El dataset contiene información nutricional sobre diversas bebidas del menú de Starbucks. Aquí está un resumen de las columnas y su contenido:

<strong>Drink name:</strong> Nombre de la bebida.

<strong>Calories:</strong> Calorías de la bebida.

<strong>Fat (g):</strong> Grasa en gramos.

<strong>Carb. (g):</strong> Carbohidratos en gramos.

<strong>Fiber (g):</strong> Fibra en gramos.

<strong>Protein:</strong> Proteína en gramos.

<strong>Sodium:</strong> Sodio en miligramos.

# Limpieza de dataset

<strong>Cantidad de datos válidos:</strong> Hay 177 bebidas en total, pero las columnas numéricas (calorías, grasa, carbohidratos, fibra, proteína y sodio) tienen 92 valores válidos cada una.

<strong>Valores únicos:</strong> Hay 154 nombres de bebidas únicos.

<strong>Calorías:</strong>

Promedio: 135.16 calorías

Mínimo: 0 calorías

Máximo: 430 calorías

<strong>Grasa:</strong>

Promedio: 2.34 gramos

Mínimo: 0 gramos

Máximo: 26 gramos

<strong>Carbohidratos:</strong>

Promedio: 24.74 gramos

Mínimo: 0 gramos

Máximo: 64 gramos

<strong>Fibra:</strong>

Promedio: 0.45 gramos

Mínimo: 0 gramos

Máximo: 8 gramos

<strong>Proteína:</strong>

Promedio: 4.15 gramos

Mínimo: 0 gramos

Máximo: 20 gramos

<strong>Sodio:</strong>

Promedio: 57.93 miligramos

Mínimo: 0 miligramos

Máximo: 240 miligramos

# Bebidas bajas en calorias

Iced Coffee - 0 calorías, Nariño 70 Cold Brew with Milk - 0 calorías

# Bebidas bajas en grasa

Cool Lime Starbucks Refreshers™ Beverage - 0 g de grasa, Strawberry Acai Starbucks Refreshers™ Beverage - 0 g de grasa, Very Berry Hibiscus Starbucks Refreshers™ Beverage - 0 g de grasa, Iced Coffee - 0 g de grasa, Shaken Sweet Tea - 0 g de grasa, Tazo® Bottled Berry Blossom White - 0 g de grasa, Tazo® Bottled Iced Passion - 0 g de grasa, Tazo® Bottled Organic Iced Black Tea - 0 g de grasa, Teavana® Shaken Iced Black Tea - 0 g de grasa, Teavana® Shaken Iced Black Tea Lemonade - 0 g de grasa, Teavana® Shaken Iced Green Tea - 0 g de grasa, Teavana® Shaken Iced Green Tea Lemonade - 0 g de grasa, Teavana® Shaken Iced Passion Tango™ Tea - 0 g de grasa, Teavana® Shaken Iced Passion Tango™ Tea Lemonade - 0 g de grasa, Teavana® Shaken Iced Peach Green Tea - 0 g de grasa, Starbucks Refreshers™ Raspberry Pomegranate - 0 g de grasa, Starbucks Refreshers™ Strawberry Lemonade - 0 g de grasa, Starbucks® Iced Coffee Caramel - 0 g de grasa, Starbucks® Iced Coffee Light Sweetened - 0 g de grasa, Starbucks® Iced Coffee Unsweetened - 0 g de grasa, Blonde Roast - 0 g de grasa, Clover® Brewed Coffee - 0 g de grasa, Decaf Pike Place® Roast - 0 g de grasa, Featured Dark Roast - 0 g de grasa, Iced Coffee - 0 g de grasa, Nariño 70 Cold Brew - 0 g de grasa, Nariño 70 Cold Brew with Milk - 0 g de grasa, Nitro Cold Brew - 0 g de grasa, Pike Place® Roast - 0 g de grasa

# Bebidas bajas en carbohidratos

Iced Coffee - 0 g de carbohidratos, Blonde Roast - 0 g de carbohidratos, Clover® Brewed Coffee - 0 g de carbohidratos, Decaf Pike Place® Roast - 0 g de carbohidratos, Featured Dark Roast - 0 g de carbohidratos, Iced Coffee - 0 g de carbohidratos, Nariño 70 Cold Brew - 0 g de carbohidratos, Nariño 70 Cold Brew with Milk - 0 g de carbohidratos, Nitro Cold Brew - 0 g de carbohidratos, Pike Place® Roast - 0 g de carbohidratos

# Bebidas altas en fibra

Chocolate Smoothie - 8 g de fibra

# Bebidas altas en proteinas

Starbucks® Doubleshot Protein Dark Chocolate - 20 g de proteína, Starbucks® Doubleshot Protein Vanilla - 20 g de proteína, Chocolate Smoothie - 20 g de proteína

# Bebidas bajas en sodio

Iced Coffee - 0 mg de sodio, Starbucks® Iced Coffee Caramel - 0 mg de sodio, Starbucks® Iced Coffee Light Sweetened - 0 mg de sodio, Starbucks Refreshers™ Raspberry Pomegranate - 0 mg de sodio, Starbucks Refreshers™ Strawberry Lemonade - 0 mg de sodio, Teavana® Shaken Iced Black Tea Lemonade - 0 mg de sodio, Teavana® Shaken Iced Passion Tango™ Tea Lemonade - 0 mg de sodio, Teavana® Shaken Iced Peach Green Tea - 0 mg de sodio, Very Berry Hibiscus Starbucks Refreshers™ Beverage - 0 mg de sodio

# Bebida con mas calorias

Starbucks® Signature Hot Chocolate - 430 calorías

# Distribucion de Calorias

![image](https://github.com/mstovarh/analisis-de-bebidas-de-starbucks/assets/107591274/b9aabfb7-747b-46b2-a6c2-45a3818aee19)

# Correlaciones

<h3>Relacion entre calorias y proteinas</h3>

![image](https://github.com/mstovarh/analisis-de-bebidas-de-starbucks/assets/107591274/a52c4d87-9a93-43df-b5d4-ea8204359115)

La gráfica muestra la relación entre las calorías y las proteínas en las bebidas de Starbucks. Observamos que hay una tendencia positiva: a medida que aumentan las calorías, también tiende a aumentar la cantidad de proteínas en las bebidas.

Además, la correlación entre las calorías y las proteínas es de aproximadamente 0.775. Esto indica una relación positiva moderadamente fuerte entre estos dos nutrientes: las bebidas con más calorías tienden a tener más proteínas.

<h3>Relaciones positivas y fuertes con calorías</h3>

<strong>Grasa (g):</strong> Correlación de 0.756

<strong>Carbohidratos (g):</strong> Correlación de 0.871

<strong>Fibra (g):</strong> Correlación de 0.520

<strong>Proteína (g):</strong> Correlación de 0.775

<strong>Sodio (mg):</strong> Correlación de 0.730
