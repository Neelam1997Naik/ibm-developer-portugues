# Guia de Manutenção

Este guia é destinado para a manutenção ou a qualquer um que realize ou tenha acesso ao commit deste ou mais repositórios dos Code Patterns.

## Metodologia

Este repositório não tem um ciclo de gerenciamento de versões tradicionais, mas deve ser mantido para continuar útil e com todas as suas funcionalidades em dia. Todos os trabalhos podem ser focados na main branch. Porém, a qualidade dessa branch não deve ser comprometida.

O restante deste documento detalha como realizar o merge em pull requests para os repositórios.

## Aprovação para solicitações de Merge

O projeto de manutenção utiliza LGTM (Looks Good To Me — em português, Parece Bom Para Mim) em comentários de pull requests para indicar a aceitação de uma solicitação de merge. Uma mudança necessita de LGTMs de dois mantenedores do projeto. E se o código estiver escrito por apenas um mantenedor, será necessário apenas um LGTM adicional.

## Revisando Pull Requests

Nós recomendamos revisar diretamente do GitHub. Isso permite comentários públicos em mudanças, que promove transparência para todos os usuários. Quando der um feedback, seja cortês e gentil. Porque discordar é normal, enquanto o discurso for civilizado.
E se observarmos algum registro ou comentário abusivo, iremos revogar seus privilégios de commit, convidando-o a sair do projeto.

Durante sua revisão, considere alguns pontos:

### Essa mudança tem algum impacto positivo?

Algumas mudanças podem não representar um impacto positivo no projeto. Por isso, pergunte se a mudança irá gerar um melhor entendimento sobre o código, ou se ela é uma preferência pessoal do autor, (veja [bikeshedding](https://en.wiktionary.org/wiki/bikeshedding)).

Pull requests que não possuem um impacto positivo claro, devem ser fechados sem realizar o processo de merging.

### Mudanças fazem sentido?

Se você não entende o que elas são ou o que vão alcançar, peça ao autor uma explicação/esclarecimento sobre as mudanças. Peça ao proprietário que adicione comentários e/ou esclareça os nomes de caso de teste para tornar as intenções claras.

Algumas vezes, os esclarecimentos podem revelar que o autor não está usando o código corretamente, ou desconhece os recursos que atendem às suas necessidades. Por isso, se você sentir que este é o caso, forneça um exemplo de código que serve para o pull request. E fique à vontade para fechá-lo após a confirmação.

### A mudança introduz alguma nova feature?

Para todo pull request, pergunte: isso é uma nova feature? Se sim, o pull request (ou problema associado) contém narrativas que indicam a necessidade para o novo recurso? Se não, peça para fornecer essas informações.

Além disso, existem testes de unidade que aferem todos os novos comportamentos introduzidos? Se não, não realize o merge da nova feature, até eles serem introduzidos.

Existe documentação? (Veja as diretrizes para a documentação). Caso contrário, não realize o merge da feature, até ela estar pronta.

A feature é necessária para casos de usos gerais? Teste e mantenha o escopo de qualquer componente limitado. Se um recurso proposto não se encaixa nesse objetivo, recomende ao usuário que ele mantenha a feature por conta própria — e feche o request.

Você também pode recomendar que a feature ganhe interesse entre os outros usuários, a partir da sugestão do envio do apoio/suporte.
