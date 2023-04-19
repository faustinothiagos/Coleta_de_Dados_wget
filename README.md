# Coleta_de_Dados_wget

# Enunciado:

- Wget é uma ferramenta criada pelo GNU Project. Você pode usá-la para recuperar conteúdos e arquivos de vários servidores na internet. O nome vem de uma combinação de World Wide Web e a palavra get. Ela suporta downloads via FTP, SFTP, HTML e HTTPS. Ela foi criado em linguagem C portátil e executável em qualquer sistema Unix. Também é possível implementá-lo no Mac OS X, Microsoft Windows, AmigaOS e outras plataformas populares.

# Como instalar o Wget?

- Para essa demonstração do comando Wget, vamos usar a versão do 22.04 LTS do Ubuntu. Mas a mesma sintaxe funciona para qualquer outra distribuição do Linux. A seguir, execute o seguinte comando para instalá-lo no seu sistema:

- apt-get install wget

- Aqui neste aquivo foi usado dentro do jupyter Notbook mais poderia ser via terminal do linux.

# Exemplos de comandos Wget

- Um dos exemplos de comandos mais básicos é fazer o download de um único arquivo e armazená-lo em seu diretório de trabalho atual. Por exemplo, você pode obter a versão mais recente de um arquivo de CGE AL da folha ativa usando o seguinte código:

-!wget -p https://transparencia.al.gov.br/media/arquivo/folha_ativo-2023.zip

- Aqui mostra o resultado:

---2023-04-04 11:34:26--  https://transparencia.al.gov.br/media/arquivo/folha_ativo-2023.zip
Resolvendo transparencia.al.gov.br (transparencia.al.gov.br)... 186.249.51.25
Conectando-se a transparencia.al.gov.br (transparencia.al.gov.br)|186.249.51.25|:443... conectado.
A requisição HTTP foi enviada, aguardando resposta... 200 OK
Tamanho: 2527166 (2,4M) [application/zip]
Salvando em: ‘transparencia.al.gov.br/media/arquivo/folha_ativo-2023.zip’

transparencia.al.go 100%[===================>]   2,41M  8,62MB/s    em 0,3s    

2023-04-04 11:34:26 (8,62 MB/s) - ‘transparencia.al.gov.br/media/arquivo/folha_ativo-2023.zip’ salvo [2527166/2527166]

FINALIZADO --2023-04-04 11:34:26--
Tempo total decorrido: 0,4s
Baixados: 1 arquivos, 2,4M em 0,3s (8,62 MB/s)

- Neste exemplo, um arquivo nomeado folha_ativa-2023.zip será baixado no seu diretório de trabalho atual. Você também verá informações extras, como o progresso do download, a velocidade, o tamanho, a hora e a data dele. 

- Esse foi um teste de uma vaga de analista de dados da CGE Al no qual participei.

