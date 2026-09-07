# 🏗️ Kit do Arquiteto de Agentes

Sete modelos preenchíveis que viram a **especificação de um agente de IA numa página**, mais o prompt de ensaio simulado para testar a especificação num chat de IA antes de qualquer construção. Kit de trabalho derivado do curso [Arquiteto de Trabalho com IA](https://inematds.github.io/pffia/) (INEMA.CLUB PRO).

## 📖 Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/kit-arquiteto-agentes/guia/**

## Usar

App: **https://inematds.github.io/kit-arquiteto-agentes/** (página única, sem instalação, tudo salva no seu navegador).

Os sete blocos:

1. Processo e resultado
2. Mapa de seis elos (entrada, decisão, ação, verificação, exceção, resultado)
3. Pedido de longo horizonte (objetivo, contexto, restrições, critério, aprovação)
4. Cadeia de orquestração (coordenador, especialistas, ferramentas, sistemas, verificação)
5. Inventário de contexto (o que é, onde está, formato, acessível, dono)
6. Ficha de qualidade (condições com faixa, parar, chamar, bateria de casos)
7. Matriz de permissões (ler, escrever, alterar, enviar, comprar, apagar, aprovar + dados fora do alcance)

Presets por área (botão "carregar exemplo por área"): **vendas** (reativação de clientes), **saúde** (confirmação de consultas e glosas de convênio), **contábil** (cobrança de documentos e obrigações) e **advocacia** (controle de prazos). Ao carregar, a área fica marcada e o kit passa a apontar lacunas específicas dela: dado de paciente fora do alcance na saúde, "quem lança não aprova" no contábil, prazo sempre chamando humano na advocacia.

Cadernos de profissão que usam esses presets: [saúde](https://inematds.github.io/arquiteto-agentes-saude/) · [contábil e financeiro](https://inematds.github.io/arquiteto-agentes-contabil/) · [advocacia](https://inematds.github.io/arquiteto-agentes-advocacia/).

Saídas: especificação em uma página (copiar, imprimir/PDF, baixar `.md`), lista de lacunas detectadas, prompt de ensaio simulado, exportar/importar `.json`.

## Estrutura

- `index.html` — o app (HTML + CSS + JS, self-contained)
- `guia/index.html` — landing + guia de uso
- `capa/capa.png` — capa oficial 1280×720
