Esse repositório contem um arquivo yaml que possibilita criar uma instância ec2 via cloudformation , usando o console da aws.

ao acessar a stack cloudformation a AWS e subir o arquivo ec2_v2.yaml , iniciará o processo de criar uma máquina ec2, pedindo dois parametros como entrada.

1º o número do seu IP privado, seguido de /32 para que o seu ip consiga acessar a máquina ec2 via ssh
2° informar um nome para definição do security group que será criado via script