# occ_assets_analysis
Exporta um arquivo .json com a árvore dos componentes utilizados nas páginas e um arquivo com a lista de assets não usados nas páginas.

## Para montar árvore em json:
- Adicione os assets na pasta occ_assets;
- Execute as notas - Get diretory, Build component tree e Export asset component tree in json;

#### exemplo de exportação
``` json
{ "pagina_name.json" :{
    "address": "endereço da pagina",
    "title": "titulo da pagina",
    "COMPONENTS":{
      "nome_do_componente":{
        "type": "nome do componente js",
        "COMPONENTS": {}
      },
      
    }
  }
}
```

## Para montar lista de assets não utilizados:
- Adicione os assets na pasta occ_assets;
- Execute todas as notas;

#### exemplo de exportação
``` json
{ "components" :["componente_nao_usado"] }
```
