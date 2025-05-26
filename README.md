# 📂 Script em Lote para Listar Arquivos no Diretório Atual

Este é um exemplo simples de script em lote (batch script) para Windows que lista os arquivos do diretório atual e pausa a execução, permitindo ao usuário visualizar a saída antes de fechar a janela.

## 🛠️ Instruções de Uso

1. Faça o download do arquivo `ListarArquivos.bat`.
2. Dê dois cliques no arquivo ou execute-o através do Prompt de Comando.
3. O script exibirá uma lista com todos os arquivos e pastas no diretório onde o script está localizado.
4. A execução será pausada automaticamente para que você possa ler a lista com calma.
5. Pressione qualquer tecla para fechar a janela.

## 📄 Exemplo de Código

@echo off  
echo Listando arquivos no diretório atual...  
dir  
pause

## 💡 Observações

- O script é executado no diretório onde estiver salvo.  
- Pode ser usado como base para scripts mais avançados com filtros (`dir *.txt`, `dir /b`, etc.).  
- Ideal para iniciantes que estão aprendendo automação no Windows com `.bat`.

## 📜 Licença

Este projeto está licenciado sob os termos da [MIT License](LICENSE).
