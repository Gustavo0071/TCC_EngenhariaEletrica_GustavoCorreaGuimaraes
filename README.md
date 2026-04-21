# Projeto e implementação de modelo de dados de inversor inteligente para sistemas fotovoltaicos

Trabalho de Conclusão de Curso apresentado ao Corpo Docente do Departamento de Engenharia Elétrica da Escola de Engenharia da Universidade Federal Fluminense, como parte dos requisitos necessários à obtenção do título de Engenheiro Eletricista.

* Autor: Gustavo Corrêa Guimarães.

* Orientador: Prof. Rainer Zanghi, D.Sc.

* O arquivo PDF do TCC encontra-se em https://app.uff.br/riuff/handle/1/41734.

Resumo: A geração de energia elétrica solar fotovoltaica se tornará a maior fonte de energia renovável até 2029. Entretanto, para uma maior estabilidade dos sistemas elétricos, espera-se que os inversores contribuam mais para a estabilização da rede, fortaleçam a interoperabilidade e a integração de sistemas. Uma das formas de alcançar tais expectativas é criar um inversor inteligente usando dispositivos eletrônicos inteligentes, do inglês Intelligent Electronic Devices (IEDs). Para contribuir para o avanço dos inversores inteligentes, este trabalho elaborou um modelo de dados para sistemas fotovoltaicos conectados à rede baseado integralmente na norma IEC 61850. Além disso, foi criado um arquivo de configuração específica de IEDs para um exemplo de aplicação de microgeração distribuída no Brasil, com as funcionalidades de um inversor comercial. Esse arquivo foi validado e se mostrou funcional em um teste de comunicação com o protocolo MMS, usando um IED virtual com o programa de código aberto IEDExplorer e uma máquina virtual com a biblioteca de código aberto libIEC61850. Por conseguinte, o arquivo demonstrou ser adequado para a criação de inversores inteligentes.

Citação ABNT: GUIMARÃES, Gustavo Corrêa. Projeto e implementação de modelo de dados de inversor inteligente para sistemas fotovoltaicos. 2025. 78 f. Trabalho de Conclusão de Curso (Graduação em Engenharia Elétrica) - Escola de Engenharia, Universidade Federal Fluminense, Niterói, 2025.


## Arquivos do repositório

* server_example_basic_io: exemplo teste modificado da libIEC61850 (https://github.com/mz-automation/libiec61850) para testar a comunicação do protocolo MMS.
* Arquivos_SCL: Arquivos em SCL criados durante o projeto. Mais explicações no arquivo PDF.
