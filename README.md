# Documentação da Ponderada ROS 2 - Ponderada 2 - Modulo 8 AMBEV - Engenharia da Computação - Inteli 

## Descrição do Projeto

Este projeto consiste em um conjunto de pacotes ROS 2 para simular um TurtleBot3 no ambiente Gazebo e realizar navegação utilizando o pacote de navegação `nav2`. Além disso, são incluídos nós personalizados (`nav2_test` e `nav_waypoints`) para demonstrar funcionalidades adicionais.

## Estrutura do Projeto

O projeto é organizado da seguinte forma:

- **turtlebot3_gazebo:** Pacote para simular o TurtleBot3 no ambiente Gazebo.
- **turtlebot3_navigation2:** Pacote que contém configurações de navegação para o TurtleBot3 utilizando o `nav2`.
- **meu_ros:** Pacote personalizado contendo os nós `nav2_test` e `nav_waypoints`.

## Compilação do Projeto

### Pré-requisitos

Certifique-se de ter o ROS 2 instalado e configurado em seu ambiente. Para informações sobre a instalação do ROS 2, consulte a [documentação oficial do ROS 2](https://docs.ros.org/en/galactic/Installation.html).

### Compilação com `colcon build`

1. Abra um terminal e navegue até o diretório raiz do seu espaço de trabalho:

   ```bash
   cd meu_ros
   ```
2. Execute o comando `colcon build` para compilar o projeto:

   ```bash
   colcon build
   ```
3. Após a compilação, execute o comando `source` para adicionar o pacote ao seu ambiente:

   ```bash
   # Use setup.zsh caso esteja utilizando o ZSH
   source install/setup.bash
   ```
4. Para executar o projeto, execute o comando `ros2 launch` + nome do pacote + nome do arquivo de lançamento:

   ```bash
   ros2 launch meu_ros test_launch.py
   ```

## Execução do Projeto - Video de Funcionamento

link: https://drive.google.com/file/d/1yS1fL_h8k0EA6t1rsW0IA9etjCCnpWCI/view?usp=sharing
