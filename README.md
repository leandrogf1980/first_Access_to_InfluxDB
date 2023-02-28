# Primeiro Acesso ao InfluxDB e Configuração no Jmeter

1- Acesse o InfluxDB através da URL: http://localhost:8086/ (a porta irá depender do que foi definido na instalação do InfluxDB).

2- Preencha os dados para seguir.

![image](https://user-images.githubusercontent.com/126198206/221857738-19da4add-f579-460f-b071-a843b1ba6298.png)

3- Acesse o menu ***Load Data*** e em seguida ***API Tokens***, clique no botão ***GENERATE API TOKEN*** e em ***Custom API Token***.

![image](https://user-images.githubusercontent.com/126198206/221857817-0d526d72-0f8e-49fa-866d-b1c642f3abc3.png)

4- Localize o Bucket criado no primeiro acesso e marque as opções ***Read*** e ***Write***, depois clique no botão ***Generate*** para gerar o token que deve ser informado na configuração do JMeter e do Grafana, que veremos a seguir.

![image](https://user-images.githubusercontent.com/126198206/221860053-951d7e7b-c1fc-46b0-86f5-da60282ecd6a.png)

5. Token gerado com sucesso.  
Obs.: Esse token só é gerado e exibido apenas uma vez, caso não tenha anotado, precisará repetir o procedimento anterior.

![image](https://user-images.githubusercontent.com/126198206/221860231-bab60703-5d88-474e-b3ad-708663f440d0.png)

## Configuração do InfluxDB no JMeter
