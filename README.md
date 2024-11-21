# Aplicação para Encurtamento de URL's



## Aplicação desenvolvida no curso gratuito de Java da RocketSeat
O intuito do curso era criar uma aplicação backend java serverless.

Foram utilizados as tecnologias Lambda, E3 e API Gateway da AWS.

### Arquitetura

![image](https://github.com/user-attachments/assets/47c39656-02da-4c80-a7c2-af3b1f971761)



### EndPoints


* A aplicação esta hospedada no seguinte URL: [Link Aplicação](https://53y4noyffk.execute-api.sa-east-1.amazonaws.com)

* Para cadastrar um link a ser encurtado, deve ser passado como requisição POST para a URL acima acrescida de um "/create" juntamente com um body JSON como o do exemplo abaixo.

![image](https://github.com/user-attachments/assets/f43fdd79-0ddd-458b-9146-bbbc1b696800)

OriginalUrl: O URL que deseja encurtar.
ExpirationTime: a data de expiração do link desejado em convertida em Timestamp.

[Link para converter data](https://www.epochconverter.com/)

* Após realizar a requisição, será retornado ao usuário o codigo daquele link.


### Para acessar um link previamente encurtado, deve ser colocado no navegador o URL da aplicação acrescido de "/codigo-do-url"

Exemplo: 
![image](https://github.com/user-attachments/assets/8e2bfbe5-4363-4df4-ba36-8ad789959b0f)
