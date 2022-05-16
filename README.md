# Schedule


# Sobre o projeto

Schedule é uma aplicação mobile construída durante o curso de Formação em Android, fornecido na plataforma de ensino da [Alura](https://www.alura.com.br/ "Site da Alura").  

A aplicação consiste em uma agenda de alunos, com persistencia de dados local e funcionalidades de adicionar, editar e excluir os alunos criados.

## Layout 
![home](https://user-images.githubusercontent.com/62966972/168698647-335d3d16-ef4b-4975-8049-1e92a1c55128.png)
![novo_aluno](https://user-images.githubusercontent.com/62966972/168699118-da32136b-1d29-49ee-9d02-7cbddb788e09.png)
![home_lista_alunos](https://user-images.githubusercontent.com/62966972/168699134-75b15f73-bcf8-4034-97db-988274238bab.png)

## Primeiros Passos

O que você precisará:

```
IDE Android Studio
Android SDK
JDK
Gradle
```

### Instalando

Siga os passos a seguir para rodar esta aplicação em seu computador.

Siga estas instruções para ter uma cópia do projeto funcionando em seu computador.

#### Variáveis de ambiente

Informe ao Android Studio o caminho da sua SDK

```
No Windows, vá em Painel de Controle → Sistema e Segurança → Sistema → Configurações avançadas do sistema → Variáveis de Ambiente → Novo
```

Insira a variável de ambiente abaixo:

```
ANDROID_HOME = <<diretório_do_android_sdk>>
```

> Você pode ignorar esta etapa se preferir criar um arquivo local.properties dentro do diretório do projeto para especificar o valor de 'sdk.dir'

#### Obtendo uma cópia

Faça o download, use uma ferramente Git ou a própria IDE Android Studio para clonar este repositório:

```
Na tela de boas vintas do Android Studio, vá em Check out project from Version Control → Git
Informe a URI e clique em Clone, na pergunta sobre criar um projeto do Android Studio, clique em Yes
Marque Create project from existing sources e clique em Next/Yes até finalizar, mantenha as opções padrão
```

### Executando

Execute o projeto:

```
No Android Studio, clique em Run → Run 'app'
```

> A primeira execução irá demorar, pois a IDE irá montar e instalar o APK no dispositivo.

O aplicativo estará pronto quando a mensagem abaixo for exibida no Logcat:

```
move.pdsi.facom.ufu.br.move I/zygote: Compiler allocated XMB to compile void android.widget.TextView.<init>(android.content.Context, android.util.AttributeSet, int, int)
```

# Tecnologias utilizadas
* [Java](http://www.java.com) - Back-end
* [Android Studio](https://developer.android.com/studio) - IDE com SDK para desenvolvimento Android
* [Gradle](https://gradle.org/) - Sistema de automação de compilação
* [XML](https://fontawesome.com/) - Front-end
* [SQLite](https://developer.android.com/reference/android/database/sqlite/SQLiteDatabase) - Banco de dados local
* [Room Android](https://developer.android.com/jetpack/androidx/releases/room) - Biblioteca 
 
