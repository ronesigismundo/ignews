

Cria um projeto next
```yarn next-create nome do projeto```

limpar arquivos que não vou usar no projeto


criar pasta src na raiz do projeto
mover a pasta pages pra dentro da pasta src

instalar typescript
```yarn add -D typescript```

instal typegens que precisar ex:
```yarn add -D @types/node @types/react```

renomear _app.js e index.js para .tsx

em _app.tsx deixar com esta estrutura

```
import { AppProps } from 'next/app'

function MyApp({ Component, pageProps }: AppProps) {
  return <Component {...pageProps} />
}

export default MyApp
```

para trabalhar com o statuses
```yarn add sass```