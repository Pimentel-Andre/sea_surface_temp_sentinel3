## Uso do Sentinel 3 para obtenção de temperatura da superfície da água  

Este repositório contém um fluxo de trabalho para processamento de dados do satélite Sentinel-3 (sensor SLSTR) visando a extração e conversão da temperatura da superfície da água (SST) de Kelvin para Celsius  

**Etapas principais**  
- Leitura do arquivo NetCDF (.nc) com dados SST da missão Sentinel-3.  
 
- Recorte espacial para limitar a análise a uma região de interesse (ROI).  

- Conversão da temperatura de Kelvin para Celsius, respeitando os metadados scale_factor, add_offset e _FillValue.  
  
- Salvamento do resultado em um novo arquivo NetCDF, mantendo a estrutura e os atributos originais.  