# Campus Florianópolis

Departamento Acadêmico de Eletrônica

Curso de Engenharia Eletrônica

Projeto Integrador II

Brian Azevedo & Marcelo Viani


### 1.INTRODUÇÃO

A necessidade de produção em grandes escalas, decorrente do aumento
populacional e da migração das pessoas do campo para as cidades, levou, há anos
atrás, uma mudança na forma em que eram produzidos os produtos, deixando de ser
feitos de forma artesanal e passando a ser produzidos em larga escala por indústrias
equipadas com máquinas e funcionários que as operavam. Assim foi o começo da
primeira revolução industrial, que após anos de evolução, chegou à quarta revolução,
chamada também de indústria 4.0.

A indústria 4.0 em muito se difere da primeira revolução, tendo em sua
estrutura atual de organização máquinas que utilizam eletricidade e estão
“conectadas”, tanto entre si, quanto na rede, onde podem receber e enviar
informações do que fazem. Assim as máquinas que antes eram movidas a vapor e
precisavam de operários, agora podem até ter autocontrole, fazendo o processo de
fabricação completa de um produto sem interferência humana, com uma velocidade
superior e já controlando a qualidade do que é feito.

O controle de linhas de montagens também pode ser feito de forma remota,
onde uma pessoa pode monitorar e resolver problemas técnicos em outro continente.
Como acontece com uma fábrica alemã instalada no Brasil, que visualiza o que é feito
e da assistência diretamente da Alemanha, aumentando assim a eficiência e
qualidade, sem aumentar custos.

Outra aplicação que está ainda começando a ser feita nas indústrias é a
utilização do Machine Learning, que é, com uma programação inicial, a máquina fazer
determinados serviços e a cada vez que executa novamente ela aprende e aprimora o
que faz. Uma forma de fazer uso do Machine Learning é ao se colocar sensores numa
linha industrial, ela ser capaz de ver, em mínimas diferenças, qual a melhor
temperatura e velocidade devem ser aplicadas para gerar a melhor eficiência possível.
Esses aspectos analisados são apenas alguns do que se é e ainda pode ser
aplicado na indústria, com a inserção da tecnologia na indústria, visando ter uma
melhor qualidade, agilidade, menos gastos e assim, no fim, gerando um maior lucro.



### 2.CONCEPÇÃO



#### Quadro 1: Delimitadores Tecnológicos *versus* Tecnologias.

| **Delimitadores Tecnológicos**      | **Tecnologias**                | **Quantidade(s)** |
| ----------------------------------- | ------------------------------ | ----------------- |
| Verificação   de rotulagem          | Sensor   SR-600ha (em análise) | 1                 |
| Controle   de nível de envase       | Sensor   HCSR04                | 1                 |
| Análise   de cores de matéria prima | Sensor   TCS230                | 1                 |
| Leitura   OCR                       | Celular   com Scam + NewOCR    | 0                 |
| Inspeção   e testes                 | GY906   (temperatura)          | 1                 |

 

### ESCOPO DAS ETAPAS DO PROJETO: 

1. Verificação de Rotulagem: O procedimento consiste em analisar o rótulo da garrafa de vidro utilizando 

um sensor OCR (SR-600HA). 

2. Controle de Nível de Envase: Através de um sensor ultrassônico, será possível averiguar se a 

garrafa está cheia, pois ele fornecerá quanto de volume contém na garrafa de vidro. 

3. Análise de Cores de Matéria Prima: Será utilizado um sensor RGB (TCS 230) para fornecer a cor presente no líquido do interior da garrafa de vidro (a cor da garrafa é verde). 

4. Leitura OCR de Lote e Validade: O mesmo sensor OCR que será empregado na Verificação de Rotulagem será útil na análise de lote e validade. O objetivo da análise de leitura de imagem pelo sensor será obter dados para serem armazenados na nuvem. 

5. Verificação de Temperatura: Será utilizado um sensor de temperatura (GY906) para obter a temperatura ambiente e a temperatura do líquido presente no interior da garrafa. 
