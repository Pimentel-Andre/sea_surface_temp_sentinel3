## Uso do Sentinel 3 para obtenção de temperatura da superfície da água  

![image](https://github.com/user-attachments/assets/12877285-1b9f-44b9-b95e-060b972aace1)

Este repositório contém um fluxo de trabalho para processamento de dados do satélite Sentinel-3 (sensor SLSTR) visando a extração e conversão da temperatura da superfície da água (SST) de Kelvin para Celsius  

**Etapas principais**  
- Leitura do arquivo NetCDF (.nc) com dados SST da missão Sentinel-3.  
 
- Recorte espacial para limitar a análise a uma região de interesse (ROI).  

- Conversão da temperatura de Kelvin para Celsius, respeitando os metadados scale_factor, add_offset e _FillValue.  
  
- Salvamento do resultado em um novo arquivo NetCDF, mantendo a estrutura e os atributos originais.

__________________________________________________________________________________________________________

Importante: Para acesso à coleção disponibilizada pelo portal EUMETSAT, você precisa fazer o registro em: 
https://user.eumetsat.int/cas/login  

Com isso, deve obter o API key: https://api.eumetsat.int/api-key/

Para substituir conforme indicado em documentação: https://usc.tools.eumetsat.int/docs/eumdac/v3.0.0/eumdac.html
