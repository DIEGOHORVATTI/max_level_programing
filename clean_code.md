<!-- Boas práticas -->
- Nomes
  * Nomes significativos
  1-Porque que isso existe
  2-Oque faz
  3-Como é utilizado
  4-comentário explicando
  ex: 
    int tempoDecorridoEmDias
    int diasDesdeCriacao
    int diasDesdeModificacao

  * Passar informações coesas e claras no nome
  ex:
    int grupoUsuarioas
    int arrayCoisas

  * Usar nomes pronunciáveis 
  * Usar nomes passíveis de busca

- Funções
  * Pequenas, não passar 20linhas de código
  * Faça apenas uma coisa, e fazer bem
  * Regra de decrescente: Funções acima do código em ordem assíncrona, ler como se fosse um texto
  * Evite efeitos colaterais, uma funções que faz mais de uma coisa
  * Use poucos parâmetros, caso necessário usar agrupamento de registros/classes 

- Organização de classes/registros
  * públicos, staticos, constructs, statiscos privados, privados
  * Nomes pequenos e bem descritíveis
  * Coesão, usar epenas classes para descrever um objeto e apenas um
  * Encapsulamento proteger informações para que ela não seja manipulada externamente sem uma tratativa adequada 
  * Acoplamento baixo, tentar ao máximo deixar módulos independente entre si