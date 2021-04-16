# Localizando tnsnames.ora

**O que é o tnsnames.ora?**

É um arquivo de configuração que serve para armazenar os dados de conexão, como por exemplo: host, protocolo, server e etc dando a possibilidade ao cliente de se conectar ao servidor.

**Como encontrá-lo?**

Acesse o prompt de comando do seu sistema operacional teclando *windows + R* e digite *cmd*, após isso, tecle ENTER: 

![cmd](https://github.com/Hellemos/localiza-tnsnames.ora/blob/main/cmd.png)

Com o prompt de comando aberto digite: *tnsping nome_da_base*

![tnsping](https://github.com/Hellemos/localiza-tnsnames.ora/blob/main/tnsping.png)

Em seguida tecle ENTER

![tnspingorcl](https://github.com/Hellemos/localiza-tnsnames.ora/blob/main/tnspingorcl.png)

O caminho pode mudar de acordo com cada máquina, para o meu caso, o arquivo *tnsnames.ora* se encontra em:

### *C:\app\Hellen\product\11.2.0\dbhome_1\network\admin\sqlnet.ora*

Vá até o diretório indicado ou então copie o caminho até "admin" e cole no Explorador de arquivos

        C:\app\Hellen\product\11.2.0\dbhome_1\network\admin\

![exp](https://github.com/Hellemos/localiza-tnsnames.ora/blob/main/exp.png)
