# 🧭 Compass Navigator Loader

Uma tela de carregamento elegante e técnica que utiliza o movimento de uma bússola magnética para representar a busca e o processamento de informações.

## 💡 O Conceito
A ideia é transformar o tempo de espera em uma experiência de navegação. A agulha da bússola não gira apenas em círculos; ela oscila e busca o "norte" (o ponto de conclusão do carregamento), transmitindo a ideia de que o sistema está localizando os dados com precisão.

### 🧩 Elementos Visuais
* **A Rosa dos Ventos:** Uma grade de fundo detalhada com pontos cardeais (N, S, E, W).
* **A Agulha Magnética:** O elemento principal que reage ao progresso, estabilizando conforme o carregamento chega a 100%.
* **O Aro Giratório:** Um anel externo que rotaciona lentamente para indicar que o sistema não está travado.

---

## 🎨 Design e Estilo

Este loader combina um visual clássico com tecnologia moderna:

| Componente | Estilo | Efeito |
| :--- | :--- | :--- |
| **Agulha** | Bicolor (Vermelho/Prata) | Oscilação magnética (Ease-in-out) |
| **Mostrador** | Minimalista / Dark Mode | Opacidade variável nas marcações |
| **Brilho** | Neon sutil nas pontas | Efeito de "radar" integrado |

---

## 🛠️ Detalhes Técnicos

A implementação foca em suavidade matemática para replicar a física de um imã:

* **Physics-based Animation:** Uso de funções de tempo cúbicas para simular a inércia da agulha.
* **SVG Vectorial:** Garante que os detalhes da rosa dos ventos permaneçam nítidos em qualquer zoom.
* **CSS Custom Properties:** Permite mudar o "Norte" da bússola dinamicamente via JavaScript.

<img width="228" height="243" alt="Image" src="https://github.com/user-attachments/assets/03322055-5a1a-4a98-acf7-d8c4addabcd9" />
