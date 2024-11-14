# Dependências do Computador
  - Node.js (v20.18.0 LTS)
    - npm (v10.9.0 ou superior)

# Modo de Uso

  Endpoints

  # Login (method POST)

    http://localhost:3031/login

  Input (exemplo)
  
    {
      "register": 1,
      "password": "12345678"
    }

  Outputs
    - {message: "Já há um usuário autenticado!"}
    - {message: "Usuário não encontrado"}
    - {message: "Senha inexistente"}
    - {message: "Senha incorreta"}

  # Is Authenticated (method GET)
  
      http://localhost:3031/is-authenticated
      
  Outputs
    - {message: "Usuário autenticado"}
    - {message: "Nenhum usuário autenticado."}



  #Logout
    
    http://localhost:3031/logout

  Outputs
    - {message: "Logout efetuado com sucesso!"}
    - {message: "Nenhum usuário autenticado para efetuar logout."}
