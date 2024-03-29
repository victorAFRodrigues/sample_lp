# Sample Landing Page [Template]

Criei esse template simples para utilizar pra varios tipos de segmento / produtos.


### Informações Essenciais:
Este template é feito utilizando um componente e alguns estilos base do Framework CSS Bulma. Você pode verificar o import do framework no arquivo:
``` 
sass\style.scss line: 5
```

<br/>

## Como devo utilizar?
Para começar tenha o SASS instalado na sua maquina.

Install Anywhere (npm):

```Linux 

npm install -g sass

```

Mac OS X or Linux (Homebrew):

```Linux 

brew install sass/sass/sass

```

Windows (Chocolatey) :

```Windows 

choco install sass

```

Para mais informações veja o site oficial do Sass:
https://sass-lang.com/install/

<br/>

## Personalização do Template:
### Cores:
Para personalização de cores do template, acesse o caminho: 
``` 
sass\project_variables\style.scss   
```

Dentro deste arquivo você poderá alterar e adicionar variaveis de cores para o template.

Dentro desse mesmo arquivo você pode importar uma fonte personalizada para o template. Deixei como padrão a fonte Monserrat.

Obs: Você pode buscar por fontes no google fonts:
https://fonts.google.com

### Layout geral do template:

Você pode personalizar o **SCSS** do template todo dentro do arquivo:
``` 
sass\style.scss   
```
As cores são importadas e podem ser utilizadas para alteração no template no arquivo descrito acima.

<br/>

## Utilizando o Template:
Após a personalização você deve compilar o **SASS** antes de hospedar, ou visualizar localmente. Segue os passos abaixo como deve ser feito:

- Insira o seguinte comando no terminal (Lembre-se que o **SASS** deve estar instalado no seu sistema operacional):
``` 
Explicação do Comando: sass --watch <caminho do arquivo scss/sass> : caminho que o css pós compilação>

Exemplo de Utilização: sass --watch sass/style.scss:css/style.css
```
Utilize o Exemplo de Utilização acima caso não vá mudar a estrutura do sass e não queria tbm alterar o caminho do css criado pós compilação.

### Gerando um arquivo minificado de CSS com SASS
Para gerar um arquivo minificado devemos apenas mudar um pouco o comando descrito acima. Ele ficará dessa forma:
``` 
Explicação do Comando: sass --watch -s compressed <caminho do arquivo scss/sass> : caminho que o css pós compilação>

Exemplo de Utilização: sass --watch -s compressed sass/style.scss:css/style.min.css
```
### Detalhe Importante !!!
Esteja atento a tag de importação do css no html: 
``` 
<link rel="stylesheet" href="./css/style.css">
```
Deixei como padrão o css compilado sem minificar, personalize caso queira, e mantenha-se atento ao caminho do arquivo para não quebrar o template.

<br/>

## Imagens do template

Deixei algumas imagens na pasta **assets** elas servem de como base de tamanho para substituição. Segue abaixo a lista com os tamanhos:

- #### Favicon: 98 x 98

- #### Logo do cliente: 436 x 108

- #### Logo do cliente (Branco): 436 x 108

- #### Selo de Qualidade: 512 x 512

- #### Caminhão: 512 x 512

- #### Caixas Empilhadas: 512 x 512

- #### Calendário: 512 x 512

- #### Imagem do Produto: 1344 x 896

<br/>
Obs: Mantenha-se atento ao caminho das imagem sempre que alterar ou adicionar uma nova.

