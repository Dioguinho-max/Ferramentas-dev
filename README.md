# Ferramentas Dev

Este repositório contém um conjunto de ferramentas úteis para o dia a dia de desenvolvedores. As ferramentas são simples, práticas e visam otimizar várias tarefas comuns.

## Ferramentas Disponíveis

1. **Gerador de Senhas Seguras**  
   Gera senhas fortes e aleatórias.

2. **Conversor de JSON ↔ CSV**  
   Converte arquivos JSON para CSV e vice-versa.

3. **Temporizador Pomodoro**  
   Um timer simples para usar a técnica Pomodoro de produtividade.

4. **Formatador Automático de Código**  
   Usa o [Black](https://black.readthedocs.io/en/stable/) para formatar automaticamente seu código Python.

5. **Buscador de Arquivos por Extensão**  
   Encontra arquivos por extensão dentro de um diretório.

6. **Verificador de Links Quebrados**  
   Verifica links quebrados em uma página web.

7. **Cheatsheets de Git e Linux**  
   Resumos rápidos de comandos essenciais.

---

## Como Usar

### Passo 1: Clonar o repositório

```bash
git clone https://github.com/seu-usuario/ferramentas-dev.git
cd ferramentas-dev
```

### Passo 2: Instalar Dependências

Algumas ferramentas podem precisar de bibliotecas externas, como o `requests` ou o `beautifulsoup4`.

```bash
pip install -r requirements.txt
```

### Passo 3: Executar as Ferramentas

Você pode rodar qualquer uma das ferramentas assim:

```bash
python utils/password_generator.py
python utils/json_csv_converter.py
python utils/pomodoro_timer.py
python utils/code_formatter.py
python utils/file_finder.py
python utils/link_checker.py
```

Ou então rodar diretamente um comando no código para um dos scripts.

## Contribuindo

Se você tem alguma ferramenta ou melhoria para sugerir, fique à vontade para abrir um **pull request** ou criar uma **issue**.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
