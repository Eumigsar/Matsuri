# LEIA PRIMEIRO — por que “nada mudou”

Se o site não mudou, o GitHub Pages provavelmente ainda está publicando uma versão antiga pelo workflow anterior.

Este pacote é a versão **EXPLORÁVEL V2** e inclui um workflow novo:

```txt
.github/workflows/deploy.yml
```

## O que precisa acontecer

1. Subir **todos** os arquivos deste ZIP, incluindo a pasta oculta `.github`.
2. Fazer commit.
3. Ir em **Actions**.
4. Rodar/aguardar o workflow **Deploy EXPLORABLE V2 to GitHub Pages** ficar verde.
5. Abrir em aba anônima ou dar `Ctrl + F5`.

## Como conferir que o arquivo certo subiu

No GitHub, abra `index.html` e procure por:

```txt
EXPLORÁVEL V2 · avatar + mapa + sifus
```

Se essa frase não estiver no `index.html` do GitHub, você ainda está com o arquivo antigo.

## O que deve aparecer na tela

Uma faixa no topo dizendo:

```txt
EXPLORÁVEL V2 · avatar + mapa + sifus · 2026-06-20
```

Se essa faixa não aparecer, o deploy ainda não pegou a versão nova.
