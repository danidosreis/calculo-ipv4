# calculo-ipv4
Sistema que calcula ipv4 criado acompanhando o curso 'Python 3 do Básico ao Avançado' 

```py
calc_ipv4 = CalcIPv4(ip='192.160.1.1', cidr=23)

print(f'IP: {calc_ipv4.ip}')
print(f'Máscara: {calc_ipv4.mascara}')
print(f'Rede: {calc_ipv4.rede}')
print(f'Broadcast: {calc_ipv4.broadcast}')
print(f'Prefixo: {calc_ipv4.cidr}')
print(f'Número de IPs de rede: {calc_ipv4.numer_ips}')
```
Ou

``` py
calc_ipv4 = CalcIPv4(ip='192.160.1.1', mascara='255.255.254.0')

print(f'IP: {calc_ipv4.ip}')
print(f'Máscara: {calc_ipv4.mascara}')
print(f'Rede: {calc_ipv4.rede}')
print(f'Broadcast: {calc_ipv4.broadcast}')
print(f'Prefixo: {calc_ipv4.cidr}')
print(f'Número de IPs de rede: {calc_ipv4.numer_ips}')
```
Resultado:
```
IP: 192.160.1.1
Máscara: 255.255.254.0
Rede: 192.160.0.0
Broadcast: 192.160.1.255
Prefixo: 23
Número de IPs de rede: 512
