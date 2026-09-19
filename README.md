# Site Empresa Sem Esforço

Landing page estática servida por Nginx em um container Docker.

## Executar

```bash
docker build -t site-empresem-sem-esforco .
docker run --rm -p 8080:80 site-empresem-sem-esforco
```

Abra `http://localhost:8080`.

## Estrutura

- `index.html`: landing page
- `assets/`: imagens e logos usados pela página
- `Dockerfile`: imagem de produção baseada em Nginx Alpine
