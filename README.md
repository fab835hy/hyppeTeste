![](https://www.hyppe.com.br/assets/logo_rosa-069a89d9733bc3643c73a66351e6bb2e8a3483d5a16f54e536f51ea1d65952e2.png)

# Teste hyppe
- Criar uma **API** de agenda para cadastrar eventos.
- Preferência em **Rails**, mas pode usar framework de melhor domínio.
- DB no **MySQL** ou **PostgreSQL**.
- Incluir documentação com instrução de uso. 
- Pode usar **Docker** para facilitar o teste.
- Todo retorno deve ser em **JSON**.
- Deve conter os seguintes métodos:
1. **Cadastro** e **Login** com _email_ e _senha_:
    - Deve retornar **token** da sessão.
2. **Criar, Editar, Ler e Apagar** os eventos:
    - Deve conter _nome, data, hora, local, participantes e confirmação de participantes_.
    - **_Apenas usuários logados podem executar essas funções._**
    - Deve retornar as informações do evento.
3. Listar todos os eventos do usuário logado:
    - Devem estar **agrupados por data**.
4. Deve **confirmar ou não presença** no evento:
5. Extras opcionais:
    - Integrar com API do google calendar.
    - Integrar API em alguma interface visual (Pode ser app ou web).
