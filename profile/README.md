# Ceris

A Ceris desenvolve soluções para organizar alimentos, planejar compras e reduzir o desperdício. Nosso ecossistema une um aplicativo para o dia a dia das pessoas a uma plataforma web que apoia empresas com gestão de filiais e análise de dados.

## Para quem usa o aplicativo

O **Ceris para Android** ajuda a acompanhar os alimentos da geladeira, do freezer e da despensa, controlar validades e organizar listas de compras. O cadastro pode ser feito por código de barras ou leitura de notas fiscais, e o assistente com IA auxilia com dúvidas sobre o estoque, receitas e planejamento de compras.

## Para empresas

A **plataforma empresarial Ceris** reúne gestão de filiais, dashboards e relatórios mensais sobre estoque, validade e desperdício. Com análises por região e período e um assistente de Business Intelligence com IA, as empresas podem interpretar os indicadores e apoiar suas decisões com dados da plataforma.

## Conheça os repositórios

Ceris é o nome atual da empresa e de seus produtos. Alguns repositórios ainda usam NexUs, o nome anterior da empresa.

| Repositório | Responsabilidade | Principais tecnologias |
| --- | --- | --- |
| [Ceris-Mobile](https://github.com/NexUs-ofc/Ceris-Mobile) | Aplicativo Android: estoque, validades, listas, receitas e assistente. | Kotlin, Android Views/XML, Retrofit, ML Kit |
| [NexUs-Web](https://github.com/NexUs-ofc/NexUs-Web) | Portal empresarial com dashboards, relatórios e gestão de filiais. | React, TypeScript, Vite |
| [NexUs-Core](https://github.com/NexUs-ofc/NexUs-Core) | API central de perfis, estoque, consumo, descarte, lojas e listas de compras. | Java 17, Spring Boot, PostgreSQL, MongoDB, Redis |
| [NexUs-Auth](https://github.com/NexUs-ofc/NexUs-Auth) | Cadastro, login, autenticação Google, recuperação de senha e emissão de tokens. | Java 17, Spring Boot, Spring Security, JWT |
| [NexUs-AI](https://github.com/NexUs-ofc/NexUs-AI) | Assistente sobre estoque, receitas e compras, além da leitura de notas fiscais. | Python, FastAPI, LangChain, LangGraph |
| [NexUs-Notify](https://github.com/NexUs-ofc/NexUs-Notify) | Avisos de validade, eventos e compras, sugestões de lojas e envio de notificações push. | Java 17, Spring Boot, MongoDB, Firebase Cloud Messaging |
| [NexUs-DB](https://github.com/NexUs-ofc/NexUs-DB) | Modelagem, migrations, cargas de dados e pipeline de BI. | PostgreSQL, MongoDB, Python, Flyway, Databricks |
| [NexUs-BI-AI](https://github.com/NexUs-ofc/NexUs-BI-AI) | Dados para dashboards, relatórios mensais em PDF e chatbot de BI. | Python, FastAPI, LangChain, Gemini, Databricks |
| [NexUs-ADMPanel](https://github.com/NexUs-ofc/NexUs-ADMPanel) | Painel de monitoramento das APIs e dos serviços de IA. | React, TypeScript, Vite, Recharts |
| [WebApp-1ano](https://github.com/NexUs-ofc/WebApp-1ano) | Aplicação web com páginas institucionais e cadastros administrativos. | Java 21, Servlets, JSP, PostgreSQL |

Os detalhes de configuração, execução e integração estão nos respectivos repositórios.
