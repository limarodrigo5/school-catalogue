# School Catalog 🏫

Bem-vindo ao School Catalogue! Este projeto representa um catálogo digital para o Departamento de Educação da Cidade de Nova York. Ele contém informações sobre escolas primárias e secundárias.

## 🚀 Iniciando

Para começar com o School Catalog, siga estas etapas:

1. Clone este repositório: `git clone https://github.com/limarodrigo5/school-catalogue.git`
2. Navegue até o diretório: `cd school-catalogue`
3. Execute o projeto: `node main.js`

## 📋 Pré-requisitos

Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo em [https://nodejs.org/](https://nodejs.org/).

## ⚙️ Funcionalidades

- Este projeto utiliza classes para representar escolas, incluindo escolas primárias e secundárias.
- Cada escola possui informações como nome, nível de ensino e número de alunos.
- As escolas primárias têm uma política de retirada adicional.
- As escolas secundárias podem ter equipes esportivas.

## 📝 Uso

Você pode usar este projeto para criar e gerenciar informações sobre escolas primárias e secundárias da cidade de Nova York.

Exemplo:

```javascript
// Crie uma escola primária
const lorraineHansbury = new PrimarySchool('Lorraine Hansbury', 514, 'Os alunos devem ser retirados por um responsável maior de 13 anos.');

// Imprima informações sobre a escola primária
lorraineHansbury.quickFacts();

// Escolha um professor substituto aleatório
School.pickSubstituteTeacher(['Jamal Crawford', 'Lou Williams', 'J. R. Smith', 'James Harden', 'Jason Terry', 'Manu Ginóbili']);
