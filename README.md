# Executável em Python

Este repositório oferece um código simples que permite transformar um arquivo Python em um executável. Essa funcionalidade é útil para distribuir suas aplicações de forma mais fácil, sem a necessidade de compartilhar o código-fonte.

## Como Utilizar

1. **Instalação das Dependências:**
   - Certifique-se de ter as ferramentas adequadas instaladas. Você pode utilizar o `pyinstaller` para criar o executável.
   ```bash
   pip install pyinstaller
   ```

2. **Execução do Código:**
   - Execute o script Python fornecido, passando o caminho do arquivo que deseja transformar em executável como argumento.
   ```bash
   pyinstaller --onefile caminho/do/seu/arquivo.py
   ```

3. **Resultado:**
   - O script utilizará o `pyinstaller` para criar um diretório `dist` que conterá o executável da sua aplicação.
## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.


Esperamos que este código torne o processo de criação de executáveis Python mais simples para você. Se precisar de suporte ou tiver dúvidas, sinta-se à vontade para entrar em contato.
