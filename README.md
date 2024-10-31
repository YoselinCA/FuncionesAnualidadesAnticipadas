# FuncionesAnualidadesAnticipadas

```
source(https://raw.githubusercontent.com/YoselinCA/FuncionesAnualidadesAnticipadas/refs/heads/main/FuncionesAnualidadesAnticipadas.R)
```
**FV: Valor Futuro (VF) <br>
PV: Valor Actual (VA)<br>
A: Anualidad o Pago periódico (A)<br>
r: Tasa de interés del periodo (r)<br>
n: Número de pagos o plazo (n)**

# Calculo para Valor Futuro (VF)

Vfuturo = round(VF(A = 500, r = 0.05706, n = 10))


# Calculo para Anualidad (A) conociendo valor futuro
 
Anualidad = round(A(VF = 6500, r = 0.05706, n = 10))


# Calculo para Número de Pagos (n) conociendo valor futuro
 
NPagos = round(n(VF = 6500, r = 0.05706, A = 500))


# Calculo para tasa de interes (r) conociendo valor futuro

tasa = round(r(VF = 6500, A = 500, n = 10),4)


# Calculo para Valor Actual (VA)

V_actual = round(VA(A = 400, r = 0.02504, n = 10))


# Calculo para Anualidad (A) conociendo valor actual
 
Anualidad2 = round(A_(VA = 3500, r =  0.02504, n = 10))


# Calculo para Número de Pagos (n) conociendo valor actual
 
NPagos2 = round(n_(VA = 3500, r =  0.02504, A = 400))


# Calculo para tasa de interes (r) conociendo valor actual

tasa2 = round(r_(VA = 3500, A = 400, n = 10),4)
