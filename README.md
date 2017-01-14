# Arquivos de linguagem do Laravel 5 - Português do Brasil

## Instalação

1. Clonar este projeto para a pasta `resources/lang/`

  ```
  $ cd resources/lang/
  $ git clone https://github.com/becker/laravel-pt-br-localization.git ./pt-br
  ```

  Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -rf pt-br/.git/
  ```

2. Configurar o Framework para utilizar a linguagem pt-br como Default

  ```
  // Linha 68 do arquivo config/app.php
  'locale' => 'pt-br',
  ```
