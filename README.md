# 🏆 Simulador da Copa do Mundo - LAB 6

![FIFA World Cup](https://upload.wikimedia.org/wikipedia/en/thumb/b/bf/FIFA_World_Cup_Trophy.svg/800px-FIFA_World_Cup_Trophy.svg.png)

## 🌍 Sobre o Projeto

Este projeto simula um torneio da Copa do Mundo FIFA utilizando Python. O objetivo é calcular a probabilidade de cada equipe vencer com base nas classificações da FIFA.

## ⚽ Como Funciona?

O programa utiliza classificações da FIFA para estimar a probabilidade de um time vencer uma partida. Com essas informações, ele simula um torneio completo, repetindo o processo um número definido de vezes (por padrão, 1000 simulações) para calcular as chances de cada equipe sair campeã.

## 📝 Requisitos

- Python 3
- Biblioteca CSV (já inclusa no Python padrão)

## ⚙️ Como Executar

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/repo-copa-mundo.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd repo-copa-mundo
   ```
3. Execute o programa com o arquivo de times desejado:
   ```sh
   python tournament.py 2018m.csv
   ```

## ✨ Exemplo de Saída

```sh
$ python tournament.py 2018m.csv
Belgium: 20.9% chance of winning
Brazil: 20.3% chance of winning
Portugal: 14.5% chance of winning
...
```

## 🌍 Estrutura do Projeto

- `tournament.py` - Código principal da simulação.
- `2018m.csv` - Dados da Copa do Mundo Masculina de 2018.
- `2019w.csv` - Dados da Copa do Mundo Feminina de 2019.

## 🛠 Testando seu Código

Para verificar a precisão e o estilo do seu código, utilize:
```sh
check50 cs50/labs/2021/x/copa_mundial
style50 tournament.py
```

## 🌟 Contribuição

Fique à vontade para abrir issues e enviar pull requests!

## ✨ Licença

Este projeto é de uso livre para fins educacionais. 🌐

