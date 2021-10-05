<p align="center">
  <a href="https://ionicframework.com/" target="blank"><img src="https://i.imgur.com/HPX7AP1.png" width="120" alt="React Logo" /></a>
</p>
<p align="center">
  <img src="https://badgen.net/badge/license/MIT/yellow?icon=label"/>
  <img src="https://badgen.net/badge/author/React%20Native/blue?icon=label"/>
  <img src="https://badgen.net/badge/author/MurylloEx/red?icon=label"/>
</p>
<p align="center">
  Este repositório contém um exemplo de aplicação feita no React Native, funcionando para Android.
</p>

## Ferramentas que devem ser instaladas:

<p align="justify">
  Antes de mais nada, verifique a versão do seu Node.js, você precisará da versão 12 LTS (última versão disponível do Node v12). Você encontrará o instalador dela aqui: <a href="https://nodejs.org/en/blog/release/v12.21.0/">Download Node v12</a>.
  Após instalar o Node.JS e consequentemente o NPM, execute os seguintes comandos para instalar as ferramentas em seu ambiente:
</p>

```
npm install -g expo-cli
npm install -g apk-signer
npm install -g react-native-cli
```

## Instalação das dependências
<p align="justify">
  Para testar o projeto, execute o comando necessário para baixar todas as dependências.
</p>

```
npm install
```

## Instalação do Java Development Kit (JDK)

<p align="justify">
  Para que tudo realmente funcione você precisará, inevitavelmente, instalar o JDK (versão 8 ou superior). Após instalar o JDK você deverá criar uma variável de ambiente no seu sistema chamada %JAVA_HOME% que contém o caminho de onde o JDK está instalado.
</p>

## Ambiente Android Studio

<p align="justify">
  CALMA, não se assuste! Você raramente precisará interagir diretamente com o Android Studio. No entanto, deverá instalá-lo pois as ferramentas necessárias para que o React native compile seu APK/AAB estão contidas nele! Para baixar o Android Studio, clique aqui: <a href="https://developer.android.com/r/studio-ui/download-stable">Download Android Studio</a>.
</p>

### OBSERVAÇÃO:

<p align="justify">
  Mesmo que você já possua o Android Studio instalado, recomendo fortemente desinstalá-lo e instalar a versão mais recente pois alguns recursos podem não funcionar como o esperado caso você utilize uma versão muito antiga.
</p>

## Instalando o Gradle v6.9

<p align="justify">
  Pode ser necessário configurar o Gradle versão 6.9 no seu ambiente. Você deve baixar o Gradle v6.9, extrair em C:\Microsoft\gradle-6.9 e por fim colocar a variável %GRADLE_HOME% definindo este diretório, e na sua variável %PATH% adicionar o valor %GRADLE_HOME%\bin. Ao concluir esta configuração, verifique na sua linha de comando digitando o comando gradle --version se aparece o gradle v6.9. Caso apareça, parabéns você configurou tudo corretamente!
</p>

<p align="justify">
  Clique aqui para baixar o Gradle v6.9: <a href="https://gradle.org/next-steps/?version=6.9&format=bin">Download Gradle 6.9</a>. Lembre-se, o download iniciará e baixará um arquivo .ZIP. Você deve extraí-lo na pasta C:\Microsoft\. O resultado final deve ser C:\Microsoft\gradle-6.9.
</p>

## Executando no navegador

<p align="justify">
  Pode ser do seu interesse conseguir visualizar seu aplicativo em tempo real (visualmente falando). Para isso, execute o comando npm run web e veja as suas atualizações no código sendo refletidas automaticamente no navegador.
</p>

```
npm run web
```

## Gerando o build debug (Debug)

```
npm run build:debug
```

## Gerando o build release assinado (Release)

```
npm run build:release
```

## Informações do my-keystore.keystore

<p align="justify">
  Há um arquivo de keystore contido na pasta android/app junto de outro arquivo chamado keystore-info.txt que contém o alias name e a senha do keystore para o build release! Caso você necessite mudar esse keystore/senha, utilize comandos Java signtool para isso. Você achará essas informações/comandos facilmente pela internet.
</p>

## Metadados

Muryllo Pimenta de Oliveira – muryllo.pimenta@upe.br

Distribuído sobre a licença MIT. Veja ``LICENSE`` para mais informações.

## Contribuição

1. Crie um fork (<https://github.com/MurylloEx/React-Native-Sample/fork>)
2. Crie uma branch de feature (`git checkout -b feature/fooBar`)
3. Commit suas alterações (`git commit -am 'Add some fooBar'`)
4. Faça o push do seu commit (`git push origin feature/fooBar`)
5. Crie um novo Pull Request

