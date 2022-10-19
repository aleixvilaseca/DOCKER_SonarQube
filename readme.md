# Comandos para ejecutar en PowerShell antes de crear los contenedores. 

wsl -d docker-desktop

sysctl -w vm.max_map_count=262144

# Comandos para ejecutar los contenedores

docker-compose up -d

docker ps 

# Abrir en el navegador

http://localhost:9000   

"user y pass por defecto: admin"
