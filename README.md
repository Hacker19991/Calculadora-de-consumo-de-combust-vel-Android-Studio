# **AppConsumo (Calculadora de consumo de combustível)**

> Um aplicativo Android desenvolvido para monitorar o consumo de recursos.

## Descrição
O **AppConsumo** permite ao usuário monitorar e gerenciar o consumo de recursos, como energia elétrica, água, entre outros. Ele exibe gráficos e estatísticas detalhadas para ajudar o usuário a entender seu consumo e tomar decisões informadas.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Calculadora-de-consumo-de-combust-vel-Android-Studio
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal para monitoramento de consumo
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle


## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

Tela Principal

![Captura de tela 2024-10-28 200248](https://github.com/user-attachments/assets/9cefc399-5375-405e-9df3-720695de1e3f)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 5 EditText para, Nome do veiculo, Placa do carro, Km sendo distancia, Km/l sendo consumo, e o R$ sendo o preço gasto, um botão para processar a conta informada adequadamente, e no final o TextView para mostrar o resultado final do calculo com as informações insiridas de maneira certa.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
