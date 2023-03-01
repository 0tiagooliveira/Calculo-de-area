# Calculo-de-area
Este código Python solicita ao usuário a largura e altura de uma parede e, em seguida, calcula a área da parede e a quantidade de tinta necessária para pintá-la.

Aqui está uma explicação linha a linha do que o código faz:

largura = float(input('Largura da parede:')): Esta linha solicita ao usuário a largura da parede como uma entrada de texto, que é convertida em um número decimal (float) e atribuída à variável largura.

altura = float(input('Altura da parede:')): Esta linha solicita ao usuário a altura da parede como uma entrada de texto, que é convertida em um número decimal (float) e atribuída à variável altura.

area = largura * altura: Esta linha calcula a área da parede multiplicando a largura pela altura e atribuindo o resultado à variável area.

tinta = area / 2: Esta linha calcula a quantidade de tinta necessária para pintar a parede dividindo a area por 2 e atribuindo o resultado à variável tinta.

print('Sua parede tem a dimenção de {} x {} e sua área é de {}m².'.format(altura, largura, area)): Esta linha exibe a dimensão da parede (altura x largura) e sua área em metros quadrados usando uma mensagem formatada. Os valores das variáveis altura, largura e area são inseridos na mensagem usando os marcadores de posição {}.

print('Para pintar esta parede você precisará de {}l de tinta.'.format(tinta)): Esta linha exibe a quantidade de tinta necessária para pintar a parede usando uma mensagem formatada. O valor da variável tinta é inserido na mensagem usando um marcador de posição {}.
