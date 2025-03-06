# Caça-Níquel em Python

Este projeto implementa um simulador de **Caça-Níquel** em Python. Ele permite que um jogador realize apostas, veja os resultados gerados aleatoriamente e tenha o saldo atualizado conforme os ganhos e perdas.

## 📌 Funcionalidades
- Gerar combinações aleatórias de emojis.
- Simular a exibição de uma rolagem de slot.
- Verificar se o jogador venceu a rodada.
- Atualizar o saldo do jogador e da máquina.

## 🛠 Tecnologias Utilizadas
- Python 3
- Biblioteca `itertools` para gerar combinações
- Biblioteca `random` para gerar resultados aleatórios
- Biblioteca `os` e `time.sleep` para simular a animação

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/ca%C3%A7a-niquel-python.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd caca-niquel-python
   ```
3. Execute o script Python:
   ```bash
   python caça_niquel.py
   ```

## 🏆 Regras do Jogo
1. O jogador aposta um valor (exemplo: 10 R$).
2. A máquina gera uma combinação aleatória de três emojis.
3. Se os três forem iguais, o jogador ganha **3x** o valor apostado.
4. Caso contrário, o jogador perde o valor apostado.

## 📷 Exemplo de Saída no Terminal
```bash
🎰 Rodando...
💰🔥💔
Foi quase, tente novamente.

🎰 Rodando...
👽👽👽
Você venceu e recebeu: 30 R$
```

## 📄 Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

