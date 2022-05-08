## 780_Projeto1_MarioHenriqueRomagnaCesa

O objetivo do projeto será desenvolver um estudo no dataset `COVID.csv`, base esta que contém informações sobre casos de COVID. Ou seja a partir do diagnóstico de sintomas e informações dos pacientes deve-se desenvolver um modelo para prever casos confirmados de COVID.



A descrição das variáveis contidas no dataset pode ser encontradas a seguir:

 - **id**: Identificação do paciente
 - **sex**: Sexo do Paciente (0 - Homem / 1 - Mulher)
 - **patient_type**: Se o paciente foi dispensado para casa (1) ou se foi internado (0)
 - **intubed**: Seo paciente foi intubado ou não
 - **pneumonia**: Se o paciente apresentou pneumonia ou não
 - **age**: Idade do Paciente
 - **pregnancy**: Se a paciente estava grávida ou não (para pacientes mulheres)
 - **diabetes**: Se o paciente tem diabetes ou não
 - **copd**: Se opaciente tem COPD ou não
 - **asthma**: Se o paciente tem Asma ou não
 - **inmsupr**: Se o paciente apresentou Imunosupressão ou não
 - **hypertension**: Se o paciente tem hipertensão ou não
 - **ohter_disease**: Se o paciente tem outras doenças ou não
 - **cardiovascular**: Se o paciente tem doenças cardiácas ou não
 - **obesity**: Se o paciente tem obesidade ou não
 - **renal_chronic**: Se o paciente tem problemas renais ou não
 - **tobacco**: Se o paciente é fumante ou não
 - **contact_other_covid**: Se o paciente teve contato com outras pessoas diagnosticadas com covid
 - **icu**: Se o paciente precisou ser internado na UTI
 - **covid_res**: Se o resultado do teste foi Positivo ou Negativo
 
PAra ajudar no desenvolvimento do projeto, vamos separar o projeto em algumas seções, conforme descritas a seguir:

- Preparação dos Dados e Verificação de Consistência: Neste tópico deve ser feita a verificação da consistência dos dados e caso necessário efetuar eventuais modificações na base de dados. Alguns dos procedimentos que podemos fazer aqui são: Remoção e/ou tratamento de valores faltantes, remoção de duplicatas, ajustes dos tipos de variáveis, análise de _outliers_ entre outras;



- Análise Exploratória dos Dados: Para fazermos a modelagem, precisamos conhecer muito bem os dados que estamos trabalhando. Por isso, nesta parte do projeto vocês desenvolveram an´laises e gráficos a respeito dos dados que estão utilizando. Tente tirar ao máximo informaç~eos sobre as variáveis em si e suas relações com as demais;



- Modelagem dos Dados: Nesta parte, vamos modelar um classificador para os resultados dos exames de COVID (`covid_res`). VocÊs deveram __treinar pelo menos 3 modelos__ (podendo testar mais que 3 também) e de acordo com alguma métrica de avaliação (escolhida por vocÊs), decidir qual será o melhor modelo a ser utilizado!;



- Otimização do Modelo: A partir do modelo escolhido no tópico anterior, vamos tentar aprimorar e garantir um melhor desempenho no modelo, seja fazendo validação cruzada, otimização de parâmetros com _GridSearchCV_ ou _RandomizedSearchCV_ e até mesmo testar diferentes _thresholds_ (ao invés de utilizar a função _predict_ do modelo, utilize a função _predict_proba_ do modelo e a partir das probabilidades determinar qual vai ser o limiar onde será considerado um caso positivo ou negativo);
r>

- Conclusões sobre o Projeto: Para finalizar, descreva as suas conclusões sobre o desenvolvimento do modelo e os resultados obtidos.