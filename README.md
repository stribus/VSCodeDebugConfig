# VSCodeDebugConfig

Este repositório contém configurações de depuração para o Visual Studio Code (VSCode), organizadas para diferentes tecnologias, como Angular e PHP com Xdebug.

## Estrutura do Repositório


```
VSCodeDebugConfig/
    ├── README.md
    ├── Angular/
    │      └── .vscode/
    │             └── launch.json
    ├── PHP/
    │    └── xdebug2.x/ 
    │          ├── .vscode/
    │          └── launch.json
```


## Configurações Disponíveis

### Angular

O arquivo [Angular/.vscode/launch.json](Angular/.vscode/launch.json) contém configurações para:

1. **Executar o comando `npm start`**:
   - Tipo: `node-terminal`
   - Nome: `Run npm start`

2. **Iniciar o Chrome apontando para o `localhost`**:
   - Tipo: `chrome`
   - Nome: `Iniciar o Chrome em relação a localhost`
   - URL: `http://localhost:4210`

### PHP com Xdebug 2

O arquivo [PHP/xdebug2.x/.vscode/launch.json](PHP/xdebug2.x/.vscode/launch.json) contém configurações para:

1. **Escutar conexões do Xdebug 2 (Legacy)**:
   - Tipo: `php`
   - Nome: `Listen for Xdebug 2 (Legacy)`
   - Porta: `9003`

## Como Usar

1. Copie os arquivos de configuração para o diretório `.vscode` do seu projeto.
2. Certifique-se de que as dependências necessárias (como o Xdebug para PHP ou o Chrome para Angular) estejam instaladas e configuradas corretamente.
3. Abra o Visual Studio Code e selecione a configuração desejada no menu de depuração.

## Referências

- [Documentação do VSCode sobre depuração](https://code.visualstudio.com/docs/editor/debugging)
- [Configuração do Xdebug](https://xdebug.org/docs/install)
- [Angular CLI](https://angular.io/cli)
