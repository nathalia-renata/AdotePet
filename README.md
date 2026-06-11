# 🐾 Adote Pets

* Site criado para estudo e suas informações são meramente ilustrativas.
  
## Descrição 
> Encontros felizes entre pessoas e animais à espera de um lar.

O Adote Pet é um site institucional e interativo focado em promover a adoção responsável de cães e gatos, além de incentivar a doação de suprimentos (como ração e medicamentos) para ONGs e protetores parceiros. O projeto foi desenvolvido com uma interface amigável, visual moderno e totalmente responsiva para computadores e dispositivos móveis.

---

## 🚀 Funcionalidades e Páginas

O projeto é composto por um ecossistema de páginas interligadas para atender tanto adotantes quanto doadores:

* Página Inicial (index.html): Apresentação do projeto, contagem de história, categorias de animais (Cães, Gatos e Outros) e destaques com dicas de cuidados.
* Quero Adotar (adote.html): Galeria visual com cartões dos animais disponíveis para adoção (como o Luke, a Luna e o Bolinha), exibindo fotos, descrição de temperamento e idade.
* Quero Doar (doe.html): Sessão informativa detalhando quais suprimentos são mais necessários (Medicamentos, Produtos de Higiene, Ração) e o endereço físico para envio.
* Dúvidas Frequentes (duvidas.html): Uma central de ajuda explicando o passo a passo da entrevista de adoção, preenchimento do formulário online e a retirada do pet.
* Dicas de Cuidados (cuidadoscao.html e cuidadosgato.html): Guias completos de saúde, higiene, alimentação e afeto específicos para cães e gatos.
* Autenticação (login.html e cadastro.html): Formulários estruturados para login e um painel completo de cadastro com validação de dados para novos adotantes.

---

## 🎨 Diferenciais do Design & Código

* Responsividade Fluida: O site adapta-se dinamicamente para ecrãs de telemóveis (celulares) e tablets através de regras de @media customizadas, garantindo botões centralizados e caixas adaptáveis.
* Efeitos Dinâmicos: Uso de transições em CSS (:hover com transform: scale) que dão vida e interatividade aos cards de animais e formulários.
* Tipografia Customizada: Integração de fontes exclusivas via @font-face para dar uma identidade visual única e acolhedora ao projeto.

---

## 🛠️ Tecnologias Utilizadas

As seguintes tecnologias foram utilizadas na construção deste ecossistema web:

* HTML5: Estruturação semântica de todas as páginas e formulários.
* CSS3: Estilização moderna, uso de sistemas de posicionamento dinâmico (Flexbox/Grid), centralização matemática e responsividade mobile.
* JavaScript: Interações dinâmicas locais e alertas de validação de ações no sistema.

---

## 📄🖥️ Visualizar Site

Para visualizar as páginas e testar algumas funcionalidades acesse o site abaixo 👇🏻
https://nathalia-renata.github.io/AdotePet/

---

## Diagrama de Casos de Uso

Este diagrama representa as funcionalidades do sistema sob a perspectiva dos utilizadores. Ele define "quem" pode fazer "o quê" no seu site.

* Os Atores:Usuário (Adotante): É o cliente final. Ele interage com a parte pública do site, podendo Registrar-se, Efetuar login e Adotar pet (ações ligadas diretamente às suas telas de cadastro, login e galeria de adoção).
* Colaborador: Geralmente um voluntário ou membro de uma ONG parceira. Ele tem permissões intermediárias, como Atualizar as adoções, Fazer entrevistas para liberar adoção e Gerenciar doações.
* Administrador: É o usuário mestre do sistema. Ele possui controle total e gerencia as regras de negócio, controlando os utilizadores menores (Gerenciar usuários, Gerenciar colaboradores) e supervisionando o fluxo principal (Gerenciar sistema de adoções, Gerenciar doações).

## Diagrama Entidade-Relacionamento Estendido (EER)

Este diagrama representa a modelagem do meu banco de dados relacional, ou seja, como as informações que o usuário digita nos formulários HTML serão armazenadas de forma organizada.
As tabelas principais foram estruturadas:
Tabela cadastro (Dados Pessoais)Esta tabela mapeia exatamente os campos que eu criei tá no formulário do arquivo cadastro.html:
id_usuario INT: A Chave Primária (PK). Um identificador exclusivo e numérico para cada pessoa.nome, email, cpf, celular, datanasc, bairro, rua, cidade, estado: Armazenam os dados cadastrais coletados no formulário.Tabela login (Credenciais de Acesso)Esta tabela gerencia a segurança e a autenticação do utilizador na página login.html:
id_login INT: Chave Primária da tabela de autenticação.email e senha: Dados validados no momento do acesso.cadastro_id_usuario: Esta é a Chave Estrangeira (FK). Ela cria a linha de conexão que liga as duas tabelas.O Relacionamento (Cardinalidade)A linha que conecta as tabelas possui o símbolo de 1 para 1 (1:1) nas extremidades (representado pelos traços perpendiculares ||).
O que significa: Significa que um registro na tabela de cadastro possui exatamente um registro correspondente na tabela de login. Um usuário não pode ter dois logins com o mesmo perfil, e um login não pode pertencer a dois usuários diferentes.

## 👩‍💻 Autora

* Nathália Renata Garcia Oliveira
* Contacto: [nathalia.renata.oli@gmail.com](mailto:nathalia.renata.oli@gmail.com)

---
<p align="center">Feito com ❤️ para ajudar os animais resgatados!</p>
