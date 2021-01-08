# nike-bot

Compra um tênis SNKRS na Nike Brasil.

## 🚀 Como usar

**Requerimentos:**

- NodeJS

Instalar as dependências:

```sh
npm install
```

Compilar o programa:

```sh
npm run build
```

Iniciar o programa:

```sh
npm start
```

## 📜 Documentação

Certifique-se de ajustar as configurações de acordo com suas necessidades no arquivo de configuração ".env" (caso não exista, inicie o bot para ele ser criado).

Para utilizar o bot a conta deve ter, no mínimo, um endereço e cartão salvos.

### Estrutura do arquivo de configuração

```text
# o email usado para entrar na sua conta
EMAIL="nome.sobrenome@gmail.com"
# a senha usada para entrar na sua conta
PASSWORD="s3nh4"
# o número de celular que receberá o código SMS, caso necessário
PHONE=00911223344
# os 4 últimos números do cartão salvo
CARD_LAST_DIGITS=1234

# link da página do tênis
SHOE_URL="link"
# tamanhos preferíveis, deixe vazio para selecionar o primeiro tamanho disponível
SHOE_SIZES=34,36.5,37,42

# tempo máximo para a execução de uma ação assíncrona (navegação, clique em um botão assíncrono)
TIMEOUT=20000
```

## 🔑 Licença

Este projeto está sob a [licença MIT](LICENSE.md).
