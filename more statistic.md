
# Crear un vector numérico
mi_vector_num <- c(1, 2, 3, 4, 5)
# Calcular la media y la desviación estándar del vector
media <- mean(mi_vector_num)
desviacion_estandar <- sd(mi_vector_num)
# Graficar un histograma del vector
hist(mi_vector_num)
# Graficar un diagrama de cajas del vector
boxplot(mi_vector_num)



# Crear dos vectores numéricos
x <- c(1, 2, 3, 4, 5)
y <- c(2, 4, 6, 8, 10)

# Calcular la media y la desviación estándar de los vectores
media_x <- mean(x)
media_y <- mean(y)
desviacion_estandar_x <- sd(x)
desviacion_estandar_y <- sd(y)

# Graficar un diagrama de dispersión de los vectores
plot(x, y)
# Calcular la matriz de correlación de los vectores
matriz_correlacion <- cor(x, y)
# Graficar una matriz de correlación de los vectores
corrplot(matriz_correlacion, method = "circle")


# Crear tres vectores numéricos
grupo1 <- c(1, 2, 3, 4, 5)
grupo2 <- c(2, 4, 6, 8, 10)
grupo3 <- c(3, 6, 9, 12, 15)

# Realizar un ANOVA
modelo <- aov(c(grupo1, grupo2, grupo3) ~ rep(1:3, each = 5))
# Graficar un diagrama de cajas de los tres grupos
boxplot(grupo1, grupo2, grupo3)
# Graficar un gráfico de barras de los tres grupos
barplot(c(mean(grupo1), mean(grupo2), mean(grupo3))).
