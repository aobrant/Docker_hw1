Сборка образа

docker image build --tag stockproducts:mine

Запуск контейнера

docker run --name my_stockproducts -d -p 8000:8000 stockproducts:mine