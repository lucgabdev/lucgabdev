<div align="center">

# Lucas Gabriel

**Desenvolvedor full stack · front end e back end**

Produtos web em TypeScript e sites para negócios locais.<br>
Anápolis, GO · Engenharia de Software na UniEVANGÉLICA

<br>

[![Portfólio](https://img.shields.io/badge/Portf%C3%B3lio-lucgabdev.vercel.app-111111?style=for-the-badge&logo=vercel&logoColor=white&cacheSeconds=86400)](https://lucgabdev.vercel.app)
[![Clientry](https://img.shields.io/badge/Clientry-SaaS_de_agenda-1E3A8A?style=for-the-badge&logo=nextdotjs&logoColor=white&cacheSeconds=86400)](https://clientry.com.br)
[![Instagram](https://img.shields.io/badge/Instagram-lucwp__-E4405F?style=for-the-badge&logo=instagram&logoColor=white&cacheSeconds=86400)](https://www.instagram.com/lucwp__/)

</div>

---

## Sobre

Trabalho do banco de dados à interface. Hoje meu foco está em duas frentes: SaaS para pequenos negócios de serviço e sites que trazem cliente pelo WhatsApp e pelo Google para o comércio da minha região.

Gosto de projeto que chega em produção com teste, regra de negócio no servidor e cuidado com o dado de quem usa. A maior parte do código fica em repositórios privados porque é produto comercial ou trabalho de cliente; abaixo está o que cada um faz e como foi construído.

## Experiência

| Função | Foco |
| --- | --- |
| Auxiliar de programação | Desenvolvimento e manutenção de software |
| Auxiliar administrativo | Rotinas administrativas e apoio à operação |

## Projetos em destaque

<table>
<tr>
<td width="50%" valign="top">

### [Clientry](https://clientry.com.br)
SaaS de agenda, clientes e pagamentos para barbearias, salões, estúdios e clínicas.

- Multi-tenant: toda consulta é filtrada pela organização no serviço, nunca na tela
- Agendamento público, CRM, financeiro, automações por cron e cobrança de planos via Mercado Pago, com tokens dos negócios cifrados
- Login por senha (scrypt) ou código por e-mail, com dispositivos confiáveis
- Conta de demonstração isolada por visitante e removida automaticamente

`Next.js 16` `React 19` `TypeScript` `Drizzle` `PostgreSQL` `Zod` `Vitest` `Playwright`

<sub>Código privado · produto comercial</sub>

</td>
<td width="50%" valign="top">

### KindUP
Plataforma de doações que liga doadores a instituições, com três perfis: doador, instituição e administração.

- Fluxo da doação como máquina de estados, da confirmação à entrega
- Verificação de instituições, moderação, denúncias e trilha de auditoria
- Sessões com token guardado só como hash, rate limit persistido no banco e validação de upload pela assinatura do arquivo
- LGPD: exportação dos próprios dados e exclusão com anonimização

`Next.js 15` `TypeScript` `Prisma` `PostgreSQL` `Zod` `Recharts` `Vitest`

<sub>Código privado · projeto acadêmico</sub>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [Fallen Pantera Pro V2](https://fallen-pantera.vercel.app)
Página de produto e filme de 45 s para um headset gamer, num monorepo que compartilha o mesmo kit de marca entre os dois.

- Vista explodida interativa, diagrama polar dos microfones e visualizador de crosstalk em canvas
- Filme em Remotion a 1080p/60 fps, com roteiro e linha do tempo versionados em JSON
- Respeita `prefers-reduced-motion`

`React 19` `Tailwind CSS 4` `Framer Motion` `Remotion` `npm workspaces`

</td>
</tr>
</table>

## Sites para negócios

Landing pages e catálogos pensados primeiro para o celular, com conversão pelo WhatsApp.

| Projeto | Segmento |
| --- | --- |
| [Oben Place](https://oben-place.vercel.app) | Hamburgueria em Anápolis, com cardápio e pedidos online |
| [Mel Nativo](https://mel-jatai.vercel.app) | Loja e guia de méis de abelhas nativas |
| [Mahi 3D Printing](https://mahi-printing.vercel.app) | Impressão 3D sob medida (EUA) |
| [Valim Impressões 3D](https://valim-impress-es.vercel.app) | Impressão 3D em Goiás, com orçamento pelo WhatsApp |
| [Chaveiro City](https://chaveirocity.vercel.app) | Chaveiro residencial, comercial e automotivo |
| [Globo Materiais](https://globomateletricos.vercel.app) | Materiais elétricos e hidráulicos em Anápolis |
| [CraftGuess](https://fast-vega-cpqi9w3.vercel.app) | Web app de quiz sobre Minecraft, com modos, ranking e conquistas |

## Stack

**Frontend**<br>
<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,vite,html,css&perline=8" alt="TypeScript, JavaScript, React, Next.js, Tailwind CSS, Vite, HTML, CSS" />

**Backend e dados**<br>
<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,prisma,java,spring&perline=8" alt="Node.js, Express, PostgreSQL, Prisma, Java, Spring" />

**Infra e ferramentas**<br>
<img src="https://skillicons.dev/icons?i=git,github,vercel,netlify,figma,vscode,linux&perline=8" alt="Git, GitHub, Vercel, Netlify, Figma, VS Code, Linux" />

**Sistemas**<br>
<img src="https://skillicons.dev/icons?i=c&perline=8" alt="C" />

![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logoColor=white&cacheSeconds=86400)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Remotion](https://img.shields.io/badge/Remotion-0B84F3?style=flat-square&logo=remotion&logoColor=white&cacheSeconds=86400)

## Como eu trabalho

- **Regra de negócio no servidor.** Ações e rotas são finas; permissão e validação ficam nos serviços, que são testados diretamente.
- **Tipos e validação de ponta a ponta.** TypeScript estrito e Zod em toda entrada que vem do usuário.
- **Teste antes de publicar.** Vitest para domínio e integração contra Postgres real, Playwright para os fluxos principais.
- **Segurança e privacidade por padrão.** Hash de senha e de sessão, rate limit, cabeçalhos de segurança e LGPD tratada no modelo de dados.
- **Acessível e leve.** Mobile first, contraste e foco visíveis, `prefers-reduced-motion` respeitado.
- **Nada inventado.** Preço, depoimento, horário ou número de cliente só entra no site se for real e confirmado.

## Contato

Orçamentos, parcerias e projetos: pelo [portfólio](https://lucgabdev.vercel.app) ou no Discord **@lucgabdev**.
