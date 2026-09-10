MARKETMAP - DUAS VERSOES

Este pacote contém duas versões independentes do MarketMap:

1) /desktop
Versão para computador/notebook.
Indicada para análise gerencial, relatórios 360, filtros e uso com tela maior.
Arquivo principal: desktop/index.html

2) /smartphone
Versão otimizada para celular.
Indicada para consultores em campo, registro rápido de checkpoint, GPS e cadastro pelo smartphone.
Arquivo principal: smartphone/index.html

As duas versões usam a mesma estrutura Firebase:
- companies
- checkpoints

Portanto, os dados registrados no celular poderão aparecer no relatório da versão desktop, desde que ambas estejam usando o mesmo firebaseConfig.

ATENÇÃO PARA PUBLICAÇÃO:
Se publicar em um único site GitHub Pages, você pode manter as duas pastas:
- https://seuusuario.github.io/seurepo/desktop/
- https://seuusuario.github.io/seurepo/smartphone/

Se quiser que a versão desktop seja a página principal, copie desktop/index.html para a raiz como index.html.
Se quiser que a versão smartphone seja a página principal, copie smartphone/index.html para a raiz como index.html.

Não coloque dois arquivos index.html diferentes na mesma pasta raiz, pois um substituirá o outro.

Após publicar, limpe cache ou use Ctrl+F5 para evitar que o navegador carregue versão antiga.
