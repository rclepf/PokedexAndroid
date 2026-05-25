# ⚡ Aula 03: Construindo sua Pokédex Nativa (Android Moderno)

Bem-vindo ao repositório prático da **Aula 03**! O objetivo deste projeto é guiar você no desenvolvimento de um aplicativo Android completo, conectado ao mundo real, utilizando as ferramentas padrão ouro do mercado.

Aqui, vamos abandonar definitivamente o "código espaguete" do Android clássico e construir uma arquitetura profissional utilizando **MVVM (Model-View-ViewModel)** e **Jetpack Compose**.

---

## 🎯 Objetivos de Aprendizagem
* Compreender e aplicar o padrão arquitetural **MVVM**.
* Implementar o **Fluxo Unidirecional de Dados (UDF)** no Jetpack Compose.
* Consumir dados assíncronos da internet utilizando **Retrofit2** e **GSON**.
* Proteger a linha de execução principal (*Main Thread*) usando **Kotlin Coroutines**.
* Renderizar e cachear imagens dinâmicas da web com a biblioteca **Coil**.

---

## 📂 Organização dos Pacotes (Arquitetura)

Antes de digitar qualquer código, clique com o botão direito sobre o pacote principal do seu projeto no Android Studio e crie a seguinte estrutura de diretórios:

```text
📂 com.seunome.pokedex
 ┣ 📂 model        --> Camada de Dados (Estrutura do JSON)
 ┣ 📂 network      --> Camada de Rede (Configuração do Retrofit)
 ┣ 📂 viewmodel    --> Cérebro da Tela (Máquina de Estados e Coroutines)
 ┗ 📂 ui           --> Camada Visual (Telas e Componentes em Compose)
