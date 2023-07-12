# Trabalho de Conclusão de Curso - Escola da Nuvem.
## Projeto Website para Divulgação de Currículo com HTML, CSS e Javascript. 

## Objetivo

Desenvolvimento de um website (html, css, javascript) contendo os currículos do grupo e a implantação de um ou mais serviços na nuvem AWS, com **rede de entrega de conteúdo, com baixa latência, com segurança, e armazenamento durável**, para atender a demanda de 11 milhões de requisições por mês. 

## Serviços da AWS usados

- Simple Storage Service - Amazon S3 -- Serviço de armazenamento de objetos construído para armazenar e recuperar qualquer volume de dados de qualquer local.
  
- Bucket -- Baude onde vamos colocar os objetos e que é virtualmente infinito para armazenamento de objetos.
  
- Amazon CloudFront -- Serviço de entrega de conteúdo (CDN) que entrega dados, vídeos, aplicativo e API’s com segurança, baixa latência e alta velocidade. 


## Arquitetura 

![arquitetura-projeto-website](https://github.com/Wlisses-Silva/Escola-da-Nuvem-TCC/assets/104795256/a2ade54c-baae-49c7-ac80-529e0e009145)

Aqui basicamente o usuário acesso através do link do site e chega no **CloudFront** o próporio busca e os arquivos no **BicketS3** que retorna para o usuário. 

