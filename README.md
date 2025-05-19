# Configurando Recursos e Dimensionamentos em VM

- Na Azure, as VMs são servidores na nuvem que podem ser configurados conforme a necessidade do usuário. Isso que dizer que é possível definir a quantidade de processamento, memória, armazenamento e conectividade para atender diferentes aplicações.

- O primeiro passo para criar uma VM é acessar o portal da Azure e iniciar a configuração, escolhendo um sistema operacional (Windows ou Linux), a potência da máquina (quantidade de vCPUs e RAM) e o tipo de armazenamento. A Azure oferece três opções principais de discos: Standard HDD (mais barato e com menor desempenho), Standard SSD (equilíbrio entre custo e velocidade) e Premium SSD (melhor desempenho, indicado para cargas de trabalho mais exigentes).

- Além disso, é possível ativar o dimensionamento automático para que a quantidade de VMs seja ajustada conforme a demanda, garantindo eficiência e controle de custos. Esse ajuste pode ser baseado no uso de CPU/memória ou programado para expandir ou reduzir em determinados horários.

- Na parte de rede, a configuração envolve a escolha de um IP público ou privado, a definição de regras de acesso com Grupos de Segurança de Rede (NSG) e, se necessário, o uso de um Load Balancer para distribuir o tráfego entre várias VMs.
