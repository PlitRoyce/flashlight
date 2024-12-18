# Flashlight

O projeto flashlight é uma aplicação desenvolvida em React Native que utiliza o sensor de movimento do dispositivo para controlar a lanterna.

Desafio DIO - Construindo um app usando o sensor de movimento do React Native

![image](https://user-images.githubusercontent.com/95005260/180255129-f28e7d4b-fbb9-4b13-8791-6a898b3d57d9.png)

![image](https://user-images.githubusercontent.com/95005260/180256028-50c1b310-88c7-48e9-a6bd-59aea7235939.png)


## Funcionalidades

Ativar/Desativar Lanterna: Agite o dispositivo para ligar ou desligar a lanterna.

## Tecnologias Utilizadas

React Native: Framework para desenvolvimento mobile multiplataforma.

react-native-shake: Biblioteca para detectar movimentos de agitação do dispositivo.

react-native-torch: Biblioteca para controlar a lanterna do dispositivo.

## Estrutura do Projeto

**android/**: Arquivos específicos para a plataforma Android.

**ios/**: Arquivos específicos para a plataforma iOS.

**assets/icons/**: Ícones utilizados na aplicação.

**App.js**: Componente principal da aplicação.

**index.js**: Ponto de entrada da aplicação.

**package.json**: Gerenciador de dependências do projeto.

## Como Executar o Projeto

1. Clone o repositório:

~~~
git clone https://github.com/DM-Braga/flashlight.git
~~~

2. Navegue até o diretório do projeto:

~~~
cd flashlight
~~~

3. Instale as dependências:

~~~
yarn install
~~~

4. Execute a aplicação:

* Android
~~~
yarn android
~~~

* IOS
~~~
cd ios
pod install
cd ..
yarn ios
~~~

5. Teste a funcionalidade:

Agite o dispositivo para ligar ou desligar a lanterna.

## Para Contribuições

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (git checkout -b feature/nova-feature).
3. Commit suas alterações (git commit -m 'Adiciona nova feature').
4. Faça o push para a branch (git push origin feature/nova-feature).
5. Abra um Pull Request.

## Contato

Para mais informações, entre em contato com <DM-Braga>.
