# Teste de seleção para estágio PHP Imobibrasil

## Regras:
- Você tem sete dias corridos a partir do recebimento deste teste. Após o término do prazo, pode enviar o código mesmo que incompleto.
- O sistema deve ser feito na linguagem PHP e com o banco de dados MySQL. 
- Recomendamos para o sistema de arquivos e aplicativos do servidor utilizar o stack LAMP, mas você é livre para utilizar qualquer stack com server ou serverless.
- Para este desafio você deve utilizar PHP sem frameworks como: Laravel, Cake ou CodeIgnite.
- O código deve estar disponível no GitHub ou outra ferramenta de versionamento de sua escolha.
- Você poderá utilizar qualquer biblioteca de frontend JS ou CSS como: Bootstrap, Materialize CSS, Foundation, jQuery UI, Vue.js ou React)

## Diferenciais para análise:
- Código organizado e limpo.
- Uso das PSRs.
- Montar a estrutura do projeto na ferramenta de sua preferência.


## O projeto:
Desenvolver um sistema de gerenciamento de mídias como: imagens, documentos, Arquivos PDF, Word e etc. Essas mídias podem ser anexadas a um determinado imóvel. Por exemplo: um imóvel pode ter um comprovante de locação, uma escritura ou uma foto da planta da casa. 
*Dica: Você pode utilizar o gerenciamento de mídia do wordpress como inspiração.*

### Gerenciamento de Mídias
Abaixo os requisitos da funcionalidade:

- Deve ter a listagem com busca por nome do arquivo, upload de arquivos, edição do nome, um select para anexar o arquivo a um imóvel e por fim a exclusão do arquivo.
- Campos: ID, ID imovel, nome do arquivo, caminho do arquivo,  data de upload.
- Campos obrigatórios: Nome e E-mail.
- Um arquivo de mídia pode estar ligado a um imóvel

### Imóveis
Abaixo os requisitos da funcionalidade:

- Deve ter a listagem com busca, cadastro, edição e exclusão do imóvel.
- Campos: Id, título do imóvel, descrição, preço e data do cadastro.



## Tabelas necessárias:
- imoveis
- midias
