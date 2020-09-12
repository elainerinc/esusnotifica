# esusnotifica

O pacote R **esusnotifica** inclui a fun��o gen�rica **clean_esus** que executa uma s�rie de instru��es de curadoria dos dados do e-SUS Notifica. 

Adicionalmente, pretende-se que este reposit�rio configure um ambiente colaborativo de desenvolvimento de solu��es computacionais para o trabalho com dados do e-SUS Notifica. Informa��es adiconais est�o dispon�veis em https://osf.io/quvsf/.

## Como instalar?

Este pacote **em desenvolvimento** pode ser instalado no R executando os c�digos abaixo:

```{r}
install.packages("devtools")
devtools::install_github("ronaldoalves-ms/esusnotifica")
```

## Como usar?

A fun��o **clean_esus** � aplicada aos dados do e-SUS Notifica, conforme exemplo a seguir:

```r
library(esusnotifica)
dados_esus <- clean_esus(dados_esus)
```


## D�vidas e sugest�es

Crie uma [issue](https://github.com/ronaldoalves-ms/esusnotifica/issues) no projeto ou envie um e-mail para ronaldo.alves@saude.gov.br
