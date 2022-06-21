# Preparando o Ambiente

## Configuração:

Baseado no conteúdo de nossa aula, realize a instalação e configuração dos pacotes necessários para utilização do `Spark`.

### Instalando Java: 
sudo apt install curl mlocate default-jdk -y


### Instalando Apache Spark:
Ao entrar no [site do Spark](https://spark.apache.org/downloads.html) encontraremos as diversas versões existentes, atualmente esta é a [versão mais atual.](https://www.apache.org/dyn/closer.lua/spark/spark-3.2.0/spark-3.2.0-bin-hadoop3.2.tgz)

### Instalando Hadoop3.2
Uma forma simples de instalação é através do comando `wget` seguido pelo [link](https://dlcdn.apache.org/spark/spark-3.2.0/spark-3.2.0-bin-hadoop3.2.tgz) do site:
 wget https://dlcdn.apache.org/spark/spark-3.2.0/spark-3.2.0-bin-hadoop3.2.tgz
 
Após o download extrair o arquivo .tar e mover para o diretório /opt/spark
 
### Editando o bashrc:
Adicione as seguintes informações ao final do arquivo:
 * export SPARK_HOME=/opt/spark
 * export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin 

Atualiza o Bash no terminal:
source ~/.bashrc


