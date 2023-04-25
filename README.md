# SistemaWeb

=> OBJETIVO:
    
    O sistema terá como objetivo permitir que cadastrados acessem a página principal de um sistema web. De acordo com o seu nível de acesso, o usuário poderá ter acesso/visibilidade ou não a funcionalidades (comandos) avançadas do sistema.
         
  
=> DETALHAMENTO DO SISTEMA:  

    O sistema sera construído no padrão MVC, utilizando ASP.NET Core como recurso tecnológico para o desenvolvimento do produto final para o FRONT-END e BACK-END.
    
    Na camada de persistência, o sistema utilizará o banco de dados SQL SERVER (Microsoft). A base de dados será criada utilizando o recurso ORM Entity Framework.


    =====================================
    --> FRONT-END
    =====================================

    Este sistemas terá 2 páginas web: 

        -  Tela 1:
        
                -> Nome: Login
                
        -  Tela 2:
        
                -> Nome: Página Principal            


    =====================================
    --> BACK-END
    =====================================
      
    O sistema possuirá 2 classes: 
        
        -  Classe 1 

                -> Nome: usuario
                -> Atributos: usuario
                              
                              & nome:
                              & 
                
        -  Classe 2

                -> Nome: Nível de Acesso
                -> Atributos: usuarioDeAcesso
                              
                              & nome:
                              & 
                

    =====================================
    --> CAMADA DE PERSISTÊNCIA DE DADOS
    =====================================
      
    O sistema possuirá 2 tabelas no banco de dados: 
        
        -  Tabela 1 

                -> Entidade: Usuários
                -> Nome: usuarios
                
        -  Tabela 2

                -> Entidade: Nível de Acesso
                -> Nome: nivelDeAcesso
        
        
        
        
        
