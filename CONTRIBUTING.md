### Guia de Contribuição - Networking Data Engineering
Para manter este repositório como uma fonte de consulta confiável, seguimos padrões de engenharia. Utilize o checklist abaixo para validar sua contribuição antes de abrir o Pull Request.

#### 1. Organização e Localização
    [ ] O conteúdo foi inserido em uma subpasta dentro de um dos pilares (ex: processamento/etl-elt-spark/).

    [ ] Não foram criadas pastas novas na raiz do projeto.

    [ ] O nome da subpasta é descritivo e utiliza letras minúsculas separadas por hífen.

    [ ] O conteúdo respeita a coerência do tópico (ex: lógica de transformação em Processamento, infra em DataOps).

#### 2. Padrões de Código e Formatação
    [ ] Todo código Python foi formatado com o Black Formatter.

    [ ] Scripts complexos possuem comentários explicando blocos de lógica.

    [ ] Arquivos de configuração ou credenciais (como .env) não foram incluídos.

    [ ] Obrigatório seguir o layout de pasta (arquivos padrões)! 

#### 3. Layout de Envio (Estrutura da Pasta)

    [ ] Possui um README.md explicativo dentro da subpasta.

    [ ] Código fonte está localizado na pasta src/. ou app/.

    [ ] Diagramas, imagens ou PDFs estão na pasta assets/.

    [ ] Se houver lógica de negócio, incluiu testes simples na pasta tests/.

    [ ] Caso tenho variaveis de ambiente ou algo como banco de dados, usar .gitignore

#### 4. Metadados e Identificação
O README.md da subpasta deve começar com o seguinte cabeçalho preenchido:

    [ ] Autor: [Seu Nome/GitHub]

    [ ] Contexto: [Ex: Estudo para certificação X, Solução de problema real]

    [ ] Data: [DD/MM/AAAA]

#### 5. Fluxo de Revisão (Peer Review)

    [ ] Criei uma branch seguindo o padrão feature/nome-do-tema.

    [ ] O Pull Request foi aberto contra a branch main.

    [ ] Enviei o link no Grupo do WhatsApp para solicitar a revisão de 1 ou 2 outros membros. (Bom para criar uma rotina de aviso de coisa nova)
