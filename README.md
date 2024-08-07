# Java BlackJack Console Game

## Overview

This Java-based BlackJack game simulates a multiplayer BlackJack experience. It includes the functionality for players to join a game, interact with a dealer, and play according to the standard BlackJack rules. The project also includes server-client architecture to manage multiple players.

## Features

- **Card Deck Management**: Shuffling and dealing cards from the deck.
- **Player and Dealer Interaction**: Players can hit or stand, and the dealer manages the game flow.
- **Multiplayer Support**: Server-client architecture to handle multiple players in a game.

## File Structure

### `src/main/java/BlackJackProject` Directory

- **`BlackJackGame.java`**: Main class to initiate and manage the BlackJack game.
- **`CardDeck.java`**: Manages the deck of cards, including shuffling and dealing.
- **`Dealer.java`**: Handles the dealer's actions in the game.
- **`Hand.java`**: Represents a player's hand of cards.
- **`Message.java`**: Manages messages exchanged between the server and clients.
- **`Player.java`**: Represents a player in the game.
- **`PlayingCard.java`**: Represents a single playing card, including its suit and value.

### `src/main/java/BlackJackProject/Client` Directory

- **`Client.java`**: Handles client-side communication with the server.
- **`ClientSecond.java`**: An additional client implementation for secondary functionality.

### `src/main/java/BlackJackProject/Server` Directory

- **`DealerHandler.java`**: Manages interactions between the dealer and the players.
- **`Server.java`**: Sets up and manages the server-side of the game, including handling multiple clients.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/jmwoodrow33/JavaProjectJMWBlackJack.git
    cd JavaProjectJMWBlackJack
    ```

2. **Build the project using Maven**:
    ```bash
    mvn clean install
    ```

3. **Run the server**:

4. **Run the client**:

## Usage

- **Starting the Game**: Run the server first, then start multiple clients to join the game.
- **Gameplay**: Players can hit or stand, and the dealer manages the game flow according to BlackJack rules.
- **Multiplayer Support**: Multiple clients can join the game simultaneously.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

