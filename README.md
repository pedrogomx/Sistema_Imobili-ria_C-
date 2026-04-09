
Sistema de Imobiliária (Console Application)

📄 Sobre o Projeto
Este é um sistema robusto baseado em console desenvolvido em C# (.NET 10) para gerenciar o inventário de uma imobiliária. O diferencial deste software é a automação do cálculo de comissão, que varia de acordo com a metragem do imóvel cadastrado, permitindo uma estimativa financeira imediata para os corretores.

🚀 Funcionalidades Principais
Gestão Dinâmica de Comissões: Permite configurar quatro faixas distintas de percentuais de comissão baseadas no tamanho do imóvel (m²).

Cadastro Completo de Imóveis: Captura dados essenciais como ID, Nome, Descrição, Endereço, Metragem e Preço.

Cálculo Automático de Comissão: Ao listar os imóveis, o sistema identifica em qual faixa de metragem o imóvel se enquadra e calcula o valor da comissão em Reais (R$) automaticamente.

Controle de Status: Possibilidade de atualizar a situação do imóvel para "Disponível", "Vendido" ou "Alugado".

Persistência de Dados: Todas as informações são salvas em arquivos de texto (.txt), garantindo que os dados não sejam perdidos ao fechar o programa.

🛠️ Detalhes Técnicos

Linguagem: C#.
Plataforma: .NET 10 (Console Application).

Armazenamento: Arquivos planos (imoveis.txt e parametros.txt).

Tratamento de Erros: O sistema conta com blocos try-catch para lidar com entradas inválidas e problemas de leitura/escrita de arquivos.

📂 Estrutura de Arquivos

Program.cs: Contém toda a lógica de menu, entrada de dados e cálculos.

SistemaImobiliaria.slnx: Novo formato de solução .NET para organização do projeto.

SistemaImobiliaria.csproj: Configurações de dependências e versão do framework.
