# Codificação

Envio de sinais entre amostras

# PCM

$$g_{\delta}(t)=\sum^{+\infty}_{-\infty}m(t)\delta (t-nT_\delta)$$
$$G_{\delta}(t)=\sum M(t-nT_\delta)$$
Isto seria no caso ideal, na realidade diracs são aproximados por rects

# DPCM - Differential Pulse Code Modulation

Os primeiros pulsos são iguais a PCM ,mas depois envia-se a diferença entre a amostra aterior e a nova, chegando assim à nova amostra sem necessitar de enviar a amostra total. Evita interrupcoes

# DM - Delta modulation

O primeiro pulso é enviado normalmnte, amostras após a primeira enviam apenas se a onda sobe, ou desce nos intervalos de quantização (usa se uma frequência muito a cima do dobro da onda original)

Se o sinal estagna ha ==granular noise==
$$\Delta=\frac{dm(t)}{dt}$$



