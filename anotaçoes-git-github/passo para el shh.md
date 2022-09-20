# Anotaçoes de passo a passo de shh do github
en el bash colocamos estos comandos
-1.>ssh-keygen -t ed25519 -c (el email)
as chaves publica são .pub
-2.>cat (endereço da chave publica)
despues de colocar todo en el github
-3.>eval $(ssh-agent -s)
-4.>ssh-add (endereço da chave privada)
