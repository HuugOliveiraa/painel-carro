# Painel do Carro

App pessoal para controlar o carro: abastecimentos, manutenções, despesas e quilometragem.
Funciona como app instalável (PWA), abre sem internet, e os dados ficam salvos só no próprio celular.

**Abrir / instalar:** https://huugoliveiraa.github.io/painel-carro/
No Chrome do Android: ⋮ → *Instalar app*. No iPhone (Safari): Compartilhar → *Adicionar à Tela de Início*.

## Arquivos
- `index.html`: o app completo
- `manifest.json`: nome, cores e ícones do app instalado
- `sw.js`: service worker (cache para uso offline)
- `icons/`: ícones

## Publicar uma atualização
1. Substitua o `index.html`.
2. No `sw.js`, aumente a versão do cache (`painel-carro-v1` → `v2`...).
3. No celular, feche e abra o app duas vezes.

Os dados não são apagados em atualizações. Use **Ajustes → Exportar backup** de vez em quando.
