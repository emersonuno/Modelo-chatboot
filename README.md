	entrada = input()


def descrever_recurso(recurso):
    if recurso == "Ambiente Conda":
        return "Espaço isolado para armazenar pacotes e dependências do projeto"
    elif recurso == "Docker":
        return "Containerização para garantir replicabilidade do ambiente"
    elif recurso == "Compute Instance":
        return "Máquina virtual dedicada para experimentação e desenvolvimento"
    elif recurso == "Inference Cluster":
        return "Infraestrutura escalável para implantação de modelos em produção"
    else:
        return "Recurso inválido"


print(descrever_recurso(entrada))
