# missao_espacial.py

# 1. Entrada de dados
nome = input('Digite seu nome completo:')
distancia = float(input('Digite a distancia da viagem (em km): '))
velocidade = float(input('Digite a velocidade média da nave(em km/h):'))

# 2. Cálculos
tempo_horas = distancia / velocidade
tempo_dias = tempo_horas / 24

# 3. Exibição do resultado
print(f'\n Astronauta {nome}, Bem - vindo à simulação!')
print(f'A vigem terá uma distância de {distancia} km.')
print(f'Com a velocidade média de {velocidade} km/h, o tempo estimado é:')
print(f'{tempo_horas:.2f} horas({tempo_dias:.2f} dias).')
print('Boa sorte na missão!')
