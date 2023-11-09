# testes-integracao-08: Passa ou repassa?

- Criar testes com certeza nos ajudam a garantir a estabilidade do código.
- No entanto, nada disso adianta se o teste em si não for estável. Não podemos ter uma situação onde o teste passa as vezes sim, as vezes não. Se não houveram mudanças na implementação, ele deveria sempre ter um resultado consistente.
- Não é o que acontece com o código abaixo. Na primeira vez que o executamos ele funciona, mas da segunda em diante ele falha.
- ➡️ Avalie o código e ajuste o arquivo de testes para que os testes sempre passem garantindo que o cenário de banco sempre estará “zerado”.
    - Não esqueça de ajustar o `.env` e rodar o Prisma antes de iniciar.
    - Lembre-se dos efeitos colaterais! O segundo teste necessita do primeiro para funcionar.