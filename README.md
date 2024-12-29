Calculadora Científica em Tkinter ✨
Este projeto é uma calculadora científica desenvolvida em Python usando a biblioteca Tkinter para a interface gráfica. Ela realiza operações matemáticas básicas e também operações com potências, utilizando o operador ^.

Funcionalidades 🎯
Operações Básicas: Soma, subtração, multiplicação e divisão.

Potências: Cálculo de potências com o operador ^.

Teclado Interativo: Controle via botões e teclado.

Limpeza da Tela: Pressione "C" para limpar a entrada.

Calculadora Científica: Realização de cálculos mais complexos.

Tecnologias Utilizadas ⚙️

Python: versão 3.8 ou superior

Tkinter: Biblioteca padrão do Python para interfaces gráficas.

math: Funções matemáticas para cálculos avançados.

Instalação 🚀

Clone o repositório:
git clone https://github.com/seu-usuario/calculadora-em-tkinter.git
Instale as dependências: Não há pacotes externos, apenas bibliotecas padrão do Python.

Execute o projeto: Navegue até o diretório do projeto e execute:
python main.py
A interface gráfica será aberta e você poderá realizar cálculos diretamente pela tela de botões.

Como Funciona 🧠
Interface Gráfica
A interface foi construída com Tkinter e apresenta botões para cada número e operação, além de um display para exibir a expressão e o resultado.

Eventos de Teclado
Pressione Enter/Return para realizar o cálculo da expressão inserida.
A entrada é corrigida antes de ser avaliada, removendo caracteres inválidos e corrigindo operadores repetidos.
Cálculos
eval() é usado para calcular a expressão inserida.
Potências são tratadas de forma separada, garantindo que o operador ^ funcione corretamente.
Estrutura do Código 🗂️

Funções de Criação de Componentes (calculator_factories.py)

make_root: Cria a janela principal da calculadora.

make_label: Cria o rótulo para exibir o resultado ou erros.

make_display: Cria o campo de entrada para a expressão.

make_buttons: Cria os botões para números e operações.

Classe Calculator (calculator_class.py)

start: Configura os botões, o display e inicia o loop do Tkinter.

_config_buttons: Configura os botões e suas ações.

_config_display: Configura o comportamento do display.

calculate: Realiza o cálculo da expressão.

_fix_text: Corrige a entrada antes de calcular.

_get_equations: Divide a expressão para o cálculo de potências.

Exemplos de Uso 🧮

Somando 2 + 3:
Clique nos botões 2, +, 3 e depois em =.
Resultado: 2 + 3 = 5.

Calculando a potência 2 ^ 3:
Clique nos botões 2, ^, 3 e depois em =.
Resultado: 2 ^ 3 = 8.

Limpar a Tela:
Clique no botão C para limpar a entrada.

Como Contribuir 💡
Faça um fork do projeto.
Crie uma branch para a feature:

git checkout -b feature/nome-da-feature
Realize suas alterações e faça commit:

git commit -m 'Adiciona nova funcionalidade'
Envie para o repositório:

git push origin feature/nome-da-feature

Abra um pull request.

Licença 📄
Este projeto é licenciado sob a Licença MIT. Sinta-se à vontade para usar, modificar e distribuir!

