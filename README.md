# Vim Dot Config

## Instalação

Para que tudo ocorra como esperado, execute o arquivo [rmvim.sh](rmvim.sh) ele irá remover o diretório _.vim_ e o arquivo _.vimrc_, mas antes certifique-se de que a permissão de execução foi garantida para esse arquivo.

```bash
# Permite que o arquivo possa ser executado.
chmod +x rmvim.sh
```

Agora que tudo está limpo, vamos prosseguir para o próximo passo. Baixar o pacote *GNU Stow*
```bash
# Ubuntu/Fedora respectivamente
sudo apt install stow
sudo dnf install stow
```

Agora o ponto final, acesse o diretório que o repositório se encontra e execute o comando abaixo para concluir a instalação:
```bash
stow -t ~ vim
```

#### Metas 🤠
- [x] Adicionar script bash para remover arquivos vim.
- [x] Usar o stow como método de instalação.
- [x] Sinconizar minhas configuraçoes em vários SO.