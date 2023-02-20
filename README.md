# Clonar o projeto
https://github.com/EliasFernandes03/Vite-Three.git

# Instalar as dependencias
npm install

# Criar a imagem
docker build -t react-app . 

# Rodar o Container
docker run -d --rm -p 5173:5173 react-app

# Acessar a seguinte rota
http://localhost:5173

## Consideracoes
Projeto ainda se encotra com um problema de Page reload, onde as  novas modificacoes carregam em baixo da modificacao antiga