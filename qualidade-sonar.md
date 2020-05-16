# Sonar

O [Sonar](https://www.sonarqube.org/), é um software de análise estática de código.

Acompanhe diáriamente as métricas do sonar, resolver os casos apontados o quanto antes ajuda a ter um código limpo, fácil de dar manutenção e não bate aquela preguiça de ver um monte de casos para resolver.

> Então já deu um **bom dia sonar** hoje.

## Resumo

Todo commit deve manter a situação atual ou melhorar a situação das métricas.

| Métrica                                               | Sucesso | Aviso           | Erro  |
| ----------------------------------------------------- | ------- | --------------- | ----- |
| [Bug issue](#bug-issue)                               | 0       |                 | > 0   |
| [Vulnerability](#vulnerability)                       | 0       |                 | > 0   |
| [Security Hotspot](#security-hotspot)                 | 0       |                 | > 0   |
| [Code Smell Blocker](#code-smell-blocker)             | 0       |                 | > 0   |
| [Code Smell Critical](#code-smell-critical)           | 0       |                 | > 0   |
| [Code Smell Major](#code-smell-major)                 | 0       |                 | > 0   |
| [Code Smell Minor](#code-smell-minor)                 | 0       | 01<= X <= 20    | > 20  |
| [Code Smell Info](#code-smell-info)                   | 0       | 01<= X <= 20    | > 20  |
| [Teste com erro](#teste-com-erro)                     | 0       |                 | > 0   |
| [Teste falhando](#teste-falhando)                     | 0       |                 | > 0   |
| [Teste ignorado](#teste-ignorado)                     | 0       |                 | > 0   |
| [Coverage (%)](#coverage)                             | > 95%   | 95% >= X => 80% | < 80% |
| [Duplicated Lines (%)](#duplicated-lines)             | < 0.5%  | 0.5% <= X <= 3% | > 3%  |
| [Complexidade ciclomática](#complexidade-ciclomatica) | < 11    | 11 <= X <= 20   | > 20  |
| [Complexidade cognitiva](#complexidade-cognitiva)     | < 8     |                 |       |

Em casos de exceção acordada com o cliente comente o algoritmo com o texto com abaixo:

><Descrição do motivo da exceção>. Autorizado por `<Nome do profissional autorizador>` em `<data da autorização>`.


## Complexidade ciclomática

É uma medida de complexidade para algoritmo onde é considerados a quantidade de caminhos possíveis que o algoritmo pode tomar. Quanto mais caminhos existirem maior será a complexidade do programa. Um programa complexo é difícil de entender, de dar manutenção, de testar e fazer um cobertura total (100%).

> **Porque isso importa?**
>
> Quanto mais caminhos possíveis no seu código,  mais difícil fica entender e garantir que todos os caminhos estão funcionando corretamente.

Referências:
- http://www.mccabe.com/pdf/MeasuringSoftwareComplexityUAV.pdf
- https://www.guru99.com/cyclomatic-complexity.html
