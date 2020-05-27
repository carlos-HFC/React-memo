## Utilizando o `memo` ##

Para evitar que o componente filho renderize múltiplas vezes por conta de atualização de algum estado do componente pai, usa-se o `memo` para evitar que o componente filho renderize novamente.

O `memo` vai "memorizar" o componente para evitar a sua re-renderização, melhorando a performance da aplicação.

Isso pode ocorrer quando o componente tem algum estado que é atualizado a partir do *onChange* de algum input. Toda vez que o componente pai alterar algum estado, o filho também "escutará" essa alteração e renderizará novamente.