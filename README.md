# Compra Certa — Android MVP

Stack: Kotlin, Jetpack Compose, Room/SQLite e reconhecimento de voz Android.

## Abrir
1. Android Studio > Open > selecione a pasta `CompraCerta`.
2. Aguarde o Gradle sincronizar.
3. Execute em Android 8+ (API 26+), preferencialmente aparelho físico para testar microfone.

## Arquitetura do MVP
- Lista genérica organizada por setor.
- Orçamento e total da compra.
- Room para dados locais e memória de preços.
- Normalização R$/kg, R$/L e R$/un.
- Confirmação antes de gravar compras.
- Entrada por voz via Android.

## Próxima implementação
- CRUD de listas/estabelecimentos/orçamento.
- Catálogo genérico e setores.
- Parser local pt-BR para comandos de voz.
- Comparador de duas ou mais embalagens.
- Favoritos, repetir lista e projeção por histórico.
