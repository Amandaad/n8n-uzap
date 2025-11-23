#Docker 
Deploy no #Docker
**GitHub:**

###Criei uma automação não nativa Uzap envio de mensagem automática.###
Http Request Importar o codigo indepoint.

Endepoint 

**Uzap:**
{
curl --location -g '{{endpoint}}/sendText' \
--header 'content-type: application/json' \
--header 'sessionkey: {{sessionkey}}' \
--data '{
    "session": "{{session}}",
    "number": "5521989848442",
    "text": "Testando envio de texto."
}'
