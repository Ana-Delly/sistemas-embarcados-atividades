Atividade X — Nome da atividade

Plataforma e link
Plataforma: Tinkercad, Wokwi ou outra
https://www.tinkercad.com/things/4BFaxAPfF1R/editel?returnTo=%2Fclassrooms%2F7OjAnbHLZRm%2Factivities%2F4iyOzX8sN5v%3Fview%3Dwork%26type%3Dall
imagem do prototipo
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6b0999f9-eb92-41e7-9344-1e19e9ef24a5" />
Componentes utilizados
Arduino Uno
Liste os demais componentes
1 LED vermelho 1 LED amarelo 1 LED verde 1 botão (push button) 3 resistores de 220 Ω 1 resistor de 10 kΩ (para o botão, caso não utilize INPUT_PULLUP) Jumpers

1 protoboard

Como funciona
Explique os estados do sistema, o que provoca cada mudança de estado e o comportamento dos componentes.

Como funciona o sistema O semáforo começa com o LED vermelho aceso. Ao pressionar o botão, ele muda para verde, depois amarelo e, em seguida, volta para vermelho. Cada pressionamento permite apenas uma mudança de estado. O estado atual também é exibido no Monitor Serial. Dados do sistema

Entradas: botão conectado ao pino 2.
Saídas: LEDs vermelho (pino 8), amarelo (pino 9) e verde (pino 10).
Variável: estadoAtual, responsável por armazenar o estado do semáforo.
Comunicação: Monitor Serial, configurado em 9600 baud.
Linguagem: C++ (Arduino). Objetivo: utilizar estados e transições para controlar o funcionamento de um semáforo eletrônico.
Testes realizados
Entrada ou condição testada: Pressionar o botão conectado ao pino 2 do Arduino para mudar o estado do semáforo.

Resultado esperado: O semáforo deve mudar de vermelho para verde, depois amarelo e retornar ao vermelho, avançando apenas uma vez por clique.

Resultado observado: O sistema funcionou corretamente, os LEDs mudaram na sequência esperada e os estados foram exibidos no Monitor Serial.
