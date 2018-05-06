# Instruções de instalação para o workshop


### Gerenciador de pacotes: Anaconda

É altamente recomendado usar o Anaconda. O download pode ser feito no endereço:
[https://www.anaconda.com/download/](https://www.anaconda.com/download/)

Ele vem com o `jupyter notebook` que é a IDE que usaremos para o workshop

Recomendamos usar o Python 3.5.

### Pacotes necessários

Rode o seguinte script no prompt de comando para verificar se você tem todos os pacotes necessários instalados.
Para rodar, execute o seguinte comando do prompt de comando:

```sh
$ python check_env.py
```

A saída indicará se qualquer uma das bibliotecas estão faltando ou precisam ser atualizadas.

Qualquer pacote faltante pode ser instalado rodando o seguinte comando no prompt de comando:


```sh
$ pip install <package_name> 
```

Qualquer pacote desatualizado pode ser atualizado rodando o seguinte comando no prompt de comando:

```sh
$ pip install --upgrade <package_name> 
```

Substitua <*package_name*> pelo pacote que precisa ser instalado/atualizado. 

