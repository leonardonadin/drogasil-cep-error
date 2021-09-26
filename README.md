# drogasil-cep-error

Erro encontrado ao tentar adicionar um CEP no site da Drogasil.

# Retorno
description: "Argument 1 passed to App\\Domain\\DTO\\ShippingDneDTO::setNeighborhoodName() must be of the type string, null given, called in /var/www/html/app/Validation/AddressResponse.php on line 40"
message: "Erro ao tentar buscar o conteudo. Formação de dado incorreta"

# Possível problema
Alguns CEP's não possuem bairro e provavelmente o sistema está aguardando o retorno de um bairro da API de CEP's.

-----------------------------------------------------------------

Erro já foi enviado via atendimento, como cliente espero que seja solucionado.
