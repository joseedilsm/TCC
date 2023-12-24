# TCC

Esse repositorio vai servir para que eu possa inserir códigos já realizados em relação ao meu TCC.
A seguir o objetivo dos arquivos:

Os arquivos create_tests servem tanto para treinar os modelos quanto para criar os exemplos adversariais que serão utilizados por todos os classificadores.

Os arquivos Exp1 e Exp2 realizam os experimentos para os respectivos datasets sem e com destilação defensiva respectivamente.

Os arquivos create_trains servem para criar exemplos adversariais sobre o conjunto de treino que posteriomente podem ser usados para treinar classificadores e ver se eles adquirem mais robustez por terem exemplos adversariais presentes no treinamento. Os dados desse arquivo não chegaram a ser utilizados no experimento.

Para os códigos funcionarem, tem que ser criadas as pastas "data", "model", "custom_datasets" e "custom_train_datasets" na mesma pasta onde os arquivos estiverem presentes.
