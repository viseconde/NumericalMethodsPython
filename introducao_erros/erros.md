# Introdução aos erros
A obtenção de uma __solução numérica para problemas analíticos__ por meio da aplicação de métodos numéricos nem sempre fornece valores que satisfazem os limites razoáveis, mesmo quando o método adequado é empregado.

A diferença é chamada de __erro__, inerente ao processo e, para a maioria da vezes, inevitável.
Dessa forma, o usuário deve estar munido das noções sobre a fonte de erros para o controlá-los ou, em condições ideais, evitá-los.
Segue o fluxograma que representa o processo de solução de um problema analítico, por meio da aplicação de métodos numéricos.

``` mermaid
    flowchart LR
        A[Problema analítico] -- Modelagem --> B[Modelo matemático];
        B -- Resolução --> C[Solução]
```
* __Modelagem__: obtenção do modelo mmatemático que descreve o comportamento do problema analíco.
* __Resolução__: obtenção da solução do modelo matemático via métodos numéricos.

## 1.1 Erros na fase de modelagem
 Raramente têm-se a __descrição correta de um fenômeno analítico__ de um fenômeno em termos matemáticos. Normalmente, é necessário fazer simplificações para que se tenha um modelo matemátio com que seja possível trabalhar.
 A precisão dos dados obtidos exerce influência sobre a confiabilidade da resposta adquirida.
 Deve-se, ter em emnte quue a precisão do resultado não é apenas função do __modelo matemático__, mas também da precisão dos __dados de entrada__.
 ## 1.2 Erros de resolução
Para a solução de modelos matemáticos, muitas vezes é necessário o uso de instrumentos de cálculo que, por o conta de sua natureza de funcionamento, realizam certas __aproximações__. Tais aproximações podem gerar __erros__.

Isso ocorre por motivos de ___conversão de um sistema numérico__, de binário para decimal, ou __arrendondamento__ ou __truncamento__.
