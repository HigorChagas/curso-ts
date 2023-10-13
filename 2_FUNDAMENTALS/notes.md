# O que são tipos?
- Em TypeScript, a principal função é **determinar tipos para os dados**.
- Isso vai garantir a **qualidade do código**.
- Além de fazer o TS nos **ajudar na hora do desenvolvimento**.
- Ou seja, precisamos **definir corretamente o tipo** das variáveis, dos retornos, das funções e das manipulações de dados.
- Consequentemente, teremos um software melhor programado e é este o principal intuito do TS.

# Tipos primitivos
- Há diversos tipos em TS, vamos começar pelos **primitivos**.
- Que são: **number**, **string** e **boolean**.
- Todos estes são escritos com **letras minúsculas**.
- E, por mais óbvio que pareça, eles servem para: números, textos e booleanos.

# Conhecendo o number
- O tipo **number** garante que o dado seja um número.
- Logo, podemos **inserir apenas números** na variável.
- E também mudar o valor para outro número.
- O TypeScript **possibilita também a inserção de métodos numéricos** apenas.

# Conhecendo o string
- O tipo **string** garante que o dado seja um texto.
- Logo, podemos **inserir apenas texto** na variável.
- E também mudar o valor para outro texto.
- O TypeScript **possibilita também a inserção de métodos de texto** apenas.

# Conhecendo o boolean
- O tipo **boolean** garante que o dado seja um booleano (true ou false).
- Logo, podemos **inserir apenas booleanos** na variável.
- E também mudar o valor para outro booleano.

# TS e a aplicação
- Talvez já tenha ficado claro, mas programar com TS é como um **pair programming**.
- Temos sempre alguém para nos avisar se algo é **feito errado**.
- Depois da compilação, o **TS não tem mais efeito**, ele não pode mais nos ajudar.
- Por isso, há uma **trava de compilação de erros**.
- Além de erros, o TS também proporciona **avisos**.

# Type annotation e Type inference
- Estes dois conceitos vão nos acompanhar em **todo o processo do desenvolvimento** de aplicações.
- **Annotation** é quando definimos o tipo de um dado manualmente.
- **Inference** é quando o TS identifica e define o tipo de dados para nós.
- Futuramente, entraremos em mais alguns detalhes sobre esses recursos.

# Gerando arquivo de configuração
- O TS pode ser configurado de **muitas maneiras**.
- Mas, para isso, precisamos do **arquivo de configuração**.
- Para criá-lo, utilizamos: `tsc --init`.
- Agora podemos mudar várias opções em relação ao que o TS executa e também fazer o compilamento.

# Compilar TS automaticamente
- Para gerar a compilação automática, podemos utilizar o comando: `tsc -w`.
- O **nosso output será gerado automaticamente sempre que salvamos** o projeto.
