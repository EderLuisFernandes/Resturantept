## Usa  o prisma com o next 
[x] - npm i prisma --save-dev

## para dizer qual banco eu vou usar como ORM
    #Lembrando que o ultimo é para dizer qual banco 
[x] -  npx prisma init --datasource-provider postgresql
## Para format o prisma
[x] - npx prisma format
########################################################################333


# Logo em seguida eu fui no NeonDb para substituir o docker e criei um sistema para mim

## Vou usar o neon para fazer a migration 
[x] - https://console.neon.tech/app/projects

### Aqui é para criar uma migration
[x] - npx prisma migrate dev --name init_database

# Para popular meu Banco de dados 
vamos usar o seed.ts
[x] -  depois vamos  popular...
[x] - npm i -D ts-node  // para instalar o ts-node


# Deposi um npx prisma db seed