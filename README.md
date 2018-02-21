# victory-api-example
Exemplo de como usar o Victory para testar uma API REST

## Passo a passo
git clone https://github.com/alexgarzao/victory-api-example.git
cd victory-api-example

cd api
virtualenv -p python3.6 .env
source .env/bin/activate
pip install -r requirements.txt
make run

Em outro terminal...

Baixa o victory
"Aponta" para o diretorio onde esta os features
