---
name: public-apis
description: Catálogo de ~2.270 APIs públicas e gratuitas (lista public-apis/public-apis), organizadas por categoria, com indicação de autenticação, HTTPS e CORS. Use quando o usuário pedir uma API pública ou gratuita, perguntar "tem alguma API para X", ou quando uma funcionalidade puder usar dados externos (CEP, clima, mapas, feriados, moedas, etc.).
license: MIT (lista original em LICENSE)
---

# Public APIs

O catálogo completo está em `apis.md`, ao lado deste arquivo (cópia de https://github.com/public-apis/public-apis). Ele é grande: não leia inteiro; procure nele com grep.

- Por palavra-chave: `grep -i "clima\|weather" <skill-dir>/apis.md`
- Por categoria: os títulos são `### <Categoria>` (ex.: `### Weather`, `### Geocoding`, `### Government`). Liste com `grep -n '^### ' <skill-dir>/apis.md`.
- Cada linha da tabela é: `| [Nome](link) | Descrição | Auth | HTTPS | CORS |`. `Auth` = `No` significa que não precisa de chave.

Ao recomendar:
- Prefira APIs com `Auth` = `No` ou `apiKey` gratuita, `HTTPS` = `Yes`.
- A lista não garante que a API ainda funcione: confirme no site da API antes de integrar.
- Para o Brasil, procure também por "Brazil" (ex.: BrasilAPI, IBGE, ViaCEP).
