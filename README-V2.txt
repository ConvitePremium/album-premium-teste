ENGINE ÁLBUM PREMIUM V2

Otimizações desta versão:
- carrega no máximo 24 registros na abertura;
- faixa animada usa apenas as 6 fotos mais recentes;
- imagens usam lazy loading e decodificação assíncrona;
- elementos fora da tela usam content-visibility;
- novas fotos são WebP com qualidade reduzida para ~82%;
- novos uploads recebem cache longo no navegador;
- mantém Realtime, editor, moldura, nome obrigatório, compartilhamento e galeria.

Para testar:
1. Substitua os arquivos do repositório pelos arquivos desta V2.
2. Preserve sua moldura.png, caso já tenha colocado uma moldura própria.
3. Commit.
4. Aguarde o GitHub Pages atualizar.
5. Abra no celular em aba anônima para testar um carregamento realmente frio.

Observação:
Esta V2 reduz bastante o trabalho inicial no celular sem alterar a estrutura do Supabase.
A otimização mais avançada será gerar miniaturas separadas para galerias grandes.
