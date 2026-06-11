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

## 👤 Diagrama de Casos de Uso

<img width="2400" height="1708" alt="1000150012" src="https://github.com/user-attachments/assets/7cbbcd39-b424-45c8-bef0-5faa13ad5e26" />


Este diagrama representa as funcionalidades do sistema sob a perspectiva dos utilizadores. Ele define "quem" pode fazer "o quê" no seu site.

* Os Atores:Usuário (Adotante): É o cliente final. Ele interage com a parte pública do site, podendo Registrar-se, Efetuar login e Adotar pet (ações ligadas diretamente às suas telas de cadastro, login e galeria de adoção).
* Colaborador: Geralmente um voluntário ou membro de uma ONG parceira. Ele tem permissões intermediárias, como Atualizar as adoções, Fazer entrevistas para liberar adoção e Gerenciar doações.
* Administrador: É o usuário mestre do sistema. Ele possui controle total e gerencia as regras de negócio, controlando os utilizadores menores (Gerenciar usuários, Gerenciar colaboradores) e supervisionando o fluxo principal (Gerenciar sistema de adoções, Gerenciar doações).

## ⤵️🎲 Diagrama Entidade-Relacionamento Estendido (EER)

<img width="374" height="378" alt="1000150011" src="https://github.com/user-attachments/assets/0434d91a-b74f-4ed7-9880-9576590ac171" />


Este diagrama representa a modelagem do meu banco de dados relacional, ou seja, como as informações que o usuário digita nos formulários HTML serão armazenadas de forma organizada.
As tabelas principais foram estruturadas:

* Tabela cadastro (Dados Pessoais)Esta tabela mapeia exatamente os campos que eu criei tá no formulário do arquivo cadastro.html:
* id_usuario INT: A Chave Primária (PK). Um identificador exclusivo e numérico para cada pessoa.nome, email, cpf, celular, datanasc, bairro, rua, cidade, estado: Armazenam os dados cadastrais coletados no formulário.
* Tabela login (Credenciais de Acesso)Esta tabela gerencia a segurança e a autenticação do utilizador na página login.html:
* id_login INT: Chave Primária da tabela de autenticação.email e senha: Dados validados no momento do acesso.
* cadastro_id_usuario: Esta é a Chave Estrangeira (FK). Ela cria a linha de conexão que liga as duas tabelas.O Relacionamento (Cardinalidade)A linha que conecta as tabelas possui o símbolo de 1 para 1 (1:1) nas extremidades (representado pelos traços perpendiculares ||).
O que significa: Significa que um registro na tabela de cadastro possui exatamente um registro correspondente na tabela de login. Um usuário não pode ter dois logins com o mesmo perfil, e um login não pode pertencer a dois usuários diferentes.

## ✍🏻 Prototipagem do Projeto 

<img width="2160" height="3840" alt="1000150033" src="https://github.com/user-attachments/assets/34a786a7-e0a7-4f3e-91f2-0bf0045e900b" />


<img width="2160" height="3840" alt="1000150032" src="https://github.com/user-attachments/assets/a63f51c4-bf67-4654-81ad-703e75893d52" />

<img width="2592" height="4608" alt="1000150031" src="https://github.com/user-attachments/assets/80c8251c-041d-4820-b838-76bddfa74868" />


A prototipagem foi desenvolvida no Canva, apresentando uma interface limpa, intuitiva e totalmente focada na experiência do utilizador (UX/UI). Com uma paleta de cores suave baseada em tons de azul-claro e turquesa, o design transmite a tranquilidade, a transparência e a empatia necessárias para uma plataforma de adoção responsável.
As telas principais do protótipo demonstram um fluxo de navegação fluido e bem estruturado:
* Página Inicial (Landing Page): Destaca-se por um banner centralizado e acolhedor, menus de navegação claros (Dúvidas, Quero adotar, Quero doar) e botões de chamada para ação (CTA) como o Login em vermelho, garantindo alto contraste visual.
* Seções de Categorias e Dicas: Utiliza ícones minimalistas e cards responsivos com imagens ilustrativas para segmentar as opções de adoção e guias de cuidados, tornando o conteúdo altamente escaneável.
* Tela de Autenticação (Login): Apresenta um formulário centralizado em um card com cantos arredondados, priorizando campos legíveis, espaçamento confortável e um redirecionamento simples para novos cadastros.

Este protótipo serviu como base visual essencial para validar a arquitetura de informação do site antes da sua implementação em código, garantindo que o design final se mantivesse fiel à identidade visual da marca tanto em computadores quanto em dispositivos móveis.

## 👩‍💻 Autora

* Nathália Renata Garcia Oliveira
* Contacto: [nathalia.renata.oli@gmail.com](mailto:nathalia.renata.oli@gmail.com)

---
<p align="center">Feito com ❤️ para ajudar os animais resgatados!</p>
