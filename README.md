<div align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original-wordmark.svg"  title="Jupyter Lab" alt="Jupyter" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg"  title="Python" alt="Python" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/selenium/selenium-original.svg"  title="Selenium" alt="Selenium" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/plotly/plotly-original.svg"  title="Plotly" alt="Selenium" width="40" height="40"/>
  
  <h1>Projeto de análise de dados, desde o web scraping até a publicação on-line dos resultados.<h1>
</div>

💡 Primeiramente precisei extrair os dados do site em questão, usando Python e técnicas de web scraping,<br>
já que o site carrega os dados dinamicamente, não tinha como pegar todos os dados num só comando.<br>
<br>
✅ Métodos implementados:<br>
<br>
1. Requests com Paginação: Tenta diferentes formatos de URL de paginação;<br>
2. Requisições AJAX: Intercepta e testa endpoints AJAX que podem retornar todos os dados;<br>
3. Selenium: Simula um navegador real para lidar com JavaScript e conteúdo dinâmico.<br>
<br>
✅ O Selenium conseguiu simular um navegador real e:<br>
<br>
1. Executou o JavaScript necessário para carregar os dados;<br>
2. Fez scroll automático ou clicou nos botões de paginação;<br>
3. Aguardou o conteúdo carregar completamente.<br>
<br>
✅ Algumas dicas para próximas extrações:<br>
<br>
- O método Selenium é mais lento mas mais confiável para sites dinâmicos;<br>
- É possível ajustar os delays (time.sleep()) se o site for muito lento;<br>
- O arquivo CSV está pronto para análises com pandas, Excel, etc.<br>
<br>
🎯 Principais funcionalidades:<br>
1. Gráfico Matplotlib (estático).<br>
<br>
- Linhas coloridas para cada veículo;<br>
- Eixo X com anos, Y com emplacamentos;<br>
- Formatação automática (1M, 100k, etc.);<br>
- Top 10 veículos por padrão;<br>
<br>
2. Gráfico Plotly (interativo).<br>
<br>
- Zoom, hover, pan;<br>
- Tooltip com detalhes;<br>
- Mais profissional e interativo;<br>
<br>
3. Análise automática.<br>
<br>
- Identifica colunas de anos automaticamente;<br>
- Calcula tendências e crescimento;<br>
- Mostra picos e estatísticas;<br>
<br>
<br>
📊 Após o trabalho de scraping e análise de dados no JupyterLab, utilizei a IA Claude.ai para criar<br>
o código html/css/js do site interativo.<br>
<br>

https://cwbads22.github.io/carros_da/
