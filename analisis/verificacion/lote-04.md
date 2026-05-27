# Lote 04 — Verificación de citas a la propuesta SPEA (ítems 16–20)

Fuente de verdad: `analisis/extraccion/spea/pNNN.txt` (texto SPEA) y `analisis/extraccion/eval/pNNN.txt` (ISEGORÍA/eval).
Criterio: presencia verbatim (se toleran diferencias de OCR/espaciado/acentos y matemáticas perdidas en extracción).
Estados: OK / PÁGINA INCORRECTA / NO ENCONTRADA.

## item-16
| Cita/afirmación (abreviada) | Pág. citada | Estado | Pág. real / Nota |
|---|---|---|---|
| Estimador HT puntual (forma básica y calibrada) | 128 | OK | p128: "estimador de Horvitz-Thompson... La forma básica... La forma calibrada 𝑌̂=∑𝑤∗𝑦, 𝑤∗=𝑤·𝑔". |
| Cadena de pesos en dos factores (PPS 1.ª etapa + 2.ª etapa) | 128–129 | OK | p128 "Cadena de pesos en dos factores multiplicativos", πᵤ PPS y π_{i\|u}=mᵤ/Mᵤ; p129 tabla de dos factores. |
| Ajuste IPW 1/P̂(R=1\|X) + calibración gᵢ | 128–129 | OK | p129: "𝑤∗=𝑤·1/𝑃̂(𝑅=1∣𝑋)·𝑔"; IPW (Lohr cap. 8.5), calibración 4 dimensiones. |
| Fórmula varianza HT con πᵢ, πᵢⱼ (Cochran 1999 cap.4.6; Lohr 2021 cap.6.4) | 131 | OK | p131 verbatim, incl. fórmula V̂(Ŷ_HT) con (πᵢⱼ−πᵢπⱼ)/πᵢⱼ. |
| Descomposición bietápica inter/intra UPM; ρ y m̄ | 131 | OK | p131 verbatim. |
| Bootstrap B=500; varianza 12.064.019; +0,02 % | 131 | OK | p131: "𝐵=500 réplicas... 12.064.019 (sesgo relativo +0,02 %)". |
| Jackknife 12.061.565 (corrección Frankel 1971) | 131–132 | OK | Texto inicia p131, varianza y Frankel en p132. |
| Taylor 9.425.553; −21,85 % | 132 | OK | p132 verbatim. |
| Monte Carlo 500 réplicas; 2.938 UPM; PPS 80 UPM; DEFF=1,355 IC[1,20;1,54] | 132 | OK | p132 verbatim (geometría 2.938 UPM, 80 UPM, DEFF y IC). |
| Tabla 3.1.3-1 (Var/EE/CV/sesgo de 4 métodos) | 131–132 | OK | Tabla en p132 (EE 3.473/3.070; CV 28,8/25,5). |
| Factor mín-máx 0,78; equivalencia asintótica; Taylor −21,85 % conservador | 132 | OK | p132 verbatim. |
| Referencias (Cochran 1999, Lohr 2021, Gutiérrez 2016, Kish 1965, Frankel 1971, Pollán 2020) | 140 | OK | p140 "Referencias": Cochran, Frankel 1971, Kish 1965, Lohr 2021, Gutiérrez 2016, Pollán et al. 2020 presentes. |

## item-17
| Cita/afirmación (abreviada) | Pág. citada | Estado | Pág. real / Nota |
|---|---|---|---|
| "800 productores respondientes como cifra de cierre... no de UPM ni de USM seleccionadas" | 133 | OK | p133 verbatim. |
| "mínimo exigido... 783... n=800≥783"; fórmula clásica (Cochran 4.6; Lohr 3.4) | 133 | OK | p133 verbatim. |
| n_MAS≈385; n=385·DEFF 2,0≈769⇒800 (Kish 1965; Lohr 7.4) | 134 | OK | p134 verbatim (385; 769; Kish). |
| DEFF empírico Monte Carlo bietápico = 1,355; IC[1,20;1,54] | 134 | OK | p134 "Vía 1... DEFF empírico de 1,355... [1,20;1,54]". |
| DEFF por ICC ρ=0,0263 ⇒ 1,237 (Cochran 9.4) | 136 | OK | p136 verbatim. |
| e≤4,03 % nacional; supera 7 % DNP en ~42 % | 136 | OK | p136 verbatim. |
| Tabla 3.1.4-4 sensibilidad DEFF∈{1,2;1,5;1,8;2,0;2,5} | 137 | OK | p137 Tabla 3.1.4-4 verbatim (Nacional 800: 3,80 %…5,48 %). |
| Bibliografía (Cochran, Lohr, Kish, Gutiérrez, Pollán, Shao y Tu, Frankel) | (sección) | PÁGINA INCORRECTA | Shao y Tu (2012) NO aparece en Referencias p140 ni en pp.133–137; el resto sí (p140). Cita citada en el texto del ítem sin página específica; "Shao y Tu" no localizado en extracción SPEA. |

## item-18
| Cita/afirmación (abreviada) | Pág. citada | Estado | Pág. real / Nota |
|---|---|---|---|
| "tres estrategias complementarias; su combinación final se calibrará..." | 138 | OK | p138 verbatim (incl. duplicación OCR "incorporar incorpora"). |
| Estrategia (c) propensión; 𝑤_adj=𝑤ᵢ/𝑃̂(𝑅=1∣𝑋ᵢ); 𝑤*=𝑤ᵢ·ajuste_NR·ajuste_cal | 138 | OK | p138 verbatim. |
| Simulación 2.400 corridas (200×3×4); 72,34 % dosis-respuesta; 36,20 % postestrat.; 0 % IPW | 139 | OK | p139 verbatim ("2.400 corridas, 200 por escenario × 3 × 4 vías"; %). |
| MCAR/MAR recuperan β=0,5 (sesgo ~10⁻⁴); NMAR sin ajuste e IPW −0,052 | 139 | OK | p139 verbatim. |
| Tasa no respuesta 15 % (Cochran 13.2; Lohr 8.4); factor 0,85 | 138 | OK | p138 verbatim. |
| Bibliografía (Cochran 13.2; Lohr 6.5/8.4/8.5/4.4; Gutiérrez 10.5.1); Referencias p140 | 140 | OK | Citas de capítulo en pp.138–139; "Referencias" en p140 con Cochran, Lohr, Gutiérrez, Kish, Neyman, Frankel, CEPAL 2009/2023, DANE, ONU 2008. |

## item-19
| Cita/afirmación (abreviada) | Pág. citada | Estado | Pág. real / Nota |
|---|---|---|---|
| "criterios de pertinencia analítica, diversidad territorial y heterogeneidad poblacional" | 143 | OK | p143 verbatim. |
| "diversidad regional y territorial... municipios PDET y no PDET" | 143 | OK | p143 verbatim. |
| "criterios diferenciales y poblacionales... mujeres rurales, jóvenes rurales, población étnica" | 143 | OK | p143 verbatim. |
| "selección de la muestra se ajustará bajo criterios de saturación teórica y suficiencia analítica" | 144 | OK | p144 verbatim. |
| "criterios de máxima variación... experiencias diferenciadas frente al SPEA" | 141 | OK | p141 verbatim (Sección 3.2.1, estudios de caso). |
| Referencias (Banco Mundial 2017, CEPAL 2020, Chen 2005, Denzin 1978, FAO 2014, Flick 2018, Funnell & Rogers 2011, Maxwell 2012, Mayne 2012, OCDE 2017/2018) | 144 | OK | p144 "Referencias": todas presentes. |

## item-20
| Cita/afirmación (abreviada) | Pág. citada | Estado | Pág. real / Nota |
|---|---|---|---|
| "Recodificación de la variable de discapacidad... siete etiquetas heterogéneas..." | 123 | OK | p123 verbatim. |
| "discapacidad como dominio adicional de reporte y como cuarta dimensión de calibración" | 124 | OK | p124 verbatim. |
| "DEFF derivado por ICC sobre la variable de discapacidad (1,237)" | 134 | OK | p134 verbatim ("...y por encima del DEFF derivado por ICC sobre la variable de discapacidad (1,237)"). |
| Discapacidad como categoría poblacional objeto del estudio (no personal vinculado) | 6 | OK | p006: "personas con discapacidad" entre poblaciones históricamente excluidas. (Archivo real: p006.txt). |
| SPEA NO aporta certificación de vinculación de PcD / MinTrabajo (base del "No Cumple") | — | OK | Verificado: ninguna pág. SPEA menciona "Ministerio de Trabajo"/"MinTrabajo"; ninguna co-ubica "certificad*"+"discapacid*". Concesión fundada. |
| Obs. DNP "No Cumple... vinculación mínima de trabajadores con discapacidad" (eval) | eval 191–192 | OK | eval p192 verbatim; tabla "No Cumple" en eval p191. |

## Notas de método
- Las fórmulas matemáticas aparecen degradadas por la extracción del PDF (subíndices/superíndices desplazados), pero los términos, cifras y estructura coinciden; se consideran OK conforme a la tolerancia indicada.
- Cifras numéricas críticas confirmadas exactas: DEFF 1,355 e IC[1,20;1,54] (pp.131–132 y 134); n=800≥783 y n_MAS≈385 (pp.133–134); DEFF ICC 1,237 (p136); varianzas 12.064.019 / 12.061.565 / 9.425.553 (pp.131–132); 2.400 corridas y 72,34 %/36,20 %/0 % (p139); e≤4,03 % (p136).
