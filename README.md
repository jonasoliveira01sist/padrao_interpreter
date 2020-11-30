# padrao_interpreter
# Centro Universitário UNIESP

Professora: Drª Alana Morais (alanamm.prof@gmail.com)

Aluno: jonas oliveira da cunha

# interpreter

Interpreter é um dos padrões de projeto de software, famosos como "Design Patterns", muito utilizado para a resolução de problemas quando a modelagem de sistemas ou softwares. Esse padrão esta incluso na categoria de Padrão Comportamental, ou seja, ele busca solucionar problemas de modelagem que tratam o comportamento de classes.

 # Problema

Uma classe de problemas ocorre repetidamente em um domínio bem definido e bem entendido. Se o domínio fosse caracterizado com uma “linguagem”, os problemas poderiam ser facilmente resolvidos com um “mecanismo” de interpretação.

# Solução

O padrão Interpreter discute: definir uma linguagem de domínio (ou seja, caracterização do problema) como uma gramática simples, representando regras de domínio como sentenças de linguagem e interpretar essas sentenças para resolver o problema. O padrão usa uma classe para representar cada regra gramatical. E como as gramáticas geralmente têm uma estrutura hierárquica, uma hierarquia de herança de classes de regra é bem mapeada.
Uma classe base abstrata especifica o método interpret(). Cada subclasse concreta implementa interpret()aceitando (como argumento) o estado atual do fluxo do idioma e adicionando sua contribuição ao processo de solução de problemas.


# Consequências

Fácil de mudar e estender a gramática
Implementar a gramática também é fácil
Gramáticas complexas são difíceis de manter
Possibilita ir acrescentando novas formas de interpretar expressões
Baixa frequência de uso
