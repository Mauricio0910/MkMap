# MarketMap — versão evoluída

Principais evoluções desta versão:

- Nova aba Inteligência Comercial.
- Nova aba Instagram para captação assistida por @ ou link de perfil.
- Novos campos em empresas: segmento, Instagram, prioridade, próxima ação, data da próxima ação e observações.
- Ranking de concorrentes, cidades, segmentos e produção por consultor.
- Lista de oportunidades prioritárias e próximas ações da semana.
- Service Worker atualizado para reduzir problema de cache antigo.
- Headers ajustados para permitir geolocalização do botão Minha região.

Importante:

1. A coleção principal continua sendo `companies`. A atualização é aditiva e não apaga registros existentes.
2. Para não pedir a chave do Google Maps em cada máquina, abra `index.html` e cole a chave na linha:

   const GOOGLE_MAPS_API_KEY = "";

3. A aba Instagram desta versão é captação assistida. Ela não raspa dados do Instagram e não usa API oficial da Meta ainda.
4. Para integração automática oficial com Meta/Instagram, será necessário backend seguro, app Meta Developer, permissões e token fora do HTML.
5. Depois de publicar, faça Ctrl+F5 no desktop ou limpe cache no celular se a versão antiga continuar aparecendo.
