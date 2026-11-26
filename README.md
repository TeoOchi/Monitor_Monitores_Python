# Monitor_Monitores_Python

Oque esse programa faz: Primeiro de tudo, ele define as variáveis, definindo o nome do sistema, a versão dele, seus limites (Máx e Min). Esse código cria um programa de monitoramento de motores industriais, que aponta em uma tabela os seus status dos motores, se ele está normal, se tenho que ter atenção ou se o motor está em um estado crítico. Essa tabela possui informações como: Temperatura do motor, de que setor ele pertence, quantos motores estão naquele estado, sua corrente, a vibração e até mesmo o RPM. Ele também emite alertas sobre qual o problema exato do motor, ao final desta tabela, é mostrado quantos motores tem, a temperatura média deles, a corrente média, a potência total e qual motor apresenta a maior temperatura.


Tabela de demonstração:
____________________________________________________________________________________________________________________________________
================================================================
Monitoramento de Motores Industriais - v1.0.0
Data/Hora da leitura: 26/11/2026 12:29:15
================================================================
[NORMAL ] MTR-01 (Estamparia) | Temp: 68.4 C | Corr: 14.2 A | Vib: 2.1 mm/s | RPM: 1750
[CRITICO] MTR-02 (Usinagem) | Temp: 84.7 C | Corr: 19.3 A | Vib: 5.2 mm/s | RPM: 1690
  -> Alerta: Superaquecimento (84.7 C)
  -> Alerta: Sobrecorrente (19.3 A)
  -> Alerta: Vibracao elevada (5.2 mm/s)
[ATENCAO] MTR-03 (Bobinagem) | Temp: 76.2 C | Corr: 17.8 A | Vib: 4.7 mm/s | RPM: 1520
  -> Alerta: Vibracao elevada (4.7 mm/s)
[NORMAL ] MTR-04 (Pintura) | Temp: 61.0 C | Corr: 11.5 A | Vib: 1.8 mm/s | RPM: 1780
----------------------------------------------------------------
Resumo: 4 motores | Temp. media: 72.58 C | Corr. media: 15.7 A | Potencia total: 31.5 kW | Maior temp.: MTR-02
================================================================
PS C:\Users\teo_ochi\Documents\GitHub\Monitor_Monitores_Python>
____________________________________________________________________________________________________________________________________
