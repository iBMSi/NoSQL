# NoSQL

Etapa 1
página inicial: www.google.com

Idioma preferido: Português do Brasil

Localização: São Paulo

Tema: Clássico

Mostrar favoritos: Sim

Zoom: 100%

Escreva os dados acima na notação JSON. Para esta atividade utilize o bloco de notas, salve o arquivo com o nome: localização_google_sp.json

------------------------------------------------------------------------

Na notação JSON, NoSQL o arquivo fica simpificado e padronizado deste jeito:

{

  "pagina_inicial": "www.google.com",
  
  "idioma_preferido": "Português do Brasil",
  
  "localizacao": "São Paulo",
  
  "tema": "Clássico",
  
  "mostrar_favoritos": true,
  
  "zoom": "100%"
  
}

ETAPA 2

Nome	|  Endereço	|  E-mails  |	Cargo  |	Jornada  |	Salário  |

João Grilo  |	Rua Suassuna   30   João Pessoa  | PB	grilo@mail.com  | joaog@mk.com  |  Contador  |  40  |  R$ 3.000,00

Ada Byron  |  Rua Lovelace   67   London  |  ada@mail.com  | abyron@tech.com  |  Developer  |  20	R$  |  15.000,00

Gerundino  |  Rua Substantivo   78   Bairro Predicado   Mesóclise-AC  |  gerundino@gmail.com  |  Linguista  |  44  |  R$ 8.000,00

Chicó  |  Rua Eurico   50   João Pessoa   PB   Apt 28   Bloco C  |	Developer  |  20  |  R$ 15.000,00



Crie, conforme o modelo relacional, as tabelas normalizadas. Crie também um documento JSON que contenha esses dados.

Normalização das tabelas:

----------------------

Tabela Funcionário:

Id   (Chave Primaria)

Nome

Endereço

Cargo

Jornada

Salário

Email
----------------------

Com a normalização feita vamos então criar o documento JSON:

{
  "funcionarios": [
  
    {
      "nome": "João Grilo",
      "endereco": "Rua Suassuna, 30, João Pessoa, PB",
      "cargo": "Contador",
      "jornada": 40,
      "salario": "R$ 3.000,00",
      "emails": ["grilo@mail.com", "joaog@mk.com"]
    },
  
    {
      "nome": "Ada Byron",
      "endereco": "Rua Lovelace, 67, London",
      "cargo": "Developer",
      "jornada": 20,
      "salario": "R$ 15.000,00",
      "emails": ["ada@mail.com", "abyron@tech.com"]
    },
    {
      "nome": "Gerundino",
      "endereco": "Rua Substantivo, 78, Bairro Predicado, Mesóclise-AC",
      "cargo": "Linguista",
      "jornada": 44,
      "salario": "R$ 8.000,00",
      "emails": ["Gerundino@gmail.com"]
    },
    {
      "nome": "Chicó",
      "endereco": "Rua Eurico, 50, João Pessoa, PB, Apt 28, Bloco C",
      "cargo": "Developer",
      "jornada": 20,
      "salario": "R$ 15.000,00",
      "emails": []
    }
  ]
}

--------------------------------

ETAPA 3

Essa etapa consistia em pegar o exercicio anterior e faze-lo no firebase, é possiverl ver tal procedimento no arquivo "Empresa X" anexado no arquivo Read.me

Além disso também havia a necessidade de fazer uma outra tabela no firebase com o tema jogos;
Dito isso fiz um projeto chamado "Pokemon Garnet and Galatas", onde há uma tabela chamada Pokemon, com 3 pokemons cadastrados com nome e tipo,
e outra tabela chamada Fabricante com um fabricante cadastrado com nome, presidente, fundação e sede;

esse projeto também está anexado no arquivo Read.me com o nome "Pokemon Garnet and Galatas"

