# Django
Django é um framework para aplicações web gratuito e de código aberto, escrito em Python. Quando você está construindo um site, sempre precisa de um conjunto similar de componentes: uma maneira de lidar com a autenticação do usuário (inscrever-se, fazer login, fazer logout), um painel de gerenciamento para o seu site, formulários, uma forma de upload de arquivos, etc. O framework Django serve justamente para isso que já te dá os componentes prontos para usar.

- Model, a parte **M** do MTV. O modelo é a parte que interage com o banco de dados.
- View, a parte **V** do MTV. Recebe os dados que o Model obteve na base de dados, faz o processamento matemático/lógico necessário e envia estes dados já formatados para o template.
- Template, a parte **T** do MTV. Nessa camada é onde irá ficar a interface do sistema. É através do template que o usuário interage com um site Django.
