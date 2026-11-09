# Site_mudanca2

Base de um site em Next.js derivada do [AI Website Cloner Template](https://github.com/JCodesMore/ai-website-cloner-template), de JCodesMore.

## Estado atual

A rota inicial ainda exibe a mensagem padrão de configuração do template. O repositório contém a estrutura e as ferramentas iniciais de desenvolvimento. As páginas e os fluxos próprios do site ainda precisam ser definidos.

## Tecnologias e estrutura

- **Next.js 16 (App Router), React 19 e TypeScript** para a base da aplicação.
- **Tailwind CSS 4** e uma base de componentes **shadcn/ui** para a interface.
- [src/app/page.tsx](src/app/page.tsx) contém a página inicial e [src/app/layout.tsx](src/app/layout.tsx) define o layout e os metadados.
- [src/components/ui/](src/components/ui/) contém o componente de botão fornecido pela base.

## Como executar

Use Node.js 24 ou superior, conforme `package.json`. Na raiz:

```bash
npm ci
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000). Use `npm run check` para executar lint, checagem de tipos e build.

## Origem e licença

A base está sob a [licença MIT](LICENSE). Os [READMEs em japonês](README.ja.md) e [chinês](README.zh-CN.md) são referências herdadas do template.
