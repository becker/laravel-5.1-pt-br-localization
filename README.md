# Arquivos de linguagem do Laravel 5 - Português do Brasil

## Instalação

1. Clonar este projeto para a pasta `resources/lang/`:

  ```console
$ cd resources/lang/
$ git clone https://github.com/becker/laravel-pt-br-localization.git pt-BR
  ```

2. Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório:

  ```console
  $ cd pt-BR
  $ rm -rf .git/ README.md
  ```

3. Configurar o Laravel para utilizar a linguagem pt-BR como padrão:

  ```console
  # Arquivo config/app.php
  'locale' => 'pt-BR',
  ```
