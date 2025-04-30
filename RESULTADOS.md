# 📊 Análisis de Consultas SQL

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre
-Disco duro SATA3 1TB
-Memoria RAM DDR4 8GB
-Disco SSD 1 TB
-GeForce GTX 1050Ti
-GeForce GTX 1080 Xtreme
-Monitor 24 LED Full HD
-Monitor 27 LED Full HD
-Portátil Yoga 520
-Portátil Ideapd 320
-Impresora HP Deskjet 3720
-Impresora HP Laserjet Pro M26nw
+codigo | nombre | precio | codigo_fabricante
+1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
+2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
+3.00 | Disco SSD 1 TB | 150.99 | 4.00
+4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
+6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
+7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
+11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
```
- ⏱ Tiempo: 0.34 ms
- 🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 2: Correcto
- ⏱ Tiempo: 0.31 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 3: Correcto
- ⏱ Tiempo: 0.3 ms
- 🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 4: Correcto
- ⏱ Tiempo: 0.29 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 5: Correcto
- ⏱ Tiempo: 0.29 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 6: Correcto
- ⏱ Tiempo: 0.29 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 7: Correcto
- ⏱ Tiempo: 0.3 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 8: Correcto
- ⏱ Tiempo: 0.28 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 9: Correcto
- ⏱ Tiempo: 0.27 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 10: Correcto
- ⏱ Tiempo: 0.27 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 11: Correcto
- ⏱ Tiempo: 0.27 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

---
## ✅ Query 12: Correcto
- ⏱ Tiempo: 0.27 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 13: Correcto
- ⏱ Tiempo: 0.29 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 14: Correcto
- ⏱ Tiempo: 0.27 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 15: Correcto
- ⏱ Tiempo: 0.26 ms
- 🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 16: Correcto
- ⏱ Tiempo: 0.29 ms
- 🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 17: Correcto
- ⏱ Tiempo: 0.27 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 18: Correcto
- ⏱ Tiempo: 0.35 ms
- 🔍 No se usó ningún índice en esta consulta.

---
## ✅ Query 19: Correcto
- ⏱ Tiempo: 0.34 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

---
## ✅ Query 20: Correcto
- ⏱ Tiempo: 0.33 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 21: Correcto
- ⏱ Tiempo: 0.35 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 22: Correcto
- ⏱ Tiempo: 0.34 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 23: Correcto
- ⏱ Tiempo: 0.36 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 24: Correcto
- ⏱ Tiempo: 0.33 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 25: Correcto
- ⏱ Tiempo: 0.37 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 26: Correcto
- ⏱ Tiempo: 0.38 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 27: Correcto
- ⏱ Tiempo: 0.36 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 28: Correcto
- ⏱ Tiempo: 0.34 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 29: Correcto
- ⏱ Tiempo: 0.34 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 30: Correcto
- ⏱ Tiempo: 0.34 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 31: Correcto
- ⏱ Tiempo: 0.38 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 32: Correcto
- ⏱ Tiempo: 0.37 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---
## ✅ Query 33: Correcto
- ⏱ Tiempo: 0.38 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

---
## ✅ Query 34: Correcto
- ⏱ Tiempo: 0.33 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

---
## ✅ Query 35: Correcto
- ⏱ Tiempo: 0.37 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 36: Correcto
- ⏱ Tiempo: 0.39 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 37: Correcto
- ⏱ Tiempo: 0.39 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

---
## ✅ Query 38: Correcto
- ⏱ Tiempo: 0.38 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

---
## ✅ Query 39: Correcto
- ⏱ Tiempo: 0.39 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
## ✅ Query 40: Correcto
- ⏱ Tiempo: 0.43 ms
- ✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
