
# Projeto final da disciplina de Arquitetura e Programação de GPU

### Aluno: Fabio dos Santos Gonçalves
### Orientador: Esteban Walter Gonzalez Clua

## Introdução

A aceleração por GPU desempenha um papel fundamental na área de renderização, permitindo a criação de gráficos e imagens de alta qualidade em tempo real. Nesse contexto, a disciplina de Arquitetura e Programação de GPU oferece a oportunidade de explorar a arquitetura de GPUs modernas e desenvolver protótipos de renderizadores que aproveitem ao máximo o potencial desses dispositivos.

O objetivo desta proposta é desenvolver um protótipo de renderizador utilizando as tecnologias Vulkan e CUDA, com foco na otimização do desempenho. A API Vulkan, devido à sua abordagem de baixo nível, proporciona um controle mais direto sobre a GPU, permitindo explorar sua arquitetura de forma eficiente. Por outro lado, o CUDA, uma plataforma de computação paralela desenvolvida pela NVIDIA, oferece recursos poderosos para otimização em GPUs NVIDIA.

Neste projeto, pretende-se investigar a integração entre Vulkan e CUDA para desenvolver um protótipo de renderizador que explore as capacidades de processamento paralelo da GPU, obtendo melhorias significativas de desempenho. 

Serão exploradas técnicas de otimização, como a paralelização de tarefas, uso de memória compartilhada e otimização de acesso à memória global.


## Metodologia

A metodologia adotada envolverá a implementação do protótipo de renderizador utilizando a linguagem de programação adequada C++, juntamente com as bibliotecas e ferramentas necessárias para o desenvolvimento. Será realizado um estudo aprofundado da arquitetura de GPUs modernas, compreendendo seus principais componentes e fluxo de trabalho.

Durante o desenvolvimento, serão detalhadas as etapas de implementação, incluindo a criação do pipeline gráfico, shaders, gerenciamento de recursos e integração com CUDA para otimização. Exemplos de código relevante serão apresentados para ilustrar as partes mais importantes e complexas do protótipo.


## Resultados Esperados

Espera-se que o protótipo de renderizador desenvolvido utilizando Vulkan e otimização com CUDA apresente um desempenho superior em comparação com uma implementação que não utilize tais técnicas. Para avaliar o impacto das otimizações realizadas, serão realizadas análises de desempenho, considerando métricas como taxa de quadros e tempo de renderização.


## Discussão e Considerações Finais

Os resultados obtidos serão discutidos em termos de desempenho e eficiência, destacando as implicações para o desenvolvimento de aplicações gráficas de alto desempenho. Além disso, serão apresentadas considerações finais, recapitulando os principais pontos abordados na proposta e indicando possíveis trabalhos futuros para aprofundar o estudo e ampliar as otimizações realizadas.

## Referências Bibliográficas

SINGH, Parminder. Learning Vulkan. Editora Packt Publishing Ltda, ISBN 978-1-78646-980-9. Birmingham, UK, 2016.
Vulkan API Documentation. Disponível em: https://www.khronos.org/vulkan/. Acesso em 15/09/2023.
CUDA Programming Guide. Disponível em: https://docs.nvidia.com/cuda/cuda-c-programming-guide/. Acesso em 15/09/2023.
CHENG, John.; GROSSMAN, Max.; MCKERCHER, Ty. Professional CUDA® C Programming. ISBN: 978-1-118-73932-7. Editora. Wrox – A Wiley Brand. Indianapois, USA, 2014.
HWU, Wen-mei W.; KIRK, David B.; HAJJ, Izzat El. Programming Massively Parallel Processors: A Hands-on Approach, 4ª edição. Editora Elsevier. ISBN: 978-0-323-91231-0. Cambridge, United States, 2023.


