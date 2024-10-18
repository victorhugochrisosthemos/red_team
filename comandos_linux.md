# Principais Comandos Linux
## Navegação no Sistema de Arquivos
- cd <diretório>: Muda para o diretório especificado
- mkdir <nome_do_diretório>: Cria um novo diretório
- rmdir <nome_do_diretório>: Remove um diretório vazio
- pwd: Mostra o diretório atual
- ls: Lista arquivos e diretórios
- ls -l: Exibe detalhes dos arquivos e diretórios
- ls -a: Exibe arquivos ocultos
## Manipulação de Arquivos
- touch <nome_do_arquivo>: Cria um arquivo vazio
- cp <origem> <destino>: Copia arquivos ou diretórios
- mv <origem> <destino>: Move ou renomeia arquivos ou diretórios
- rm <arquivo>: Remove arquivos
    - rm -r <diretório>: Remove diretórios e seu conteúdo
## Informações do Sistema
- df: Exibe o uso do disco
    - df -h: Exibe o uso do disco de forma legível (human-readable)
- du: Mostra o uso de espaço em disco por arquivos e diretórios
    - du -h <diretório>: Exibe de forma legível
- top: Monitora os processos em tempo real
- uname -a: Exibe informações sobre o sistema operacional
- free -h: Mostra o uso de memória
## Permissões de Arquivo
- chmod <permissões> <arquivo>: Altera as permissões de um arquivo ou diretório
        - Ex: chmod 755 <arquivo> para dar permissões de leitura, gravação e execução ao proprietário, e somente leitura e execução aos outros
- chown <usuário>:<grupo> <arquivo>: Altera o proprietário de um arquivo ou diretório
## Pesquisa e Filtros
- find <caminho> -name <nome_do_arquivo>: Encontra arquivos por nome.
- grep <padrão> <arquivo>: Procura por um padrão dentro de um arquivo.
- cat <arquivo>: Exibe o conteúdo de um arquivo.
- less <arquivo>: Exibe o conteúdo de um arquivo, uma página por vez.
- head <arquivo>: Mostra as primeiras linhas de um arquivo.
- tail <arquivo>: Mostra as últimas linhas de um arquivo.
## Gestão de Processos
- ps: Exibe processos em execução.
- kill <PID>: Encerra um processo pelo seu ID.
- killall <nome_do_processo>: Encerra todos os processos com o nome especificado.
## Rede
- ping <host>: Verifica a conectividade com um host.
- ifconfig: Exibe configurações da interface de rede.
- netstat: Mostra conexões de rede, roteamento, interfaces.
## Compressão e Arquivamento
- tar -cvf <arquivo.tar> <arquivos/diretórios>: Cria um arquivo tar.
- tar -xvf <arquivo.tar>: Extrai um arquivo tar.
- gzip <arquivo>: Comprime um arquivo.
- gunzip <arquivo.gz>: Descomprime um arquivo gzip.
