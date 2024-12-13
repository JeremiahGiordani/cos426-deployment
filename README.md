# Pennsylvania Turnpike Simulator  

**Deployed Demo:** [https://jeremiahgiordani.github.io/cos426-deployment/](https://jeremiahgiordani.github.io/cos426-deployment/)  

## Overview  

The *Pennsylvania Turnpike Simulator* is an interactive 3D racing-style game built using the ThreeJS framework. In this game, players navigate a simulated Pennsylvania Turnpike, avoiding collisions with NPC vehicles and aiming to complete the course successfully. The game features dynamic road loading, responsive controls, and adaptive difficulty to create an engaging and immersive experience.  

## Gameplay Features  

- **Dynamic Road Loading**: The road is loaded in chunks as the player progresses, ensuring smooth gameplay with minimal latency.  
- **Health Bar**: A real-time health bar is displayed at the top of the screen.  
  - Your health decreases when you collide with NPC vehicles or stray outside the road boundaries.  
  - Passing a checkpoint restores your health to full, offering a chance to recover and continue.  
- **Checkpoints**: As you drive, you'll pass checkpoints that not only restore your health but also mark your progress through the game.  
- **Player Controls**: Use `W`, `A`, `S`, and `D` to steer your car, accelerate, and decelerate.  
- **Popups for Success and Failure**:  
  - If your health reaches zero, a "Jail" popup appears, simulating consequences for reckless driving.  
  - If you reach the finish line, a congratulatory popup shows your time and distance traveled.  

## How to Play  

1. Use the `W` key to accelerate, `A` and `D` to steer, and `S` to brake.  
2. Avoid collisions with NPC vehicles to conserve your health.  
3. Pass through checkpoints to restore your health to full.  
4. Try to reach the finish line while managing your speed and avoiding hazards.  

## Project Details  

This project was developed using the COS 426 project template and includes assets sourced from [https://poly.pizza/](https://poly.pizza/) for 3D models. Checkpoints were customized using Adobe Photoshop and Adobe Substance Viewer to create Pennsylvania Turnpike-specific textures and designs.  

## Writeup  

A detailed writeup explaining the design, implementation, and methodology of the game can be found in the file `Project_Report.pdf` included in this repository.  

## Installation and Running Locally  

1. Clone the repository:  
   ```bash
   git clone https://github.com/jeremiahgiordani/cos426-deployment.git
   cd cos426-deployment
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Start the development server:  
   ```bash
   npm start
   ```  
4. Open the game in your browser at `http://localhost:8080`.  

## License  

This project is for educational purposes as part of COS 426 coursework and may not be used for commercial purposes.  

## Acknowledgements

This code was based on the template for this course, found here: [COS 426 Final Project Template](https://github.com/adamfinkelstein/cos426finalproject)

NPCs and objects were obtained from [Poly Pizza](https://poly.pizza/).

The following objects were used, with their corresponding references:

- **Road**: Highway by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/0iOOmcNC19A)
- **Billboard**: Billboard by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/2Kl87jaGQEB)
- **Player**: Red Car by J-Toastie [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/dVLJ5CjB0h)
- **80s Car**: 80s Car by Nick Ladd [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/7tPSW5UYD20)
- **Ambulance**: Ambulance by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/8NOFImgkI5N)
- **Bus**: Bus by jeremy [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/bsvS0E1eo4R)
- **Standard Car 1**: Car by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/75h3mi6uHuC)
- **Standard Car 2**: Car by Quaternius via [Poly Pizza](https://poly.pizza/m/Cz6yDaUcM9)
- **Cop Car**: Police Car by Quaternius via [Poly Pizza](https://poly.pizza/m/BwwnUrWGmV)
- **Firetruck**: Fire Truck by Ivan Klus [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/7iHJ519SwxG)
- **Taxi**: Taxi by Ivan Klus [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/7iHJ519SwxG)
- **Truck**: Truck by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via [Poly Pizza](https://poly.pizza/m/36sY8cTSgKL)

---  

Feel free to reach out with any questions or feedback!  