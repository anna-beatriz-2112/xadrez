# Xadrez em Python ♟️

Jogo de xadrez interativo executado com um servidor local em Python.

## Funcionalidades
- Tabuleiro clássico 8x8 com peças Unicode e estilização moderna.
- Validação visual de movimentos legais para Peão, Torre, Cavalo, Bispo, Dama e Rei.
- Indicador visual de vez (Brancas / Pretas) e destaque para capturas possíveis.
- Área de peças capturadas.
- Efeito sonoro sintético ao mover peças (Web Audio API).
- Servidor web leve utilizando o módulo nativo `http.server`.

## Como Executar Localmente

1. Crie e ative o ambiente virtual (`venv`):
```bash
python -m venv venv
# No Windows (PowerShell):
.\venv\Scripts\Activate.ps1
# Ou no CMD:
.\venv\Scripts\activate.bat
```

2. Instale as dependências (se houver):
```bash
pip install -r requirements.txt
```

3. Inicie o servidor:
```bash
python server.py
```
Abra o navegador em: [http://localhost:8081](http://localhost:8081)
