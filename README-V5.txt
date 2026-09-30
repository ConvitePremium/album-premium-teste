ENGINE ÁLBUM PREMIUM V5

Novidades:
- Contador consulta o total real do evento no Supabase sem baixar todas as fotos.
- Paginação automática: 12 fotos por lote, carregadas conforme a rolagem.
- Novos uploads geram thumbnail 360x640 em eventoId/thumbs/.
- Galeria e faixa superior tentam usar a thumbnail; fotos antigas sem thumbnail usam o arquivo original automaticamente.
- Upload com estados “Preparando…” e “Enviando…”, barra visual e bloqueio contra clique duplo.
- Em falha de internet/upload, a foto permanece no editor e o usuário pode tentar novamente.
- Após publicar, aparece confirmação com “Compartilhar minha foto” e “Voltar ao álbum”.
- Mantidos: câmera/fotos separadas, 1 dedo rola página, 2 dedos movem/pinçam a foto, Realtime e moldura.

IMPORTANTE:
Não é preciso alterar a tabela fotos para esta V5. A thumbnail é inferida pelo caminho do arquivo.
Fotos antigas continuam funcionando; apenas não terão a economia de thumbnail até serem reenviadas/geradas.
