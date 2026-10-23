# Para você — mini livro digital

Livro romântico responsivo, feito em HTML, CSS e JavaScript sem dependências.

## Abrir localmente

Abra index.html em um navegador moderno. Para usar no celular, publique no Vercel e abra o endereço gerado.

## Publicar no Vercel

1. Envie este projeto para um repositório GitHub, GitLab ou Bitbucket.
2. No Vercel, escolha Add New → Project e importe o repositório.
3. Deixe o preset como Other e os campos de build e output directory vazios. O index.html será servido diretamente.
4. Clique em Deploy.

Também é possível usar a Vercel CLI na pasta: vercel para pré-visualização ou vercel --prod para produção.

## Editar o livro

Abra o livro e toque em Editar livro. Toque nos títulos ou textos para editá-los diretamente; Concluir edição termina o modo. Use Adicionar foto a esta página para escolher uma imagem do celular. As opções Substituir e Remover aparecem para uma foto inserida.

O texto inicial e a sequência de páginas ficam no array original, no script no fim de index.html. Edite os campos title, body, ending, eyebrow e subtitle para alterar o conteúdo padrão.

## Salvamento

As alterações e as fotos ficam no armazenamento local do navegador e aparelho usados. Cada leitor poderá personalizar a própria cópia; o deploy público fornece a mesma versão inicial para todos, mas não sincroniza personalizações entre pessoas ou aparelhos. Restaurar recupera o conteúdo inicial neste navegador. As fotos são reduzidas para facilitar o armazenamento local.
