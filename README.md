# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

- Personalizar a interface do portal Azure;
- Panorama geral sobre os serviços disponíveis;
- Alguns serviços de redes;
- Serviços de storage;
- Informações sobre serviços com versão prévia.

# Componentes de arquitetura do Azure

- Regiões, pares de região e região sobrerana;
- Zonas de disponibilidade e datacenters;
- Recursos e grupos de recursos;
- Assinaturas e grupos de gerenciamento;
- Hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento.

# Computação e rede

- Criar uma nova VM, entendendo modelos com configurações pré-definidas, ou criando uma do zero.
- Entendender o tamanho das VM conforme a estratégia necessária, mais CPU, mais memória, uma escolha mais adequada ajuda a economizar recursos e custos.
- Escala e dimensionamento, pode ser ajustada conforme necessidade de mais recursos, como por exemplo em uma black friday.
- Recursos criados durante o deploy da VM como discos, interfaces de rede, ips não devem ser esquecidos ou deixados orfãos, pois podem gerar cobranças mesmo a VM sendo removida.
- Alertas de monitoramento da VM.
- Area de trabalho remota utilzando um pool de host.
- No uso de funções para aplicativos de funções, as opções de hospedagem podem variar de acordo com a linguagem de programação, pois uma pode ser Windows e outra Linux.

# Armazenamento

Tipos de armazenamentos no Storage do Azure

- Para grandes volumes é recomendado soluções como Data Box Disk, Data Box ou Data Box Heavy onde serão feitas cópias fisicas e enviadas ao data center de escolha. São soluções para grandes empresas pois o custo é elevado.
- Categorias de armazenamento blob, files, queues e tables.  Blob para tipos genéricos de arquivos, files permite todo e qualquer tipo de arquivo e posterior compartilhamento \\, queues pode ser usado como mensagerias e table para criação de tabelas ordenadas.
- Durante a criação de um tipo de armazenamento vale ressaltar o tipo de acesso a essa informação, onde podemos ter acesso frequente, exporádico, frio, ou arquivo morto, isso pode impactar no custo de armazenamento e de acesso a informação. 

# Identidade, Acesso e Segurança

- A família do Microsoft AD (Active Directory) passou a ser chamado agora é Microsoft Entra;
- Métodos de autenticação no Azure, SSO, MGA e sem senha como por exemplo do Hello do Windows utilizando uma webcam;
- Acesso exetrno ed convidados no Azure;
- Acesso condicional do Entra com base dem função (RBAC - Rule Based Access Controll);

