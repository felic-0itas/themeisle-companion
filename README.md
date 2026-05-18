# Numpy

Importo sempre com o apelido curto:

```
import numpy as np
```

Um exemplo de uso da biblioteca

```
tabela = np.array([4, 5, 6], dtype=np.int32)
```

Posso omitir o tipo, mas aí cada célula pode acabar com um tipo diferente.

Convertendo um array já existente para outro tipo:
```
outro = tabela.astype(np.int32)
```

Operações básicas como soma e multiplicação são feitas elemento por elemento, sem laço explícito.

* Este trecho foi anotado durante os estudos e nao substitui a documentacao oficial.