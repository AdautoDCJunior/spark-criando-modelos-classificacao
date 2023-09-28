![Badge](https://img.shields.io/badge/Status_curso-Finalizado-green)

# Problema ❗

Recebemos a demanda de ajudar o time de marketing a prever se um cliente vai cancelar o serviço ou não, pois eles estão notando um problema com o churn: basicamente, muitos clientes cancelando o serviço.

Para resolver esse problema, a ideia do time de marketing é oferecer promoções para os clientes que provavelmente cancelarão o serviço, procurando evitar esse cancelamento.

# Proposta 🎯

Nossa proposta para esse problema é criar um modelo de machine learning capaz de fazer a classificação entre clientes que vão cancelar o serviço e os que não vão.

Para isso, vamos utilizar uma base de dados fornecida pelo time de marketing contendo informações sobre esse cliente, como o tipo de serviço que ele contratou, há quanto tempo seu contrato está vigente, etc. Com essas informações, criaremos o modelo.

Utilizaremos o PySpark para fazer isso, principalmente o modo Spark DataFrame SQL e o MLlib. Com essa ferramenta faremos todo o pipeline do machine learning, passando pela etapa de tratamento dos dados, ajuste dos modelos por meio de algoritmos, otimização desses modelos encontrando os melhores hiperparâmetros e, por fim, a validação dos modelos.

Ao final do pipeline, entregaremos um modelo capaz de realizar a classificação de novos clientes entre provável cancelamento do serviço ou não, oferecendo essa previsão. Ou seja, teremos um modelo com tuning, otimizado para o nosso problema.
