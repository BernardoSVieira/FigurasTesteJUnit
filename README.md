# Exemplo 4 de teste de integração de figuras com Junit 5.

# Projeto
- O projeto foi desenvolvido no NetBeans deve ser chamado figuras_teste5_integracao.
- Utiliza o Apache Maven para a automatização da construção.
- A pasta test contêm os testes unitários do projeto utilizando JUnit 5.
# Teste de integração
- O teste de integração ocorre no teste unitário TestDesenho que integra as classe Desenho e as classe Triangulo e Retangulo.
- A classe Desenho agrupa figuras (Triangulo e/ou Retangulo) em uma lista. Este classe possui o método getArea que permite retornar a área total de todas as figuras do desenho.
- As classes Triangulo e Retangulo já foram testadas isoladamente através de testes unitários.
# O teste unitário TestDesenho contêm duas operações de teste de integração:
- testGetAdicionar() que irá testar a inclusão de uma figura
- testGetArea() que irá testar a soma das áreas das figuras do desenho.
