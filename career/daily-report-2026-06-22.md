# Relatorio inicial de vagas - 2026-06-22

Primeira busca manual para validar o fluxo do assistente diario de vagas.

## Fontes testadas

- Remotive API: funcionou.
- RemoteOK HTML/JSON: funcionou, mas com bastante ruido de tags.
- Arbeitnow API: funcionou, mas os resultados iniciais vieram majoritariamente fora do alvo e fora do remoto Brasil/global.
- Remotar via HTML publico: acessivel, mas a pagina retornou "nao encontramos vagas" no snapshot consultado.
- LinkedIn, Gupy, Greenhouse e Lever: devem entrar na automacao por busca web/link direto; algumas paginas podem exigir login, JavaScript ou validacao manual.

## Top matches encontrados

| Score | Fonte | Empresa | Vaga | Localidade | Acao |
| --- | --- | --- | --- | --- | --- |
| 79 | RemoteOK | AGGRANDIZE | Desenvolvedor Front end Junior | Pelotas, RS, Brasil | Abrir e confirmar remoto real antes de aplicar |
| 59 | Remotive | Quinncia Inc | Frontend Developer | Worldwide | Conferir senioridade e ingles |
| 49 | RemoteOK | Nexmuv Tecnologia | Desenvolvedor Frontend | Mariana, MG, Brasil | Conferir remoto e requisitos |
| 46 | RemoteOK | ZYPHRA TECH | Front End Developer Fresher | Greater Visakhapatnam Area | Baixa prioridade; validar se aceita global |
| 67 | RemoteOK | GamblingCareers.com | Frontend Engineer | Toronto | Baixa prioridade; validar se aceita Brasil/LATAM |

## Vagas rejeitadas pelo criterio

- LawnStarter - Staff/Product Engineer: stack e Brasil batem, mas senioridade Staff foge do alvo Jr/Pleno.
- Resultados de marketing, RH, suporte, video, dados ou assistente executivo: rejeitar mesmo quando aparecem por tags de frontend.

## Ajuste de score recomendado

O score diario deve penalizar fortemente termos como `Staff`, `Principal`, `Lead`, `Manager`, `Senior 5+ anos`, vagas presenciais, vagas fora de Brasil/LATAM/Worldwide e resultados que so tenham frontend em tags genericas.

## Proximas acoes

1. Revisar manualmente AGGRANDIZE e Quinncia.
2. Preparar mensagem personalizada apenas depois de confirmar remoto e requisitos completos.
3. Usar o tracker para evitar repetir vagas nos proximos dias.
