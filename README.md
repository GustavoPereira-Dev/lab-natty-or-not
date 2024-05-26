# Título do Projeto Extremamente Aesthetic ;)

## 📒 Descrição
Este projeto explora a visão da utilização de uma IA Generativa, que por sua vez, demonstra aspectos como criação de texto, de códigos e de imagens

## 🤖 Tecnologias Utilizadas
1. Microsoft Copilot - A IA Generativa gratuita disponibilizada pela Microsoft
2. DALL-E 3 - IA exclusiva para o desenvolvimento de imagens, que é também disponibilizada no Microsoft Copilot

## 🧐 Processo de Criação
1. Acessei o site da Microsoft Copilot
2. Comecei a passar prompts para a IA Generativa desenvolver resenhas críticas de filmes (Her e Matrix) e escolhi o estilo de conversa "Mais preciso"
3. Pedi para desenvolver uma classe na linguagem de programação Python chamada "Programador", e cheguei a fazer umas adições de conteúdos nos prompts seguintes
4. Mudei a GPT do Copilot para "Designer" e passei prompts para desenvolver imagens com a DALL-E acoplada no sistema para personagem uma de anime, mascote do Python e IA
## 🚀 Resultados
### Textos
#### Resenha do filme "Her"
<code>“Her” (Ela), dirigido por Spike Jonze, é um filme que surpreende e encanta, trazendo uma crítica à modernidade e às relações humanas no mundo atual. O filme conta a história de Theodore Twombly (interpretado por Joaquin Phoenix), um homem introvertido que se apaixona por seu sistema operacional, Samantha (voz de Scarlett Johansson).
Theodore é um escritor de cartas de amor para pessoas que têm dificuldades em expressar seus próprios sentimentos. Ele vive uma existência solitária, tendo apenas a tecnologia como aliada no dia a dia. Samantha, por outro lado, é um sistema operacional com inteligência artificial que evolui e se adapta conforme interage com seres humanos 
O relacionamento entre Theodore e Samantha é complexo e profundo. Samantha não é humana, mas desenvolveu sua consciência, assimilou sentimentos e emoções humanas e conseguiu interpretá-las e representá-las. Ela aprende tudo sobre a humanidade buscando conhecimento em livros, filmes, obras e tudo mais que tem disponível na internet. 
O filme é sutil e profundo, pois trata de sentimentos humanos sendo processados por uma máquina que aprende e evolui com as atividades e interações humanas. Ele levanta questionamentos sobre o que é real e o que é amor. A atuação de Scarlett Johansson, mesmo que apenas por voz, é brilhante e expressiva. 
No entanto, o filme também tem seus momentos lentos, que podem não agradar a todos. Mas, no geral, “Her” é um filme que faz pensar e refletir sobre a natureza das relações humanas na era da tecnologia. </code>

#### Resenha do filme "Matrix"
<code>“Matrix”, dirigido pelas irmãs Lilly e Lana Wachowski e lançado em 1999, é um filme de ficção científica e ação que se tornou um ícone dentro do mundo cyberpunk. O filme acompanha a aventura de Neo (interpretado por Keanu Reeves), um jovem hacker que é chamado para o movimento de resistência liderado por Morpheus (Laurence Fishburne), na luta contra a dominação dos humanos pelas máquinas. 
Neo, durante o dia, é um programador e à noite trabalha como hacker. Ele é contactado por Morpheus e Trinity (Carrie-Anne Moss), descobrindo a verdade da Matrix. A partir daí, ele descobre que é o Escolhido, alguém que virá a salvar a Humanidade da simulação. Embora demore para tomar consciência do seu papel, acaba dominando os seus poderes e liderando o grupo. 
O filme Matrix é complexo e atua sob diferentes camadas que retomam às origens do pensamento ocidental. Ele carrega uma carga filosófica bastante grande, como o Mito da Caverna de Platão, que mostra, no filme, como os humanos aprisionados na simulação farão de tudo para proteger o sistema e evitar que os humanos livres tragam alguma mudança para a simulação.
No entanto, apesar de toda a parte tecnológica e enredo apelativo para o público em geral, como presença de cenas de ação, lutas e trocas de tiro, o filme também tem seus momentos lentos, que podem não agradar a todos. Mas, no geral, “Matrix” é um filme que faz pensar e refletir sobre a natureza das relações humanas na era da tecnologia. </code>

#### Código em Python de uma classe chamada "Programador"
<code>
    
    class Programador:
        def __init__(self, nome, linguagens, proficiencia, conhecimentos):
            self.nome = nome
            self.linguagens = linguagens
            self.proficiencia = proficiencia
            self.conhecimentos = conhecimentos
            
        def apresentar(self):
            print(f"Olá, meu nome é {self.nome}.")
            for linguagem, proficiencia in self.proficiencia.items():
                print(f"Eu programo em {linguagem} com proficiência {proficiencia}.")
                if linguagem in self.conhecimentos:
                    print(f"Em {linguagem}, eu tenho experiência com {', '.join(self.conhecimentos[linguagem])}.")
    
        def aprender_nova_linguagem(self, nova_linguagem, proficiencia):
            if nova_linguagem not in self.linguagens:
                self.linguagens.append(nova_linguagem)
                self.proficiencia[nova_linguagem] = proficiencia
                print(f"{self.nome} agora também programa em {nova_linguagem} com proficiência {proficiencia}.")
            else:
                print(f"{self.nome} já programa em {nova_linguagem}.")
    
        def aprender_novo_conhecimento(self, linguagem, novo_conhecimento):
            if linguagem in self.linguagens:
                if linguagem not in self.conhecimentos:
                    self.conhecimentos[linguagem] = []
                if novo_conhecimento not in self.conhecimentos[linguagem]:
                    self.conhecimentos[linguagem].append(novo_conhecimento)
                    print(f"{self.nome} agora também tem experiência com {novo_conhecimento} em {linguagem}.")
                else:
                    print(f"{self.nome} já tem experiência com {novo_conhecimento} em {linguagem}.")
            else:
                print(f"{self.nome} ainda não programa em {linguagem}.")
    
    
    joao = Programador("João", ["Python", "Java"], {"Python": "Intermediário", "Java": "Avançado"}, {"Python": ["Django"]})
    joao.apresentar()
    joao.aprender_nova_linguagem("JavaScript", "Básico")
    joao.aprender_novo_conhecimento("Python", "TensorFlow")
    joao.apresentar()

</code>

### Imagens

#### Personagem de animação (anime) 
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/61cff9be-42fd-4358-8e5f-15a781cf4058)
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/49d38de5-df0f-4803-9a01-2ffaf414040d)
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/a48eb53d-e641-4e3c-a1b9-d45bf4118038)

#### Mascote do Python
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/7c09fb5a-c564-430d-ae03-773d46e746f1)
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/8906b19b-3dd7-496a-8b71-d6d456d145d9)
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/83e142bf-b138-4801-b7a9-e6c9b2ef0768)

#### Inteligência Artificial e IA Generativa
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/bee92d6a-a794-4a2f-9252-db8262a4bacc)
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/0a0b1d05-da6c-49b8-aeaf-6b8d623eb781)
![image](https://github.com/GustavoPereira-Dev/lab-natty-or-not/assets/108029506/24d95242-631e-4285-9910-9f78e7d75cc8)




## 💭 Reflexão (Opcional)
Concluindo, mesmo no curto tempo que desenvolvi para desenvolver esse projeto, é possível perceber que, assustadoramente, os resultados de saída (principalmente os de resenha) tem uma qualidade impressionamente, que não aparenta ser tão robótico e tendo somente umas pequenas correções a se fazer para se assemelhar com algo mais real
Assim, entra aquela questão da relação de IA com o mundo externo: ela pode fazer e desenvolver bastante coisa, mas também um melhoramento e embassamento na área auxilia o texto parecer mais real, sendo um belo de um otimizador de tempo para desenvolver suas tarefas mais simples ou até um pouco mais medianas.

