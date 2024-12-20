# Título do projeto

# Projeto de Data Engineering - Gestão de Saúde Pública

Este projeto tem como objetivo implementar um pipeline de dados para a gestão de saúde pública, utilizando dados fictícios sobre pacientes, médicos, diagnósticos, medicamentos, e consultas médicas. O pipeline vai desde a ingestão de dados em um ambiente relacional até a criação de dashboards interativos para visualização dos KPIs.

## Estrutura do Projeto

- **Banco de Dados Relacional**: Estrutura com as tabelas `Pacientes`, `Consultas`, `Médicos`, `Diagnósticos`, `Medicamentos` e `Prescrições`.
- **Pipeline de Dados**: Conduz os dados através das camadas `Landing`, `Bronze`, `Silver` e `Gold` em um Data Lake.
- **Dashboard**: Visualização dos KPIs e métricas com gráficos interativos.

## Tabelas no Banco de Dados

- **Pacientes**: Contém informações sobre os pacientes, como nome, data de nascimento, sexo, etc.
- **Consultas**: Detalhes das consultas médicas realizadas pelos pacientes.
- **Médicos**: Dados dos médicos responsáveis pelas consultas.
- **Diagnósticos**: Informações sobre diagnósticos médicos.
- **Medicamentos**: Medicamentos prescritos durante as consultas.
- **Prescrições**: Detalhes das prescrições realizadas, incluindo quantidade e instruções.

## Tecnologias Utilizadas

- **Banco de Dados Relacional** (MySQL/PostgreSQL)
- **Apache Spark** (para transformação de dados)
- **Metabase / Google Data Studio** (para criação de dashboards)
- **Docker** (para ambientes locais)
- **MkDocs** (para documentação)
- **GitHub Pages** (para hospedagem da documentação)

## Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **[Implantação](#-implanta%C3%A7%C3%A3o)** para saber como implantar o projeto.

## Desenho de Arquitetura

Coloqui uma imagem do seu projeto, como no exemplo abaixo:

![image](https://github.com/jlsilva01/projeto-ed-satc/assets/484662/541de6ab-03fa-49b3-a29f-dec8857360c1)


## Pré-requisitos

De que coisas você precisa para instalar o software e como instalá-lo?

```
Dar exemplos
```

## Instalação

Uma série de exemplos passo-a-passo que informam o que você deve executar para ter um ambiente de desenvolvimento em execução.

Diga como essa etapa será:

```
Dar exemplos
```

E repita:

```
Até finalizar
```

Termine com um exemplo de como obter dados do sistema ou como usá-los para uma pequena demonstração.

## Implantação

Adicione notas adicionais sobre como implantar isso em um sistema ativo

## Ferramentas utilizadas

Mencione as ferramentas que você usou para criar seu projeto

* Ferramenta 1 + link - Breve descrição
* Ferramenta 2 + link - Breve descrição
* Ferramenta 3 + link - Breve descrição

## Colaboração

Por favor, leia o [COLABORACAO](https://gist.github.com/usuario/colaboracao.md) para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

Se desejar publicar suas modificações em um repositório remoto no GitHub, siga estes passos:

1. Crie um novo repositório vazio no GitHub.
2. No terminal, navegue até o diretório raiz do projeto.
3. Execute os seguintes comandos:

```bash
git remote set-url origin https://github.com/seu-usuario/nome-do-novo-repositorio.git
git add .
git commit -m "Adicionar minhas modificações"
git push -u origin master
```

Isso configurará o repositório remoto e enviará suas modificações para lá.

## Versão

Fale sobre a versão e o controle de versões para o projeto. Para as versões disponíveis, observe as [tags neste repositório](https://github.com/suas/tags/do/projeto). 

## Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

* **Aluno 1** - *Trabalho Inicial* - [(https://github.com/linkParaPerfil)](https://github.com/linkParaPerfil)
* **Aluno 2** - *Documentação* - [https://github.com/linkParaPerfil](https://github.com/linkParaPerfil)

Você também pode ver a lista de todos os [colaboradores](https://github.com/usuario/projeto/colaboradores) que participaram deste projeto.

## Licença

Este projeto está sob a licença (sua licença) - veja o arquivo [LICENSE](https://github.com/jlsilva01/projeto-ed-satc/blob/main/LICENSE) para detalhes.

## Referências

Cite aqui todas as referências utilizadas neste projeto, pode ser outros repositórios, livros, artigos de internet etc.


