
<img src = "https://github.com/DevGuiMuniz/Hospital-Fundamental-DataBase/blob/main/hospital.png" > <h1> Hospital Muniz e seus dados</h1>

<img height="160" width="120" src = "https://github.com/DevGuiMuniz/Hospital-Muniz-e-seus-dados/blob/main/mysql-original-wordmark.svg" >


## Parte 1 - Diagrama Entidade Relacionamento.

<li> O hospital necessita de um sistema para sua área clínica que ajude a controlar consultas realizadas. Os médicos podem ser generalistas, especialistas ou residentes e têm seus dados pessoais cadastrados em planilhas digitais. Cada médico pode ter uma ou mais especialidades, que podem ser pediatria, clínica geral, gastroenterologia e dermatologia. Alguns registros antigos ainda estão em formulário de papel, mas será necessário incluir esses dados no novo sistema.</li>

<li> Os pacientes também precisam de cadastro, contendo dados pessoais (nome, data de nascimento, endereço, telefone e e-mail), documentos (CPF e RG) e convênio. Para cada convênio, são registrados nome, CNPJ e tempo de carência. </li>

<li> As consultas também têm sido registradas em planilhas, com data e hora de realização, médico responsável, paciente, valor da consulta ou nome do convênio, com o número da carteira. Também é necessário indicar na consulta qual a especialidade buscada pelo paciente. </li>


<li> Deseja-se ainda informatizar a receita do médico, de maneira que, no encerramento da consulta, ele possa registrar os medicamentos receitados, a quantidade e as instruções de uso. A partir disso, espera-se que o sistema imprima um relatório da receita ao paciente ou permita sua visualização via internet. </li>

## Modelagem

<img src = "https://github.com/DevGuiMuniz/Hospital-Fundamental-DataBase/blob/main/Modelagem-Oficial.png">

## Parte 2 - Diagrama Entidade Relacionamento 

<li>Para cada internação, são anotadas a data de entrada, a data prevista de alta e a data efetiva de alta, além da descrição textual dos procedimentos a serem realizados.</li>
<li>As internações precisam ser vinculadas a quartos, com a numeração e o tipo.</li>
<li>Cada tipo de quarto tem sua descrição e o seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria).
</li>
<li>Também é necessário controlar quais profissionais de enfermaria estarão responsáveis por acompanhar o paciente durante sua internação. Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE).</li>
<li>A internação, obviamente, é vinculada a um paciente – que pode se internar mais de uma vez no hospital – e a um único médico responsável.</li>
<li>Por último, crie um script SQL para a geração do banco de dados.</li>
