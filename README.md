- Escolher a url do sub dominio: webrtc.wsclaudio.com
- Apontar subdominio da godaddy para o ip: webrtc.wsclaudio.com -> 64.227.15.157
- Criar os certificados ssl para acesso HTTPS: https://github.com/jsha/minica.git
    - git clone https://github.com/jsha/minica.git 
    - cd minica
    - go build
    - ./minica --domains webrtc.wsclaudio.com

- Substituir os certificados na pasta nginx
- Cotracar o nome server_name para o dominio utilizado para criar o certificado

