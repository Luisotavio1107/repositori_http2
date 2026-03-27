## <div align="center"> GET:
<img width="1919" height="1079" alt="Captura de tela 2026-03-20 112813" src="https://github.com/user-attachments/assets/2f9797e9-1a61-47c3-84bc-8b8c6ec83baf" />
COMO UNCIONA O GET?:
Função: Pedir dados ao servidor (ver uma página, buscar um produto).

Onde os dados vão: Escritos na própria URL (ex: google.com/search?q=gatinhos).

Segurança: Baixa. Como os dados aparecem na barra de endereços, nunca use GET para senhas.

Cache: O navegador salva a resposta, por isso carregar a mesma página de novo é tão rápido.

Limite: Aceita apenas textos curtos (geralmente até 2.048 caracteres).

## <div align="center"> POST:
<img width="1913" height="1078" alt="Captura de tela 2026-03-20 112628" src="https://github.com/user-attachments/assets/d7098308-d852-401f-af94-c99d4c96bb36" />
COMO FUNCIONA O POST?: 
Função: Enviar dados para serem processados (criar uma conta, postar uma foto, fazer login).

Onde os dados vão: Escondidos no corpo (body) da requisição, e não na URL.

Segurança: Maior que o GET, pois os dados (como sua senha) não aparecem na barra de endereços do navegador.

Capacidade: Não tem limite prático de tamanho (você pode enviar arquivos pesados, vídeos, etc.).

Efeito: Geralmente altera algo no servidor (adiciona uma linha no banco de dados).
