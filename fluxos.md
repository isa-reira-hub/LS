# Fluxo da pessoa usuária (Versão Mobile)

## Etapas de como acontece o cadastro do usuário completamente

| ID                |            01                   |                    
| ----------------  |:-------------:               |
| Nome do CT        | Cadastro                     | 
| Prioridade        | alta                         | 
| Pré-condições     | Estar na tela de cadastro    |
| Dados de entrada | 1. Nome civil ou social <br> 2. Sobrenome <br> 3. E-mail <br> 4. Senha <br> 5. Confirme sua senha <br> A senha deve conter, no mínimo: <br> *8 caracteres<br>Letra maiúscula e Letra minúscula <br> Número <br> Caractere especial(ex: #!*-_&) <br> *As senhas devem ser iguais* |
| Resultado Esperado| <video src="https://github-production-user-asset-6210df.s3.amazonaws.com/158104466/348387241-022108da-b2fa-4589-8ba3-f10e5a780b59.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240712T202207Z&X-Amz-Expires=300&X-Amz-Signature=077c8a8a0dd7d2c562c3654d444b3a4b03d000f68ff57f107904266d8f79f45e&X-Amz-SignedHeaders=host&actor_id=158104466&key_id=0&repo_id=827945136"> |                            
| Resultado atual   | Resultado esperado             |
| Observação        | Nenhuma                       |

---

| ID                |            02                   |                    
| ----------------  |:-------------:               |
| Nome do CT        | Pós Cadastro                    | 
| Prioridade        | alta                         | 
| Pré-condições     | Estar na tela de Pós Cadastro    |
| Dados de entrada | 1. Verificar o email <br> 2. Fazer a verificação <br> 3. Fazer o login <br> 4. Continuar cadastro |
| Resultado Esperado| <video src="https://github-production-user-asset-6210df.s3.amazonaws.com/158104466/348391810-24f6674c-1dcd-4d9c-81c2-633070efdabc.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240712T204648Z&X-Amz-Expires=300&X-Amz-Signature=805228063108b407aced68e7c22488f700f9db12952ba1f3be0b41f69cf13e11&X-Amz-SignedHeaders=host&actor_id=158104466&key_id=0&repo_id=827945136">                          |
| Resultado atual   | Resultado esperado             |
| Observação        | Nenhuma                       |



---


| ID                |            03                   |                    
| ----------------  |:-------------:               |
| Nome do CT        | Buscar Profissional.                     | 
| Prioridade        | Alta                       | 
| Pré-condições     | Ter concluído o cadastro e estar logada em sua conta   |
| Dados de entrada | 1. Faça busca pelos especialistas de sua preferência |
| Resultado Esperado| <video src="https://github-production-user-asset-6210df.s3.amazonaws.com/158104466/348395130-c6816a87-3115-4926-a12b-eeefcdc408bf.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240712T210301Z&X-Amz-Expires=300&X-Amz-Signature=bee69bae0fddfab08a9675aa06303db1501411127d5ed07f75d9914867d305fc&X-Amz-SignedHeaders=host&actor_id=158104466&key_id=0&repo_id=827945136"> |                            
| Resultado atual   | Resultado esperado             |
| Observação        | Nenhuma                       |



---


| ID                |            04                   |                    
| ----------------  |:-------------:               |
| Nome do CT        | Contatar Profissional.                    | 
| Prioridade        | alta                         | 
| Pré-condições     | Precisa estar logado com sua conta e na tela de busca   |
| Dados de entrada | 1. Fazer a busca pelo profissional <br> 2. clicar no nome do profissional <br> 3. clique em atendimentos <br> 4. escolha consulta presencial ou tele consulta <br> 5. Clique em "Exibir contato" <br> 6. Forneça seu número de celular <br> 4. clique em enviar código <br> 7. Digite o código enviado por SMS e confirme |
| Resultado Esperado| Houve bug no fim do processo |                            
| Resultado atual   | <video src="https://github-production-user-asset-6210df.s3.amazonaws.com/158104466/348401684-0d11dc87-c058-47ca-94d7-c22bb975239a.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240712T213607Z&X-Amz-Expires=300&X-Amz-Signature=ee16a6f3c5f75a359dfb14b3c4b33acf1326e0e89db1f78b7d14a2dec56c71fa&X-Amz-SignedHeaders=host&actor_id=158104466&key_id=0&repo_id=827945136">           |
| Observação        | Descrições sobre os bugs entrados no processo de contatar um profissional <br> 1. Para o número de celular ser aceito, precisa ser digitado <br> 2. O código chega por SMS, mas não é reconhecido <br> 3. Tentando reenvio do código ele também chega por SMS, mas como antes, ele não é aceito <br> O código não sendo aceito, então não avanço e não tenho como relatar o processo posterior.                      |




---




| ID                |            05                   |                    
| ----------------  |:-------------:               |
| Nome do CT        | Cadastro                     | 
| Prioridade        | alta                         | 
| Pré-condições     | Estar na tela de cadastro    |
| Dados de entrada | 1. Nome civil ou social <br> 2. Sobrenome <br> 3. E-mail <br> 4. Senha <br> 5. Confirme sua senha <br> A senha deve conter, no mínimo: <br> *8 caracteres<br>Letra maiúscula e Letra minúscula <br> Número <br> Caractere especial(ex: #!*-_&) <br> *As senhas devem ser iguais* |
| Resultado Esperado| <video src="https://github-production-user-asset-6210df.s3.amazonaws.com/158104466/348387241-022108da-b2fa-4589-8ba3-f10e5a780b59.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240712T202207Z&X-Amz-Expires=300&X-Amz-Signature=077c8a8a0dd7d2c562c3654d444b3a4b03d000f68ff57f107904266d8f79f45e&X-Amz-SignedHeaders=host&actor_id=158104466&key_id=0&repo_id=827945136"> |                            
| Resultado atual   | Resultado esperado             |
| Observação        | Nenhuma                       |



















