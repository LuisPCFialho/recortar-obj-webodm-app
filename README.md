# Recortar OBJ — distribuição

Este repositório distribui o executável da ferramenta. O código está em
[recortar-obj-webodm](https://github.com/LuisPCFialho/recortar-obj-webodm).

## Instalar

O executável é publicado em **Releases** (um ficheiro de 122 MB excede o
limite de 100 MB por ficheiro do GitHub, por isso não pode ser um ficheiro
normal do repositório).

Descarregar `RecortarOBJ_WebODM.exe` da Release mais recente, pousar numa
pasta local e fazer duplo clique.

## Atualizações automáticas

O executável verifica no arranque se existe uma versão mais recente e
atualiza-se sozinho. O canal de atualização é configurado com:

```
RecortarOBJ_WebODM.exe --canal "<pasta ou repo>"
```

A configuração fica guardada e não é preciso repeti-la.

## Versões

Ver a página de Releases. Cada Release traz o `versao.json` com a versão,
a data e o SHA-256 do executável, que é verificado antes de qualquer troca.
