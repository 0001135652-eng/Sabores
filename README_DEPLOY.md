# Guia de Hospedagem - Projeto Sabores

Este projeto foi desenvolvido utilizando **PHP** e **MySQL**, o que significa que ele requer um servidor com suporte a processamento back-end para funcionar corretamente.

## Por que não funciona no GitHub Pages?

O **GitHub Pages** suporta apenas arquivos **estáticos** (HTML, CSS, JS). Ele não executa código PHP nem se conecta a bancos de dados. Por isso, ao tentar acessar o site pelo GitHub Pages, você verá o código fonte do arquivo ou um erro 404.

## Onde hospedar este projeto?

Para que o sistema de login e as receitas funcionem, você deve hospedar em serviços que suportem PHP e MySQL. Aqui estão algumas opções:

### 1. Opções Gratuitas
*   **[InfinityFree](https://www.infinityfree.net/)**: Oferece PHP e MySQL gratuitamente com painel de controle.
*   **[000webhost](https://000webhost.com/)**: Muito popular para estudantes, permite hospedar projetos PHP de forma simples.

### 2. Opções Profissionais / Nuvem
*   **[Render](https://render.com/)**: Você pode usar um Dockerfile para rodar seu PHP.
*   **[DigitalOcean](https://www.digitalocean.com/)**: Requer configuração de servidor (VPS), mas é extremamente robusto.

## Como configurar em um servidor PHP (Ex: InfinityFree/XAMPP)

1.  Suba todo o conteúdo da pasta `htdocs` para a pasta pública do servidor (geralmente `public_html` ou `htdocs`).
2.  Importe o banco de dados `saboresdb` usando o arquivo SQL (se houver) ou crie as tabelas manualmente.
3.  Edite o arquivo `htdocs/config/database.php` com as credenciais fornecidas pelo seu host (Host, DB Name, User, Password).

---
*Este arquivo foi gerado para ajudar na compreensão das limitações de deploy estático.*
