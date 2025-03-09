# Projeto Integrador - Cadastro no sistema de uma faculdade 🖥️✏️
<p>
  Olá! Este projeto foi desenvolvido em duas partes principais para criar um sistema de cadastro de uma faculdade. 
  
  Na primeira parte, focamos na elaboração de um diagrama de uso e um diagrama de classes, estabelecendo a estrutura e funcionalidades do sistema. Na segunda parte, desenvolvemos protótipos funcionais e criamos três exemplos de cadastros: alunos, professores e fornecedores, demonstrando a aplicação prática do sistema.
</p>

# Descrição - Diagramas
  Abaixo, mostrarei o passo a passo do que foi feito:
  <li><strong>Diagrama de uso</strong></li><br>

![diagrama-caso_de_uso](https://github.com/user-attachments/assets/af2595ea-140c-48fb-a153-ae17aa2160d7)
<p>
  O diagrama de uso acima tem como objetivo permitir que uma pessoa faça o cadastro de outras pessoas (físicas e jurídicas), alunos, professores e fornecedores no sistema de uma grande universidade para que estes possam acessar os serviços oferecidos pela instituição.
</p>
<li><strong>Diagrama de classe</strong></li><br>

![diagrama_de_classe](https://github.com/user-attachments/assets/2ad9e20b-596d-45e9-a00c-8e5db587f9bf)
<p>
  Já no diagrama de classes, montamos o relacionamento que cada usuário terá com o sistema:
    <li>
      Herança:
      
  - Pessoa é a superclasse de Pessoa além de ser a classe base para Aluno , Professor e Fornecedor.
  - Isso permite o reaproveitamento de código e facilita a manutenção, já que as funcionalidades comuns são centralizadas na classe Pessoa.
  </li>

  <li>
    Interface:
    
  - A interface ValidacaoCadastro garante que todas as classes responsáveis pelo cadastro (como Pessoa) implementem o método de validação, o que melhora a consistência e modularidade do sistema.
  </li>

  <li>
    Associação:
    
  - Relacionamentos como "um-para-muitos" entre Professor e Disciplina, ou "muitos-para-muitos" entre Aluno e Disciplina, são fundamentais para modelar as interações do sistema.
  - Utilizar associações entre Fornecedor e Compra permite que o sistema registre os produtos fornecidos e o histórico de compras.
  </li>
</p>

# Descrição - Protótipos
<p>
  Como mencionado anteriormente, fizemos três exemplos de protótipos do sistema. Utilizamos o "Miro" para fazer essa etapa.

  <li>
  <strong>Tela de Login - Mobile</strong>
    
<br><ul>Visão do Aluno
    
![mobile-aluno](https://github.com/user-attachments/assets/b9210219-a6cf-4b34-8718-fecafa64d6ca)

<p>
  As setas laranjas indicam o caminho que um aluno já com um perfil cadastrado consegue fazer. E as setas pretas indicam o caminho que um aluno ainda sem acesso ao sistema deve fazer para se cadastrar e acessar as funcionalidades oferecidas pelo app.

  Neste exemplo, criamos a tela de "Notas" como demonstração de uma das opções que o aluno pode acessar. Nela, o usuário escolhe o semestre que deseja e verificar as notas obtidas naquele período e nas disciplinas específicas.
</p>
</ul>

<br><ul>Visão do Professor

![mobile-professor](https://github.com/user-attachments/assets/4a3a6f80-20f1-4f78-a4c8-ad7fa80e7224)

<p>
  Assim como na tela dos alunos, as setas laranjas indicam o caminho que um professor já com um perfil cadastrado consegue fazer. E as setas pretas indicam o caminho que um professor ainda sem acesso ao sistema deve fazer para se cadastrar e acessar as funcionalidades oferecidas pelo app.

  Neste exemplo, criamos a tela de "Turmas" como demonstração de uma das opções que o professor pode acessar. Nela, o usuário escolhe o semestre, a turma e o período desejados e verificar as turmas para realizar o lançamento de presenças e faltas, por exemplo.
</p>
</ul>

<br><ul>Visão do Fornecedor

![mobile-fornecedor](https://github.com/user-attachments/assets/f7e6d837-d522-4723-8187-39c599a6ed29)

<p>
  Assim como nas telas anteiores, as setas laranjas indicam o caminho que um fornecedor já com um perfil cadastrado consegue fazer. E as setas pretas indicam o caminho que um fornecedor ainda sem acesso ao sistema deve fazer para se cadastrar e acessar as funcionalidades oferecidas pelo app.

  Neste exemplo, criamos a tela de "Produtos e Serviços" como demonstração de uma das opções que o fornecedor pode acessar. Nela, o usuário escolhe o se deseja cadastrar um novo produto ou serviço e consultar os que já existem.
</p>
</ul>
  </li>
</p>

<li>
  <strong>Tela de Login - WEB</strong>
  <p>
    As telas na versão WEB seguem o mesmo caminho da versão mobile, o que difere é a disposição dos elementos nas telas.
  </p>
  
  <br><ul>Visão do Aluno

![web-aluno](https://github.com/user-attachments/assets/bf3938aa-6b5e-4fb6-a1e0-f5759614f676)

  </ul>

  <br><ul>Visão do Professor

![web-professor](https://github.com/user-attachments/assets/b15bd264-a8ae-4d70-8179-a5e1fa06504a)

  </ul>

  <br><ul>Visão do Fornecedor

![web-fornecedor](https://github.com/user-attachments/assets/bd07026f-824d-4f1b-ab06-882e56f7888a)

  </ul>
</li>

<p>
  <strong>Observação:</strong> quando o usuário vai se cadastrar pela primeira vez, é preciso ter um e-mail, disponibilizar CPF e data de nascimento para alunos e professores e CNPJ e Razão Social para fornecedores.
</p>



# Disposições Finais
<p>
  Posteriormente, nas próximas etapas, acreditamos desenvolver o código desta aplicação e utilizar banco de dados, front-end e back-end para ligar todas as funcionalidades e criar um sistema fiel e utilizável ao que montamos nessas duas etapas.
</p>
