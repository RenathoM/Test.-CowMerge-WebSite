# 🐄 Merge Cow 3D - Voxel Edition

Um jogo web incremental (Idle/Merge) em 3D renderizado diretamente no navegador. Compre vacas, junte-as para descobrir novas espécies, enriqueça e sobreviva a eventos caóticos numa ilha flutuante construída em Voxel Art.

## 🌟 Funcionalidades Principais

* **Gráficos 3D no Browser:** Desenvolvido com **Three.js**, apresentando iluminação dinâmica, sombras suaves e um estilo visual "Voxel" apelativo.
* **Mecânica de Merge Física:** Arraste e solte vacas do mesmo nível com o oouse para fundi-las numa espécie superior.
* **Inteligência Artificial (Pathfinding):** As vacas movimentam-se livremente pelo pasto, desviam-se de obstáculos (celeiro, árvores, cercas) e procuram erva para comer quando estão com fome.
* **Economia Idle:** As vacas bem alimentadas produzem dejetos que geram dinheiro ao serem recolhidos.
* **Leaderboard Global:** Placar mundial em tempo real (separado por Fortuna e Vacas Spawnadas) integrado com **Supabase** e identificação de país por bandeiras (API GeoJS).
* **Coleção de Espécies:** Um compêndio interativo para acompanhar as variantes de vacas desbloqueadas.
* **Áudio Procedural:** Todos os efeitos sonoros (vento, chuva, passos, mugidos e sintetizadores de compra/merge) são gerados nativamente pela **Web Audio API**, sem necessidade de ficheiros `.mp3` externos.

---

## 🌩️ Eventos Dinâmicos e Aleatórios

O jogo conta com um ecossistema vivo onde eventos inesperados podem ocorrer:

* **☄️ Queda de Meteoro (5% de chance/min):** O céu fica roxo, a câmara treme e um meteoro cai, destruindo as vacas comuns. O jogador deve clicar 100 vezes no meteoro para libertar a rara **Vaca Alienígena**.
* **🛸 Abdução OVNI (10% de chance/min):** Um disco voador sobrevoa a ilha, ilumina uma vaca com um raio trator e leva-a para o espaço sideral.
* **⛈️ Inundação (30% de chance/min):** Nuvens escuras formam-se, a chuva e os trovões começam, inundando o pasto. Uma **Vaca Inundação** surge a surfar para drenar a água e proteger a ilha.

*(Nota: Os eventos também podem ser ativados manualmente através do "Controle de Eventos" na interface do jogo).*

---

## 🎮 Como Jogar (Controlos)

* **Botão Esquerdo do Mouse:** Clicar nos botões da UI, recolher dejetos (dinheiro) e **Arrastar** as vacas para fundi-las.
* **Botão Direito do Mouse:** Clicar e arrastar no cenário para **Orbitar/Rodar** a câmara.
* **Scroll do Mouse (Roda):** Fazer **Zoom In/Zoom Out** no mapa.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3:** Interface em *Glassmorphism*.
* **JavaScript (ES6+):** Lógica principal.
* **[Three.js](https://threejs.org/):** Motor de renderização gráfica 3D.
* **Web Audio API:** Síntese sonora procedural.
* **[Supabase](https://supabase.com/):** Banco de dados (PostgreSQL) para o Leaderboard em nuvem.
* **[GeoJS](https://www.geojs.io/):** API para capturar o código do país do jogador.
* **[FlagCDN](https://flagcdn.com/):** Fornecimento visual das bandeiras no placar.

---

## 🚀 Como Executar o Projeto Localmente

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/merge-cow-3d.git](https://github.com/seu-usuario/merge-cow-3d.git)
