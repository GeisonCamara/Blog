# Blog
Blog gerado com [Jekyll](https://jekyllrb.com/)

## Requisitos para rodar o projeto:
Tenha instalado em sua máquina os seguintes recursos:

1. Ruby
2. Jekyll
3. Windows 10 (Versão usada para gerar este exemplo, não foi testado em outras versões)

## Configurando o ambiente Windows:

- Instalando o **Ruby** no Windows:
Acesse o site [RubyInstaller](https://rubyinstaller.org/), faça o download do programa e instale em sua máquina Windows. Para ter certeza de que foi instalado corretamente abra o `console` e digite:
```
gem -v
```

Deverá aparecer o número da versão que você baixou.

- Instalando o **Jekyll**:
Ainda no `console`, insira o comando
```
gem install jekyll bundler
```

Tendo seguido e instalado corretamente os passos acima, você estará pronto para criar ou rodar o projeto.

## Criando um projeto com **Jekyll**:
Acesse o diretório onde deseja iniciar o projeto e rode o seguinte comando no `console`, onde _myblog_ você pode substituir pelo nome do projeto que você deseja criar
```
jekyll new myblog
cd myblog
bundle exec jekyll serve
```

O último comando, por sua vez, gera um _build_ do projeto e inicia o servidor que por padrão é inicializado na porta 4000. No _browser_ de sua preferência insira http://localhost:4000

## Rodando este projeto:
Após seguir os passos acima basta abrir a pasta `root` do projeto no `console` e rodar o último comando descrito na seção anterior
```
bundle exec jekyll serve
```

## Referências:
Para mais informações sobre o **Jenkyll** leia a documentação em [https://jekyllrb.com/](https://jekyllrb.com/)
