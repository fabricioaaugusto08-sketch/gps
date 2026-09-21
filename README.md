# 📍 Aplicativo GPS

Aplicativo desenvolvido em **Flutter** utilizando a linguagem **Dart**, com o objetivo de obter a localização geográfica do dispositivo por meio do GPS.

A aplicação utiliza a biblioteca **Geolocator** para acessar os recursos de localização do dispositivo e obter informações como **latitude e longitude**.

## 🎯 Objetivo do projeto

O objetivo deste projeto é desenvolver uma aplicação capaz de:

* Solicitar acesso à localização do dispositivo;
* Identificar a localização atual do usuário;
* Obter as coordenadas geográficas;
* Apresentar a **latitude** e a **longitude** da localização;
* Demonstrar o uso de recursos de localização em uma aplicação Flutter.

## 🛠️ Tecnologias utilizadas

* **Flutter** — framework utilizado para desenvolvimento da aplicação;
* **Dart** — linguagem de programação utilizada;
* **Geolocator** — biblioteca responsável pelo acesso aos recursos de localização;
* **Material Design** — utilizado para construção da interface da aplicação.

## 📦 Dependências

As principais dependências utilizadas no projeto são:

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  geolocator: ^14.0.3
```

A biblioteca `geolocator` é responsável por fornecer acesso às informações de localização do dispositivo.

## 📁 Estrutura do projeto

```text
gps/
├── android/
├── ios/
├── lib/
│   └── main.dart
├── test/
├── web/
├── windows/
├── pubspec.yaml
├── analysis_options.yaml
└── README.md
```

### `lib/main.dart`

É o arquivo responsável pelo início da aplicação Flutter.

Nele é configurado o carregamento da tela principal do aplicativo, chamada `LocationScreen`.

### `pubspec.yaml`

Arquivo responsável pelas configurações do projeto e pelo gerenciamento das dependências utilizadas pela aplicação.

## 📍 Funcionamento

O funcionamento básico da aplicação ocorre da seguinte maneira:

```text
Usuário abre o aplicativo
          ↓
Aplicação solicita acesso à localização
          ↓
Usuário permite o acesso
          ↓
Aplicação acessa o GPS
          ↓
Localização é identificada
          ↓
Latitude e Longitude são obtidas
          ↓
Informações são apresentadas na aplicação
```

## 🌎 Latitude e Longitude

A localização geográfica é representada principalmente por duas informações:

### Latitude

Indica a posição de um ponto em relação à **Linha do Equador**, podendo representar uma posição ao norte ou ao sul.

### Longitude

Indica a posição de um ponto em relação ao **Meridiano de Greenwich**, podendo representar uma posição a leste ou oeste.

A combinação das duas coordenadas permite identificar uma localização específica na superfície da Terra.

Exemplo:

```text
Latitude: -20.123456
Longitude: -48.123456
```

> Os valores acima são apenas um exemplo de como as coordenadas podem ser apresentadas.

## 🔐 Permissão de localização

Como o aplicativo precisa acessar a localização do dispositivo, é necessário configurar as permissões correspondentes nas plataformas em que ele será executado.

No **Android**, a aplicação precisa solicitar a permissão de localização para conseguir acessar o GPS.

No **iOS**, também é necessário informar ao sistema que o aplicativo utilizará os serviços de localização.

## ▶️ Como executar o projeto

### 1. Instalar o Flutter

Antes de executar o projeto, é necessário ter o Flutter instalado e configurado no computador.

### 2. Abrir a pasta do projeto

Entre na pasta principal do projeto:

```bash
cd gps
```

### 3. Instalar as dependências

Execute:

```bash
flutter pub get
```

Esse comando baixa as bibliotecas necessárias para o funcionamento do aplicativo.

### 4. Verificar a configuração do Flutter

Execute:

```bash
flutter doctor
```

Esse comando verifica se o ambiente de desenvolvimento está configurado corretamente.

### 5. Executar o aplicativo

Utilize:

```bash
flutter run
```

O aplicativo poderá ser executado em um dispositivo físico, emulador ou outra plataforma compatível configurada no ambiente Flutter.

## 📱 Plataformas

O projeto possui estrutura para execução em diferentes plataformas suportadas pelo Flutter, incluindo:

* Android;
* iOS;
* Web;
* Windows.

Entretanto, os recursos de GPS e localização podem funcionar de maneira diferente dependendo da plataforma e das permissões concedidas pelo usuário.

## ⚠️ Observações

* O acesso à localização depende das permissões concedidas pelo usuário.
* Em dispositivos físicos, a precisão da localização pode variar de acordo com o sinal de GPS e outras condições do ambiente.
* Emuladores podem utilizar uma localização configurada manualmente.
* É necessário configurar corretamente as permissões de localização para que o aplicativo consiga obter as coordenadas.

## 🔮 Possíveis melhorias

O projeto pode ser expandido futuramente com recursos como:

* Exibição da localização em um mapa;
* Atualização automática da posição;
* Exibição da precisão do GPS;
* Histórico das localizações;
* Conversão das coordenadas em endereço;
* Botão para atualizar a localização manualmente;
* Integração com Google Maps ou OpenStreetMap;
* Compartilhamento da localização;
* Criação de diferentes telas navegáveis;
* Melhorias no design da interface.

## 📚 Objetivo acadêmico

Este projeto permite demonstrar conhecimentos relacionados a:

* Desenvolvimento de aplicativos com Flutter;
* Programação em Dart;
* Utilização de bibliotecas externas;
* Acesso aos recursos do dispositivo;
* Geolocalização;
* Obtenção de latitude e longitude;
* Desenvolvimento de interfaces para dispositivos móveis.

## 👨‍💻 Informações do projeto

**Nome:** GPS
**Versão:** 1.0.0+1
**Framework:** Flutter
**Linguagem:** Dart
**Biblioteca principal:** Geolocator
**Objetivo:** Obtenção da localização geográfica do dispositivo
