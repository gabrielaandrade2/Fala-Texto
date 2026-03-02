- Arquivo .gitignore

  O projeto utiliza o .gitignore para definir quais arquivos e diretórios não devem ser versionados pelo Git. Essa prática é fundamental para manter o repositório organizado, leve e seguro.

  Durante o desenvolvimento Android, diversos arquivos são gerados automaticamente pelo sistema de build (Gradle), pela IDE (Android Studio) e pelo próprio sistema operacional. Esses arquivos:

  - São recriados automaticamente a cada build;

  - Variam de máquina para máquina;

  - Não fazem parte do código-fonte;

  - Podem expor caminhos locais ou configurações específicas do desenvolvedor.

  Versionar esses arquivos poderia gerar conflitos desnecessários entre desenvolvedores, aumentar o tamanho do repositório e comprometer a portabilidade do projeto.
