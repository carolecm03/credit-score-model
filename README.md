# Proyecto de Modelos Predictivos - Predicción del Puntaje Crediticio a partir de Características Demográficas y Financieras 

Este repositorio contiene el desarrollo del proyecto final de la materia Modelos Predictivos de la Maestría en Analítica de Datos de la Universidad Tecnológica de Panamá.

## 📌 Objetivo
Predecir el puntaje crediticio (`credit_score`) de un cliente utilizando variables demográficas y financieras, e implementar reglas de negocio para asignar límites de tarjeta de crédito.

## 🧠 Algoritmo Principal
Modelo de Random Forest Regressor con evaluación por R², MAE y RMSE.

## 💳 Reglas de Negocio
Se definieron reglas para clientes con y sin historial, considerando perfiles de riesgo y variables como ingreso, deuda, edad y número de tarjetas.

## 🔗 Anexos
- [Base de Datos](users_data_credit_cards.csv)
- ####🧾 Diccionario de Datos - users_data_credit_cards.csv

| Columna               | Descripción                                                                 |
|-----------------------|------------------------------------------------------------------------------|
| `id`                  | Identificador único del cliente                                              |
| `current_age`         | Edad actual del cliente (en años)                                            |
| `retirement_age`      | Edad estimada de retiro                                                      |
| `years_to_retirement` | Años restantes para la jubilación (retirement_age - current_age)            |
| `birth_year`          | Año de nacimiento del cliente                                                |
| `birth_month`         | Mes de nacimiento del cliente                                                |
| `gender`              | Género del cliente (0 = Masculino, 1 = Femenino)                             |
| `yearly_income`       | Ingreso anual del cliente (en dólares)                                       |
| `per_capita_income`   | Ingreso per cápita por hogar (en dólares)                                    |
| `total_debt`          | Total de deuda acumulada (en dólares)                                        |
| `num_credit_cards`    | Número total de tarjetas de crédito activas                                  |
| `credit_score`        | Puntaje crediticio real del cliente                                          |
| `predicted_score`     | Puntaje crediticio estimado por el modelo de regresión                       |
| `debt_to_income_ratio`| Relación entre deuda total e ingreso anual                                   |
| `limite_tarjeta`      | Límite de crédito asignado según reglas de negocio y riesgo financiero       |

- [Análisis Descriptivo](Proyecto_CreditScore_Limite_Final.ipynb)
- [Análisis Predictivo](Proyecto_CreditScore_Limite_Final.ipynb)
- [Reporte en Word](Reporte_Final_Caroline_Cardenas_Completo.docx)


---
**Autor:** Caroline Cárdenas  
**Profesor:** Juan Marcos Castillo, PhD
