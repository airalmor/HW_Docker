Создание образа

#
 docker image build .
 
В ответ вернется <ID IMAGE>
 
 Создание контейнра
 
 docker run -d -p 8003:8003 --name stocks-products <ID IMAGE>
 
 В ответ вернется <ID Container>
 
 Проверить работоспособность можно в request-exemples
 


