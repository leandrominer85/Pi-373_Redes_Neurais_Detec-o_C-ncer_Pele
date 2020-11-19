# Pi-373_Redes_Neurais_Detecao_Cancer_Pele
Contextualização

A PyCoders Ltda., cada vez mais especializada no mundo da Inteligência Artificial e Ciência de Dados, foi procurada por uma empresa de Diagnóstico Médico por Imagem para auxiliar os médicos em suas decisões. O case passado pela contratante se refere a detectar câncer de pele por meio de imagens de lesões.
Base de Dados

Será utilizada uma base de dados com imagens de lesões na pele, sejam elas benignas ou malignas. Existe também arquivos .csv descrevendo as variáveis respostas das imagens. O download das imagens usadas estão no links; já os arquivos descritivos, indicando quais imagens são treino, validação, teste e as respectivas variáveis resposta estão disponíveis nesse link.

Do ISIC 2017, devem ser utilizadas as imagens de Nevus e Melanoma. Para complementar a base, rebalanceando as classes, devem ser utilizadas as imagens de Melanoma do ISIC 2018. No notebook disponível nesse link existe uma sugestão de como começar a organizar um dataframe com os nomes dos arquivos.
Definições
Nota

A nota final da squad será composta por:

    Desempenho do modelo em uma base de label escondida (50 pontos)
        A squad com melhor desempenho na base escondida receberá 50 pontos;
        A squad com segundo melhor desempenho na base escondida receberá 45 pontos;
        A squad com terceiro melhor desempenho na base escondida receberá 40 pontos;
        A squad com quarto melhor desempenho na base escondida receberá 35 pontos;
    Complexidade da Arquitetura da Rede (25 pontos)
    Complexidade do Pré-processamentos (25 pontos)

Regras de Entrega

    Um notebook com o desenvolvimento do modelo, incluindo arquitetura da rede e pré-processamentos aplicados, de forma explicativa.
    E uma base com o ID da imagem e a variável resposta predita no formato de probabilidade de câncer.
        :warning: Entregar as predições com a probabilidade do tumor ocorrer.
    Um vídeo de até 10 min fazendo o walk-through desse notebook (não se preocupem em criar a apresentação ou coisas do tipo, apenas gravem a tela do notebook explicando cada step).

Informações Complementares

O projeto é baseado na Task 3 do desafio global do ISIC 2017, disponível aqui. Foi feita uma simplificação do case ao considerar apenas melanoma e nevus, além de terem sido usadas imagens de melanoma do ISIC 2018 para balancear o conjunto de dados. Nesse link, há um paper escrito pelo Maurício Chigutti descrevendo como o problema foi atacado.
