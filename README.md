# Automação de Mensagens para Grupo de WhatsApp Desktop

Este é um projeto de automação de mensagens para grupos do WhatsApp Desktop, desenvolvido utilizando Python e a biblioteca PyAutoGUI.

## Pré-requisitos

- Python 3.x instalado no seu sistema.
- Biblioteca PyAutoGUI instalada. Você pode instalar utilizando o comando:
  ```
  pip install pyautogui
  ```
- Arquivo `grupos.txt` contendo os nomes dos grupos para os quais deseja enviar mensagens.

## Como usar

1. **Preparação da Mensagem:**
   Antes de executar o script, copie a mensagem que deseja enviar para os grupos. Esta mensagem será automaticamente colada e enviada para cada grupo.

2. **Configuração dos Grupos:**
   No arquivo `grupos.txt`, insira os nomes dos grupos para os quais deseja enviar a mensagem. Cada nome deve estar em uma linha separada.

3. **Execução do Script:**
   Execute o script `automacao_whatsapp.py`.

4. **Acompanhamento:**
   Durante a execução, o script automatizará o processo de abrir cada grupo, colar a mensagem e enviar. Você pode acompanhar o progresso no terminal.


## Notas Importantes

- Certifique-se de manter o WhatsApp Desktop aberto e na tela principal enquanto o script estiver em execução.
- Certifique-se que os pontos da tela foram mapeados
