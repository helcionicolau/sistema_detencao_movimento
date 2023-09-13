# sistema_detencao_movimento
Este sistema é de detenção de movimento, um sistema de intrusão. Construído com Python, IA na ponta do teclado😁



Detecção de Movimento com Python

««Visão Geral»»
Este projeto consiste em um sistema de detecção de movimento usando Python e OpenCV. Ele utiliza a câmera do computador para detectar alterações no ambiente e emitir um alarme sonoro se o movimento for detectado.

««Pré-Requisitos»»
Python: Certifique-se de ter o Python instalado na sua máquina. Você pode baixar o Python em python.org.

OpenCV: O OpenCV é usado para capturar vídeos da câmera e processá-los. Você pode instalá-lo usando o pip:

pip install opencv-python


imutils: O pacote imutils é usado para facilitar a manipulação de imagens. Você pode instalá-lo com o seguinte comando:

pip install imutils


Executando o Sistema de Detecção de Movimento
Clone ou faça o download deste repositório para o seu computador.

Navegue até o diretório onde o código do sistema de detecção de movimento está localizado.

Abra o arquivo motion_detection.py em um editor de texto ou ambiente de desenvolvimento Python. Te recomendo usar o Jupyter😉

Certifique-se de que a sua câmera esteja conectada e funcional, ou se tiveres externas, melhor ainda, porcausa da Performance...

Execute o script Python com o seguinte comando:

python motion_detection.py

A janela da câmera será exibida, mostrando a imagem capturada pela sua câmera.

Pressione a tecla "a" (`A` porcausa do Meu Nome `António`😅) para ativar ou desativar o modo de alarme. Quando o modo de alarme está ativado, o sistema irá detectar movimento e emitir um alarme sonoro se o movimento for detectado.

Para sair do programa, pressione a tecla "f" (O `F` é um mistério...😂😎).

««Personalização»»

Você pode personalizar este sistema de detecção de movimento ajustando os seguintes parâmetros no código:

cap = cv2.VideoCapture(0, cv2.CAP_DSHOW): Você pode mudar o índice (0) para usar uma câmera diferente, se houver várias câmeras conectadas ao seu computador. (Podes alterar do seu jeito o sistema, só não esqueça de seguir o meu perfil aqui, e meu canal do youtube: https://youtu.be/rBfMr8TV7-A?si=dGEGXnoicHRp6k4O)

cap.set(cv2.CAP_PROP_FRAME_WIDTH, 640) e cap.set(cv2.CAP_PROP_FRAME_HEIGHT, 480): Você pode alterar a largura e a altura do quadro de captura de vídeo.

threshold = cv2.threshold(difference, 25, 255, cv2.THRESH_BINARY)[1]: Você pode ajustar o valor de limite para definir o nível de sensibilidade à detecção de movimento.

««Notas Finais»»

Este sistema de detecção de movimento é uma ótima base para projetos mais avançados de segurança e automação residencial. Sinta-se à vontade para explorar e personalizar o código para atender às suas necessidades específicas.

Se você tiver alguma dúvida ou encontrar problemas, não hesite em abrir uma issue neste repositório para obter suporte adicional.

Aproveite o seu sistema de detecção de movimento Python e celebre o Dia do Programador! 🎉
