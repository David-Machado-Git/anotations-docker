
DOCKER HUB É UM LOCAL QUE POSSUI VÁRIAS IMAGENS DO DOCKER QUE SÃO DISPONIBILIZADAS PELA COMUNIDADE.


PRINCIPAIS COMANDO DO DOCKER (baixar e/ou instalar)


para poder ter acesso a todos os comandos do docker => (digitar comando): docker

baixar imagem do docker hub para minha máquina => (digitar comando): docker pull + nome da imagem no docker hub

listar todas as imagens que estão em meu computador/docker => (digitar comando): docker images

gerar imagem's no docker => (digitar comando): docker build

remover imagem's que estão em meu computador/docker => (digitar comando): docker rmi + nome da imagem


GERENCIANDO CONTAINERS

listar os container's que estão rodando ou parados => (digitar comando): docker ps

OBS: Comando run pega a imagem que vc quer, instancia e inicializa um container. Sobre os comandos em geral, cada comando pode ter um universo de possibilidades e parâmetros ou flags pra fazer determinada situação.

criar um container  => (digitar comando): create docker

iniciar um container  => (digitar comando): docker run 

pausar um container  => (digitar comando): docker pause

rodar um container  => (digitar comando): docker start

parar um container => (digitar comando): docker stop ou docker kill - a diferença entre um docker stop e docker kill é que: stop vai tentar salvar e finalizar as coisas da forma correta e o kill vai interromper tudo de imediato. recomendado stop.

remover um container  => (digitar comando): docker rm (lembrando que pra remover o container tem que estar parado).